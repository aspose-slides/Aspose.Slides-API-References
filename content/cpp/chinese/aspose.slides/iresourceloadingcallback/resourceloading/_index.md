---
title: ResourceLoading()
second_title: Aspose.Slides C++ API 参考
description: 用于调节外部资源加载的回调方法。
type: docs
weight: 1
url: /zh/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) 方法

回调方法，用于调节外部资源的加载。

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | 加载资源数据 [IResourceLoadingArgs](../../iresourceloadingargs/)。 |

### 返回值

资源加载决定 [ResourceLoadingAction](../../resourceloadingaction/)。

## 参见

* 枚举 [ResourceLoadingAction](../../resourceloadingaction/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IResourceLoadingArgs](../../iresourceloadingargs/)
* 类 [IResourceLoadingCallback](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)