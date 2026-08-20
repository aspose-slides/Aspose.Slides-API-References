---
title: ResourceLoadingAction
second_title: Aspose.Slides ل Java مرجع API
description: يحدد وضع تحميل الموارد الخارجية.
type: docs
url: /ar/com.aspose.slides/resourceloadingaction/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

يحدد وضع تحميل الموارد الخارجية.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Default](#Default) | ستقوم Aspose.Slides بتحميل المورد الخارجي كالمعتاد. |
| [Skip](#Skip) | ستتخطى Aspose.Slides تحميل المورد الخارجي. |
| [UserProvided](#UserProvided) | ستستخدم Aspose.Slides مصفوفة البايت المقدمة من المستخدم في [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) كبيانات الصورة. |
### Default {#Default}
```
public static final int Default
```


ستقوم Aspose.Slides بتحميل المورد الخارجي كالمعتاد.

### Skip {#Skip}
```
public static final int Skip
```


ستتخطى Aspose.Slides تحميل المورد الخارجي. سيتم فقط تخزين الرابط بدون بيانات لصورة.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


ستستخدم Aspose.Slides مصفوفة البايت المقدمة من المستخدم في [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) كبيانات الصورة.