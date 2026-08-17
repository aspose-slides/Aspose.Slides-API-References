---
title: ResourceLoadingAction
second_title: Aspose.Slides for Java API Referansı
description: Harici kaynak yükleme modunu belirtir.
type: docs
url: /tr/com.aspose.slides/resourceloadingaction/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Harici kaynak yükleme modunu belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Default](#Default) | Aspose.Slides dış kaynağı her zamanki gibi yükleyecek. |
| [Skip](#Skip) | Aspose.Slides dış kaynağın yüklenmesini atlayacak. |
| [UserProvided](#UserProvided) | Aspose.Slides, kullanıcı tarafından [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) içinde sağlanan bayt dizisini görüntü verisi olarak kullanacak. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides dış kaynağı her zamanki gibi yükleyecek.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides dış kaynağın yüklenmesini atlayacak. Görüntü için yalnızca veri içermeyen bağlantı saklanacak.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides, kullanıcı tarafından [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) içinde sağlanan bayt dizisini görüntü verisi olarak kullanacak.