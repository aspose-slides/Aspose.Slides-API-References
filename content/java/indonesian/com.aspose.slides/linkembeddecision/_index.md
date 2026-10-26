---
title: LinkEmbedDecision
second_title: Aspose.Slides untuk Referensi API Java
description: Menentukan bagaimana objek akan diproses selama penyimpanan.
type: docs
url: /id/com.aspose.slides/linkembeddecision/
---
**Pewarisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Menentukan bagaimana objek akan diproses selama penyimpanan.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Link](#Link) | Objek akan disimpan secara eksternal, dirujuk oleh URL |
| [Embed](#Embed) | Objek harus disematkan ke file yang dihasilkan jika memungkinkan. |
| [Ignore](#Ignore) | Objek akan diabaikan. |
### Link {#Link}
```
public static final int Link
```


Objek akan disimpan secara eksternal, dirujuk oleh URL

### Embed {#Embed}
```
public static final int Embed
```


Objek harus disematkan ke file yang dihasilkan jika memungkinkan. Jika penyematan tidak memungkinkan, GetUrl akan dipanggil dan, tergantung pada hasilnya, objek akan dirujuk oleh URL atau diabaikan.

### Ignore {#Ignore}
```
public static final int Ignore
```


Objek akan diabaikan.