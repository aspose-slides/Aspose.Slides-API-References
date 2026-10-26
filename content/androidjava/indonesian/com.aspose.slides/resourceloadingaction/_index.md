---
title: ResourceLoadingAction
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan mode pemuatan sumber daya eksternal.
type: docs
url: /id/com.aspose.slides/resourceloadingaction/
---
**Pewarisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Menentukan mode pemuatan sumber daya eksternal.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Default](#Default) | Aspose.Slides akan memuat sumber daya eksternal seperti biasa. |
| [Skip](#Skip) | Aspose.Slides akan melewatkan pemuatan sumber daya eksternal. |
| [UserProvided](#UserProvided) | Aspose.Slides akan menggunakan array byte yang disediakan oleh pengguna dalam [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) sebagai data gambar. |
### Default {#Default}
```
public static final int Default
```


Aspose.Slides akan memuat sumber daya eksternal seperti biasa.

### Skip {#Skip}
```
public static final int Skip
```


Aspose.Slides akan melewatkan pemuatan sumber daya eksternal. Hanya tautan tanpa data yang akan disimpan untuk gambar.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides akan menggunakan array byte yang disediakan oleh pengguna dalam [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) sebagai data gambar.