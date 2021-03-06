# Dashboard

## General
* The dashboard view of the status page will be accessible by clicking the dashboard icon next to the page title, and will include information regarding `Health`, `Resource Quotas`, `Resource Usage`, and project `Details`.

### Resource Quotas

![even](img/quota-even.png)

![odd](img/quota-odd.png)
* Resource quotas will be shown on the dashboard view in individual cards.
* The card title will be the name of the resource quota, and will link to the resource quota's [details page](http://openshift.github.io/openshift-origin-design/web-console/4.0-designs/resource-quota/resource-quota).
* Four gauges will show CPU Request, CPU Limit, Memory Request, and Memory Limit.
  * If a resource quota does not specify any of these four quotas, the resource quota will not be displayed on the dashboard.
* The scope of the resource quota will be listed below the gauges.
* If there is an odd number of resource quotas, leave a blank space next to the last card.
