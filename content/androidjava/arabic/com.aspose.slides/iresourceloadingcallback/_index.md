---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /ar/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

واجهة رد الاتصال المستخدمة لإدارة تحميل الموارد الخارجية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | طريقة رد الاتصال التي تنظم تحميل الموارد الخارجية. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

طريقة رد الاتصال التي تنظم تحميل الموارد الخارجية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | بيانات الموارد التي يتم تحميلها [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**القيمة المرجعة:**
int - قرار تحميل المورد [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).