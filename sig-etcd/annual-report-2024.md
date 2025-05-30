# 2024 Annual Report: SIG etcd

## Current initiatives and Project Health

1. What work did the SIG do this year that should be highlighted?

- No governance or leadership changes.
- Major SIG level KEPs.
  - [etcd downgrade](https://github.com/kubernetes/enhancements/tree/master/keps/sig-etcd/4326-downgrade) is implemented to support etcd v3.6 and above
  - Introduced [Server Feature Gate in etcd](https://github.com/kubernetes/enhancements/pull/4610)
- [Working Group etcd-operator](https://github.com/kubernetes/community/blob/master/wg-etcd-operator/README.md) was co-founded by SIG etcd and SIG cluster lifecycle
- Formed the dedicated [release team](https://github.com/etcd-io/etcd/blob/main/Documentation/contributor-guide/release.md) to streamline and enhance the release process.
- Delivered 13 patch [releases (6 for release 3.5 and 7 for release 3.4)](https://github.com/etcd-io/etcd/releases).
- Introduced [bbolt surgery commands](https://github.com/etcd-io/bbolt/tree/526ef1e15f7e3e3c8e29f3b78ed173fa29b1bc60/cmd/bbolt#help) to repair corrupted database files where possible.
- Made a lot of progress on Prow job migration, including migrating all the ARM64 jobs.

2. Are there any areas and/or subprojects that your group needs help with (e.g. fewer than 2 active OWNERS)?

- [dbtester](https://github.com/etcd-io/dbtester)
- [discovery.etcd.io](https://github.com/etcd-io/discovery.etcd.io))
- [discoveryserver](https://github.com/etcd-io/discoveryserver)
- [etcdlabs](https://github.com/etcd-io/etcdlabs)
- [gofail](https://github.com/etcd-io/gofail)
- [govanityurls](https://github.com/etcd-io/govanityurls)
- [jetcd](https://github.com/etcd-io/jetcd)
- [protodoc](https://github.com/etcd-io/protodoc)

3. Did you have community-wide updates in 2024 (e.g. KubeCon talks)?

- [Scaling and Safeguarding the Heart of Kubernetes: Deep Dive Into etcd - Panel (KubeCon NA '24)](https://youtu.be/q_HZo5Mu8Fk?si=YfjihY51X3DuY2VN)
- [etcd 3.6 and Beyond (KubeCon EU '24)](https://youtu.be/b93U1ekv0Fc?si=jqIspCFe2RLIEbel)
- [etcd mentorship program cohort 1](https://tinyurl.com/etcd-mentorship)

4. KEP work in 2024:
<!--
   TODO: Uncomment the following auto-generated list of KEPs, once reviewed & updated for correction.

   Note: This list is generated from the KEP metadata in kubernetes/enhancements repository.
      If you find any discrepancy in the generated list here, please check the KEP metadata.
      Please raise an issue in kubernetes/community, if the KEP metadata is correct but the generated list is incorrect.
-->
- [Server Feature Gate in etcd](https://github.com/kubernetes/enhancements/pull/4610)

## [Subprojects](https://git.k8s.io/community/sig-etcd#subprojects)


**New in 2024:**
  - auger
  - etcd-manager

**Continuing:**
  - bbolt
  - dbtester
  - discovery.etcd.io
  - discoveryserver
  - etcd
  - etcdlabs
  - gofail
  - govanityurls
  - jetcd
  - protodoc
  - raft
  - website

## [Working groups](https://git.k8s.io/community/sig-etcd#working-groups)

**New in 2024:**
 - etcd Operator

## Operational

Operational tasks in [sig-governance.md]:
- [ ] [README.md] reviewed for accuracy and updated if needed
- [ ] [CONTRIBUTING.md] reviewed for accuracy and updated if needed
- [ ] Other contributing docs (e.g. in devel dir or contributor guide) reviewed for accuracy and updated if needed
- [ ] Subprojects list and linked OWNERS files in [sigs.yaml] reviewed for accuracy and updated if needed
- [ ] SIG leaders (chairs, tech leads, and subproject leads) in [sigs.yaml] are accurate and active, and updated if needed
- [ ] Meeting notes and recordings for 2024 are linked from [README.md] and updated/uploaded if needed


[CONTRIBUTING.md]: https://github.com/etcd-io/etcd/blob/main/CONTRIBUTING.md
[sig-governance.md]: https://git.k8s.io/community/committee-steering/governance/sig-governance.md
[README.md]: https://git.k8s.io/community/sig-etcd/README.md
[sigs.yaml]: https://git.k8s.io/community/sigs.yaml
[devel]: https://git.k8s.io/community/contributors/devel/README.md
