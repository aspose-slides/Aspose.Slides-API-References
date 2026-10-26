---
title: Zip64Mode
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan kapan harus menggunakan ekstensi format ZIP64 untuk file OpenXML.
type: docs
url: /id/com.aspose.slides/zip64mode/
---
**Pewarisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Menentukan kapan harus menggunakan ekstensi format ZIP64 untuk file OpenXML.

--------------------

File OpenXML adalah arsip ZIP yang memiliki batas 4 GB (2^32 byte) pada ukuran file yang tidak terkompresi, ukuran file terkompresi, dan total ukuran arsip, serta batas 65.535 (2^16-1) file dalam arsip. Ekstensi format ZIP64 meningkatkan batas menjadi 2^64.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Never](#Never) | Jangan gunakan ekstensi format ZIP64. |
| [IfNecessary](#IfNecessary) | Gunakan ekstensi format ZIP64 jika diperlukan. |
| [Always](#Always) | Selalu gunakan ekstensi format ZIP64. |
### Never {#Never}
```
public static final int Never
```

Jangan gunakan ekstensi format ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Gunakan ekstensi format ZIP64 jika diperlukan.

### Always {#Always}
```
public static final int Always
```

Selalu gunakan ekstensi format ZIP64.