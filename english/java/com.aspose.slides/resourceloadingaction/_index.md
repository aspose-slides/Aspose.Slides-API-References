---
title: ResourceLoadingAction
second_title: Aspose.Slides for Java API Reference
description: Specifies the mode of external resource loading.
type: docs
weight: 464
url: /java/com.aspose.slides/resourceloadingaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Specifies the mode of external resource loading.
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | Aspose.Slides will load external resource as usual. |
| [Skip](#Skip) | Aspose.Slides will skip loading of external resource. |
| [UserProvided](#UserProvided) | Aspose.Slides will use byte array provided by user in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) as image data. |
### Default {#Default}
```
public static final int Default
```


Aspose.Slides will load external resource as usual.

### Skip {#Skip}
```
public static final int Skip
```


Aspose.Slides will skip loading of external resource. Only link without data will be stored for an image.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides will use byte array provided by user in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) as image data.

