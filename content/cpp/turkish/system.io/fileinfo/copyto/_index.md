---
title: CopyTo()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dosyayı belirtilen konuma kopyalar. Hedef dosya zaten mevcutsa, kopyalama başarısız olur.
type: docs
weight: 105
url: /tr/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) yöntemi


Geçerli nesne tarafından temsil edilen dosyayı belirtilen konuma kopyalar. Hedef dosya zaten mevcutsa, kopyalama başarısız olur.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Hedef dosya adı |

### Dönüş Değeri

Kopyayı temsil eden bir [FileInfo](../) nesnesi

## FileInfo::CopyTo(const String\&, bool) yöntemi


Geçerli nesne tarafından temsil edilen dosyayı belirtilen konuma kopyalar. Bir parametre, mevcut hedef dosyanın üzerine yazılıp yazılmayacağını belirtir.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Hedef dosya adı |
| overwrite | **bool** | Mevcut hedef dosyanın üzerine yazılması gerekiyorsa doğru, hedef dosya zaten mevcutsa kopyalamanın başarısız olması isteniyorsa yanlış |

### Dönüş Değeri

Kopyayı temsil eden bir [FileInfo](../) nesnesi

## Ayrıca Bakınız

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [FileInfo](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)