oc apply -f manifests

oc adm policy add-scc-to-user privileged system:serviceaccount:metricbeat:metricbeat
