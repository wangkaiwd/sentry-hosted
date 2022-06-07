## sentry-hosted

* [Self-Hosted Sentry](https://github.com/getsentry/self-hosted/issues/1153)
* [`./install.sh` error](https://github.com/getsentry/self-hosted/issues/1242)
* [support arm64](https://github.com/getsentry/self-hosted/issues/914)
* [how to configure self-hosted sentry with admin password](https://stackoverflow.com/questions/66531123/how-to-configure-self-hosted-sentry-with-admin-password)
* [reset.sh breaking after passing to install.sh during check-minimum-requirements.sh line 3: file not found](https://github.com/getsentry/self-hosted/issues/1079)
  * above error exist in [this repository](https://github.com/Sentry-ARM/onpremise)

### Step

```shell
git clone git@github.com:getsentry/self-hosted.git
cd self-hosted
brew install coreutils
bash install.sh
```

### Operate

under `self-hosted` execute:

* start server: docker-compose up -d
* stop server: docker-compose down

### Sentry Admin

* http://127.0.0.1:9000/admin
