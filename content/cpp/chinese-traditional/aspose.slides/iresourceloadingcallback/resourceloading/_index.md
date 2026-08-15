---
title: ResourceLoading()
second_title: Aspose.Slides for C++ API 參考
description: 用於調節外部資源載入的回呼方法。
type: docs
weight: 1
url: /zh-hant/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) method


用於調節外部資源載入的回呼方法。

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | 載入資源資料 [IResourceLoadingArgs](../../iresourceloadingargs/)。 |

### 傳回值

資源載入決策 [ResourceLoadingAction](../../resourceloadingaction/)。

## 另見

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IResourceLoadingArgs](../../iresourceloadingargs/)
* Class [IResourceLoadingCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)