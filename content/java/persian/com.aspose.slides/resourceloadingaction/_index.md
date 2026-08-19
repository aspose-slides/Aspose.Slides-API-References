---
title: ResourceLoadingAction
second_title: مرجع API Aspose.Slides برای جاوا
description: حالت بارگذاری منبع خارجی را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/resourceloadingaction/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

حالت بارگذاری منبع خارجی را مشخص می‌کند.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [Default](#Default) | Aspose.Slides منبع خارجی را به‌صورت معمول بارگذاری می‌کند. |
| [Skip](#Skip) | Aspose.Slides بارگذاری منبع خارجی را صرف‌نظر می‌کند. |
| [UserProvided](#UserProvided) | Aspose.Slides از آرایه بایت ارائه‌شده توسط کاربر در [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) به‌عنوان داده تصویر استفاده می‌کند. |
### پیش‌فرض {#Default}
```
public static final int Default
```

Aspose.Slides منبع خارجی را به‌صورت معمول بارگذاری می‌کند.

### صرف‌نظر {#Skip}
```
public static final int Skip
```

Aspose.Slides بارگذاری منبع خارجی را صرف‌نظر می‌کند. Only link without data will be stored for an image.

### کاربر-ارائه‌شده {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides از آرایه بایت ارائه‌شده توسط کاربر در [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) به‌عنوان داده تصویر استفاده می‌کند.