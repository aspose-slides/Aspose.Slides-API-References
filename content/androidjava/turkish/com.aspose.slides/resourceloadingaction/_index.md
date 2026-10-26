---
title: ResourceLoadingAction
second_title: Aspose.Slides for Android via Java API Referansı
description: Dış kaynak yükleme modunu belirtir.
type: docs
url: /tr/com.aspose.slides/resourceloadingaction/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Dış kaynak yükleme modunu belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Default](#Default) | Aspose.Slides dış kaynağı normal olarak yükleyecektir. |
| [Skip](#Skip) | Aspose.Slides dış kaynağın yüklenmesini atlayacaktır. |
| [UserProvided](#UserProvided) | Aspose.Slides, kullanıcı tarafından [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) içinde sağlanan bayt dizisini görüntü verisi olarak kullanacaktır. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides dış kaynağı normal olarak yükleyecektir.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides dış kaynağın yüklenmesini atlayacaktır. Veri içermeyen yalnızca bağlantı bir görüntü için saklanacaktır.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides, kullanıcı tarafından [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) içinde sağlanan bayt dizisini görüntü verisi olarak kullanacaktır.