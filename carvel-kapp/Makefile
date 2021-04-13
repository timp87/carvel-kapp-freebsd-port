# Created by: Pavel Timofeev <timp87@gmail.com>
# $FreeBSD$

PORTNAME=	carvel-kapp
PORTVERSION=	0.36.0
DISTVERSIONPREFIX=	v
CATEGORIES=	sysutils

MAINTAINER=	timp87@gmail.com
COMMENT=	Simple deployment tool for Kubernetes

LICENSE=	APACHE20

USES=		go:modules
USE_GITHUB=	yes
GH_ACCOUNT=	vmware-tanzu

GH_TUPLE=	\
		Azure:go-autorest:v10.15.0:azure_go_autorest/vendor/github.com/Azure/go-autorest \
		cppforlife:cobrautil:bb86e6965d72:cppforlife_cobrautil/vendor/github.com/cppforlife/cobrautil \
		cppforlife:color:6706ac40b835:cppforlife_color/vendor/github.com/cppforlife/color \
		cppforlife:go-cli-ui:1e47f820817f:cppforlife_go_cli_ui/vendor/github.com/cppforlife/go-cli-ui \
		cppforlife:go-patch:v0.2.0:cppforlife_go_patch/vendor/github.com/cppforlife/go-patch \
		davecgh:go-spew:v1.1.1:davecgh_go_spew/vendor/github.com/davecgh/go-spew \
		dgrijalva:jwt-go:v3.2.0:dgrijalva_jwt_go/vendor/github.com/dgrijalva/jwt-go \
		ghodss:yaml:v1.0.0:ghodss_yaml/vendor/github.com/ghodss/yaml \
		go-inf:inf:v0.9.1:go_inf_inf/vendor/gopkg.in/inf.v0 \
		go-yaml:yaml:9f266ea9e77c:go_yaml_yaml_1/vendor/gopkg.in/yaml.v3 \
		go-yaml:yaml:v2.2.8:go_yaml_yaml/vendor/gopkg.in/yaml.v2 \
		gogo:protobuf:v1.2.1:gogo_protobuf/vendor/github.com/gogo/protobuf \
		golang:appengine:v1.6.1:golang_appengine/vendor/google.golang.org/appengine \
		golang:crypto:f99c8df09eb5:golang_crypto/vendor/golang.org/x/crypto \
		golang:glog:23def4e6c14b:golang_glog/vendor/github.com/golang/glog \
		golang:net:3b0461eec859:golang_net/vendor/golang.org/x/net \
		golang:oauth2:0f29369cfe45:golang_oauth2/vendor/golang.org/x/oauth2 \
		golang:protobuf:v1.4.1:golang_protobuf/vendor/github.com/golang/protobuf \
		golang:sys:33540a1f6037:golang_sys/vendor/golang.org/x/sys \
		golang:text:v0.3.2:golang_text/vendor/golang.org/x/text \
		golang:time:9d24e82272b4:golang_time/vendor/golang.org/x/time \
		google:btree:v1.0.0:google_btree/vendor/github.com/google/btree \
		google:gofuzz:24818f796faf:google_gofuzz/vendor/github.com/google/gofuzz \
		googleapis:gnostic:v0.2.0:googleapis_gnostic/vendor/github.com/googleapis/gnostic \
		googleapis:google-cloud-go:v0.46.3:googleapis_google_cloud_go/vendor/cloud.google.com/go \
		gophercloud:gophercloud:f8826f28e31a:gophercloud_gophercloud/vendor/github.com/gophercloud/gophercloud \
		gregjones:httpcache:9cad4c3443a7:gregjones_httpcache/vendor/github.com/gregjones/httpcache \
		hashicorp:go-version:v1.2.0:hashicorp_go_version/vendor/github.com/hashicorp/go-version \
		imdario:mergo:v0.3.5:imdario_mergo/vendor/github.com/imdario/mergo \
		inconshreveable:mousetrap:v1.0.0:inconshreveable_mousetrap/vendor/github.com/inconshreveable/mousetrap \
		json-iterator:go:v1.1.6:json_iterator_go/vendor/github.com/json-iterator/go \
		k14s:difflib:b101e55e0592:k14s_difflib/vendor/github.com/k14s/difflib \
		vmware-tanzu:carvel-kapp-controller:v0.1.0:k14s_kapp_controller/vendor/github.com/k14s/kapp-controller \
		kubernetes:api:072894a440bd:kubernetes_api/vendor/k8s.io/api \
		kubernetes:apimachinery:103fd098999d:kubernetes_apimachinery/vendor/k8s.io/apimachinery \
		kubernetes:client-go:v8.0.0:kubernetes_client_go/vendor/k8s.io/client-go \
		mattn:go-colorable:v0.1.4:mattn_go_colorable/vendor/github.com/mattn/go-colorable \
		mattn:go-isatty:v0.0.11:mattn_go_isatty/vendor/github.com/mattn/go-isatty \
		mitchellh:go-wordwrap:v1.0.0:mitchellh_go_wordwrap/vendor/github.com/mitchellh/go-wordwrap \
		modern-go:concurrent:bacd9c7ef1dd:modern_go_concurrent/vendor/github.com/modern-go/concurrent \
		modern-go:reflect2:v1.0.1:modern_go_reflect2/vendor/github.com/modern-go/reflect2 \
		peterbourgon:diskv:v2.0.1:peterbourgon_diskv/vendor/github.com/peterbourgon/diskv \
		pmezard:go-difflib:v1.0.0:pmezard_go_difflib/vendor/github.com/pmezard/go-difflib \
		protocolbuffers:protobuf-go:v1.22.0:protocolbuffers_protobuf_go/vendor/google.golang.org/protobuf \
		spf13:cobra:v1.1.1:spf13_cobra/vendor/github.com/spf13/cobra \
		spf13:pflag:v1.0.5:spf13_pflag/vendor/github.com/spf13/pflag \
		stretchr:testify:v1.7.0:stretchr_testify/vendor/github.com/stretchr/testify \
		vito:go-interact:fa338ed9e9ec:vito_go_interact/vendor/github.com/vito/go-interact

GO_TARGET=	./cmd/kapp

PLIST_FILES=	bin/kapp

.include <bsd.port.mk>
