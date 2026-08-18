---
title: ResourceLoadingAction
second_title: Odwołanie API Aspose.Slides dla Javy
description: Określa tryb ładowania zasobów zewnętrznych.
type: docs
url: /pl/com.aspose.slides/resourceloadingaction/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Określa tryb ładowania zasobów zewnętrznych.
## Pola

| Pole | Opis |
| --- | --- |
| [Default](#Default) | Aspose.Slides will load external resource as usual. |
| [Skip](#Skip) | Aspose.Slides will skip loading of external resource. |
| [UserProvided](#UserProvided) | Aspose.Slides will use byte array provided by user in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) as image data. |
### Domyślny {#Default}
```
public static final int Default
```


Aspose.Slides will load external resource as usual.

### Pomiń {#Skip}
```
public static final int Skip
```


Aspose.Slides will skip loading of external resource. Only link without data will be stored for an image.

### DostarczoneUżytkownikiem {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides will use byte array provided by user in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) as image data.