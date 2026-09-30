# ShellKit builds 3–4: third-party source material

This directory contains the upstream source archives, Alpine packaging files, patches, and SHA-512 checksum records corresponding to the GPL-licensed guest packages identified in the ShellKit builds 3 and 4 app archives. These programs run in the bundled Alpine environment. The native ShellKit engine is Apache-2.0.

| Origin | Build version | Material |
|---|---|---|
| BusyBox | 1.37.0-r31 | [busybox](busybox/) |
| apk-tools / libapk | 3.0.6-r0 | [apk-tools](apk-tools/) |
| Alpine baselayout | 3.7.2-r1 | [alpine-baselayout](alpine-baselayout/) |
| pax-utils / scanelf | 1.3.9-r1 | [pax-utils](pax-utils/) |
| musl-utils | 1.2.6-r2 | [musl](musl/) |

Every `APKBUILD` contains the Alpine source list and SHA-512 hashes. The source archives and local patches in each folder were checked against those hashes. `APORTS_REVISIONS.txt` identifies the exact Alpine packaging revisions used for retrieval. The Alpine `apk` installed database in the archived app records the package versions listed here.

Apache-2.0 and MIT notices for the app engine and SwiftTerm are also included here. Source questions: sirouni@gmail.com.

This source material covers the identified base Alpine packages in builds 3 and 4. A future app build with additional preinstalled packages needs a new matching inventory.
