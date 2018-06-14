# openshift-templates

Instead of defining service account in other project in template:
``oc policy add-role-to-user view system:serviceaccount:<PROJECT>:turbine -n <HYSTRIX_PROJECT>``
