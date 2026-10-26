---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 用于管理外部资源加载的回调接口。
type: docs
url: /zh/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

用于管理外部资源加载的回调接口。

## 方法

| 方法 | 描述 |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | 调节外部资源加载的回调方法。 |

### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

调节外部资源加载的回调方法。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | 加载资源数据 [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs)。 |

**返回值:**
int - 资源加载决策 [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction)。