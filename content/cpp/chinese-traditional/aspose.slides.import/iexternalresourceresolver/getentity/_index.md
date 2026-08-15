---
title: GetEntity()
second_title: Aspose.Slides for C++ API 參考
description: 將 URI 映射到包含實際資源的物件。
type: docs
weight: 14
url: /zh-hant/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) 方法

將 URI 映射到包含實際資源的物件。

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | 指向該物件的絕對 URI。 |

### 傳回值

如果資源無法串流，則返回 [System::IO::Stream](../../../system.io/stream/) 物件或 null。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [String](../../../system/string/)
* 類別 [IExternalResourceResolver](../)
* 命名空間 [Aspose::Slides::Import](../../)
* 函式庫 [Aspose.Slides](../../../)