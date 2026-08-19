---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /fa/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

رابط callback که برای مدیریت بارگذاری منابع خارجی استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | متد callback که بارگذاری منابع خارجی را تنظیم می‌کند. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

متد callback که بارگذاری منابع خارجی را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | داده‌های بارگذاری منبع [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**بازگشت:**
int - تصمیم بارگذاری منبع [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).