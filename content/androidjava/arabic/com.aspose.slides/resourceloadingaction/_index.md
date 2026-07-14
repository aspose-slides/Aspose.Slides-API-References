---
title: ResourceLoadingAction
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يحدد وضع تحميل المورد الخارجي.
type: docs
url: /ar/com.aspose.slides/resourceloadingaction/
---
**الوراثة:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

يحدد وضع تحميل المورد الخارجي.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Default](#Default) | Aspose.Slides will load external resource as usual. |
| [Skip](#Skip) | Aspose.Slides will skip loading of external resource. |
| [UserProvided](#UserProvided) | Aspose.Slides will use byte array provided by user in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) as image data. |
### افتراضي {#Default}
```
public static final int Default
```

Aspose.Slides will load external resource as usual.

### تخطي {#Skip}
```
public static final int Skip
```

Aspose.Slides will skip loading of external resource. Only link without data will be stored for an image.

### مقدم من المستخدم {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides will use byte array provided by user in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) as image data.