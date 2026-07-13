---
title: LinkEmbedDecision
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan bagaimana objek akan diproses selama penyimpanan.
type: docs
url: /id/com.aspose.slides/linkembeddecision/
---
**Warisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Menentukan bagaimana objek akan diproses selama penyimpanan.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Link](#Link) | Objek akan disimpan secara eksternal, dirujuk dengan URL |
| [Embed](#Embed) | Objek harus disematkan ke file yang dihasilkan jika memungkinkan. |
| [Ignore](#Ignore) | Objek akan diabaikan. |
### Tautan {#Link}
```
public static final int Link
```


Objek akan disimpan secara eksternal, dirujuk dengan URL

### Sematkan {#Embed}
```
public static final int Embed
```


Objek harus disematkan ke file yang dihasilkan jika memungkinkan. Jika penyematan tidak memungkinkan, GetUrl akan dipanggil dan, tergantung pada hasilnya, objek akan dirujuk dengan URL atau diabaikan.

### Abaikan {#Ignore}
```
public static final int Ignore
```


Objek akan diabaikan.