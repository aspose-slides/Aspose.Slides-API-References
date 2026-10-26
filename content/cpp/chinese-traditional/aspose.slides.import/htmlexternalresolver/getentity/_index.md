---
title: GetEntity()
second_title: Aspose.Slides for C++ API 參考
description: 將 URI 映射到包含實際資源的物件。
type: docs
weight: 14
url: /zh-hant/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) 方法

將 URI 對應到包含實際資源的物件。

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolute URI to the object. |

### 返回值

[System::IO::Stream](../../../system.io/stream/) 物件或 null，如果資源無法串流。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [String](../../../system/string/)
* 類別 [HtmlExternalResolver](../)
* 命名空間 [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)