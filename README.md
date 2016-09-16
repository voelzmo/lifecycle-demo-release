## Demonstrating the BOSH lifecycle for releases
See [bosh.io documentation](http://bosh.io/docs/job-lifecycle.html) for additional details.

Containing examples for the following scripts:
* drain
* pre-start
* post-start
* post-deploy

## How to use
* Build your own release with `bosh create release`
* Upload the release to your BOSH Director with `bosh upload release`
* Start with the [manifest example](#manifest/lifecycle-demo.yml) or build your own
* `bosh deploy`
