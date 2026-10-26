---
title: SecurityPermissionFlag
second_title: Referensi API Aspose.Slides untuk C++
description: Flag izin keamanan.
type: docs
weight: 27
url: /id/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Flag izin keamanan.

```cpp
enum class SecurityPermissionFlag
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NoFlags | 0 | Tidak ada akses. |
| Assertion | 1 | Menyatakan bahwa izin telah diberikan. |
| UnmanagedCode | 2 | Memanggil kode tidak terkelola. |
| SkipVerification | 4 | Lewati verifikasi kode. |
| Execution | 8 | Menjalankan kode. |
| ControlThread | 16 | Melakukan operasi pada thread. |
| ControlEvidence | 32 | Mengontrol atau mengubah bukti CLR. |
| ControlPolicy | 64 | Melihat dan mengubah kebijakan. |
| SerializationFormatter | 128 | Serialisasi. |
| ControlDomainPolicy | 256 | Menetapkan kebijakan domain. |
| ControlPrincipal | 512 | Mengontrol objek principal. |
| ControlAppDomain | 1024 | Mengontrol domain aplikasi. |
| RemotingConfiguration | 2048 | Mengonfigurasi remoting. |
| Infrastructure | 4096 | Menyambungkan ke infrastruktur CLR. |
| BindingRedirects | 8192 | Melakukan pengalihan binding eksplisit. |
| AllFlags | 16383 | Tidak terbatas. |

## Lihat Juga

* Namespace [System::Security::Permissions](../)
* Pustaka [Aspose.Slides](../../)