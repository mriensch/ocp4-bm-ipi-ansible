Things youll need: (which are Not provided by this repo)
oc-mirror tar
mirrored tar
openshift-baremetal-install tar
oc (openshift client) tar
redhat coreos image


obtain the required tars and put them in bin.
obtain the required rhcos image and put it in roles/image-cache/files

Certs are also need, there is a script provided in roles/registry/files that will generate with openssl.


the only configuration needed is group_vars/all.yml
	* the above location can be changed via that file
