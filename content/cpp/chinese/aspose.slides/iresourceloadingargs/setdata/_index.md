---
title: SetData()
second_title: Aspose.Slides C++ API 参考
description: "在 IResourceLoadingCallback::ResourceLoading() 返回 ResourceLoadingAction::UserProvided 时，设置资源的用户提供数据。"
type: docs
weight: 40
url: /zh/aspose.slides/iresourceloadingargs/setdata/
---
## IResourceLoadingArgs::SetData(System::ArrayPtr\<uint8_t\>) 方法


设置用户提供的资源数据，在 [IResourceLoadingCallback::ResourceLoading()](../../iresourceloadingcallback/resourceloading/) 返回 [ResourceLoadingAction::UserProvided](../../resourceloadingaction/) 时使用。

```cpp
virtual void Aspose::Slides::IResourceLoadingArgs::SetData(System::ArrayPtr<uint8_t> data)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 资源提供的 **uint8_t**[] 数据 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IResourceLoadingArgs](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)