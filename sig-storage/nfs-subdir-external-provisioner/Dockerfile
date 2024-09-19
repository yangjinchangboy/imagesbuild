git clone git@github.com:yangjinchangboy/imagesbuild.git mkdir -vp imagesbuild/sig-storage/nfs-subdir-external-provisionertee imagesbuild/sig-storage/nfs-subdir-external-provisioner/Dockerfile  <<'EOF'
FROM k8s.gcr.io/sig-storage/nfs-subdir-external-provisioner:v4.0.2
LABEL MAINTAINER=master@weiyigeeek.top BUILDTYPE=Aliyun
EOF git add . && git commit -m "nfs-subdir-external-provisioner" && git push
