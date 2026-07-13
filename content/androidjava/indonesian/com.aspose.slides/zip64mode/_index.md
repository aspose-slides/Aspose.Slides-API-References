---
title: Zip64Mode
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menentukan kapan menggunakan ekstensi format ZIP64 untuk file OpenXML.
type: docs
url: /id/com.aspose.slides/zip64mode/
---
**Pewarisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Menentukan kapan menggunakan ekstensi format ZIP64 untuk file OpenXML.

--------------------

File OpenXML adalah arsip ZIP yang memiliki batas 4 GB (2^32 byte) pada ukuran tidak terkompresi sebuah file, ukuran terkompresi sebuah file, dan ukuran total arsip, serta batas 65.535 (2^16-1) file dalam arsip. Ekstensi format ZIP64 meningkatkan batas tersebut menjadi 2^64.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Never](#Never) | Jangan gunakan ekstensi format ZIP64. |
| [IfNecessary](#IfNecessary) | Gunakan ekstensi format ZIP64 bila perlu. |
| [Always](#Always) | Selalu gunakan ekstensi format ZIP64. |
### Tidak Pernah {#Never}
```
public static final int Never
```


Jangan gunakan ekstensi format ZIP64.

### Jika Diperlukan {#IfNecessary}
```
public static final int IfNecessary
```


Gunakan ekstensi format ZIP64 bila perlu.

### Selalu {#Always}
```
public static final int Always
```


Selalu gunakan ekstensi format ZIP64.