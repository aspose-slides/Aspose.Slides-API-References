---
title: RegisterPrefix()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendaftarkan keturunan WebRequest untuk URI yang ditentukan.
type: docs
weight: 92
url: /id/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) metode

Mendaftarkan keturunan [WebRequest](../) untuk URI yang ditentukan.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI atau awalan URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Membuat instance baru dari kelas [WebRequest](../). |

### Nilai Kembali

True ketika keturunan [WebRequest](../) berhasil didaftarkan untuk URI yang ditentukan, selainnya false.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [IWebRequestCreate](../../iwebrequestcreate/)
* Kelas [WebRequest](../)
* Ruang Nama [System::Net](../../)
* Pustaka [Aspose.Slides](../../../)