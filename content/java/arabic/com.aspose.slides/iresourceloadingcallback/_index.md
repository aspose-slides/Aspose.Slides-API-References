---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: واجهة رد النداء المستخدمة لإدارة تحميل الموارد الخارجية.
type: docs
url: /ar/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

واجهة رد النداء المستخدمة لإدارة تحميل الموارد الخارجية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | طريقة رد النداء التي تتحكم في تحميل الموارد الخارجية. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

طريقة رد النداء التي تتحكم في تحميل الموارد الخارجية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | بيانات تحميل المورد [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**القيمة المرجعة:**
int - قرار تحميل المورد [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).