# Project Quay

![CI](https://github.com/unioslo/quay/workflows/CI/badge.svg?branch=uio-3.6)

:warning: This a fork of [quay/quay](https://github.com/quay/quay) with a fix for
[PROJQUAY-3235](https://issues.redhat.com/browse/PROJQUAY-3235).  It tracks the
`redhat-3.6` release branch and publishes a container image to
[ghcr.io/unioslo/quay](https://ghcr.io/unioslo/quay).
[List of changes](https://github.com/quay/quay/compare/quay:redhat-3.6...unioslo:uio-3.6).

[releases]: https://github.com/quay/quay/releases

![Project Quay Logo](project_quay_logo.png)

Project Quay builds, stores, and distributes your container images.

High-level features include:

- Docker Registry Protocol [v2]
- Docker Manifest Schema [v2.1], [v2.2]
- [AppC Image Discovery] via on-demand transcoding
- Image Squashing via on-demand transcoding
- Authentication provided by [LDAP], [Keystone], [OIDC], [Google], and [GitHub]
- ACLs, team management, and auditability logs
- Geo-replicated storage provided by local filesystems, [S3], [GCS], [Swift], and [Ceph]
- Continuous Integration integrated with [GitHub], [Bitbucket], [GitLab], and [git]
- Security Vulnerability Analysis via [Clair]
- [Swagger]-compliant HTTP API

[v2]: https://docs.docker.com/registry/spec/api/
[v2.1]: https://github.com/docker/distribution/blob/master/docs/spec/manifest-v2-1.md
[v2.2]: https://github.com/docker/distribution/blob/master/docs/spec/manifest-v2-2.md
[AppC Image Discovery]: https://github.com/appc/spec/blob/master/spec/discovery.md
[LDAP]: https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol
[Keystone]: http://docs.openstack.org/developer/keystone
[OIDC]: https://en.wikipedia.org/wiki/OpenID_Connect
[Google]: https://developers.google.com/identity/sign-in/web/sign-in
[GitHub]: https://developer.github.com/v3/oauth
[S3]: https://aws.amazon.com/s3
[GCS]: https://cloud.google.com/storage
[Swift]: http://swift.openstack.org
[Ceph]: http://docs.ceph.com/docs/master/radosgw/config
[GitHub]: https://github.com
[Bitbucket]: https://bitbucket.com
[GitLab]: https://gitlab.com
[git]: https://git-scm.com
[Clair]: https://github.com/quay/clair
[Swagger]: http://swagger.io

## Getting Started

* Explore a live instance of Project Quay hosted at [Quay.io]
* Watch [talks] given about Project Quay
* Review the [documentation] for Red Hat Quay
* Get up and running with a containerized [development environment]
* Deploy on Kubernetes using the [Quay Operator]

[Quay.io]: https://quay.io
[talks]: /docs/talks.md
[documentation]: https://access.redhat.com/documentation/en-us/red_hat_quay
[development environment]: /docs/development-container.md
[Quay Operator]: https://github.com/quay/quay-operator

## Community

* Mailing List: [quay-sig@googlegroups.com]
* IRC: #quay on [freenode.net]
* Bug tracking: [JBoss JIRA]
* Security Issues: [security@redhat.com]

[quay-sig@googlegroups.com]: https://groups.google.com/forum/#!forum/quay-sig
[freenode.net]: https://webchat.freenode.net
[JBoss JIRA]: https://issues.jboss.org/projects/PROJQUAY
[security@redhat.com]: mailto:security@redhat.com

## License

Project Quay is under the Apache 2.0 license.
See the LICENSE file for details.
