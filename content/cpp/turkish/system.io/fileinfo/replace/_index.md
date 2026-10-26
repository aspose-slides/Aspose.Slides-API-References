---
title: Replace()
second_title: C++ API Referansı için Aspose.Slides
description: Belirtilen hedef dosyanın içeriğini mevcut FileInfo nesnesi tarafından temsil edilen dosyayla değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur.
type: docs
weight: 131
url: /tr/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) yöntemi

Belirtilen hedef dosyanın içeriğini mevcut [FileInfo](../) nesnesi tarafından temsil edilen dosya ile değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Değiştirilecek dosyanın adı |
| destinationBackupFileName | const [String](../../../system/string/)\& | Yedek dosyanın adı |

### Dönüş Değeri

**destinationFileName** işaret eden dosyayı temsil eden bir FileInfor nesnesi

## FileInfo::Replace(const String\&, const String\&, bool) yöntemi

Belirtilen hedef dosyanın içeriğini mevcut [FileInfo](../) nesnesi tarafından temsil edilen dosya ile değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Değiştirilecek dosyanın adı |
| destinationBackupFileName | const [String](../../../system/string/)\& | Yedek dosyanın adı |
| ignoreMetadataErrors | **bool** | Değiştirilen dosyadan yeni dosyaya birleştirme hatalarının göz ardı edilip edilmemesi gerektiğini (true) belirtir, aksi takdirde (false) |

### Dönüş Değeri

**destinationFileName** işaret eden dosyayı temsil eden bir FileInfor nesnesi

## Bakınız

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [FileInfo](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)