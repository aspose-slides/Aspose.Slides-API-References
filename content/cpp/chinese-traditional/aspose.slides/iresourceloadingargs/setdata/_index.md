---
title: SetData()
second_title: Aspose.Slides C++ API 參考文件
description: "設定使用者提供的資源資料，當 IResourceLoadingCallback::ResourceLoading() 回傳 ResourceLoadingAction::UserProvided 時使用。"
type: docs
weight: 40
url: /zh-hant/aspose.slides/iresourceloadingargs/setdata/
---
## IResourceLoadingArgs::SetData(System::ArrayPtr\<uint8_t\>) 方法

設定使用者提供的資源資料，該資料會在 [IResourceLoadingCallback::ResourceLoading()](../../iresourceloadingcallback/resourceloading/) 回傳 [ResourceLoadingAction::UserProvided](../../resourceloadingaction/) 時使用。

```cpp
virtual void Aspose::Slides::IResourceLoadingArgs::SetData(System::ArrayPtr<uint8_t> data)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 提供的資源資料 **uint8_t**[] |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IResourceLoadingArgs](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)