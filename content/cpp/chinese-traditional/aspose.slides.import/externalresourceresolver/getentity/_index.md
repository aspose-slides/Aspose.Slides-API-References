---
title: GetEntity()
second_title: Aspose.Slides for C++ API 參考
description: 將 URI 映射至包含實際資源的物件。
type: docs
weight: 14
url: /zh-hant/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) 方法

將 URI 映射到包含實際資源的物件。

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | 指向該物件的絕對 URI。 |

### 回傳值

如果資源無法串流，則返回 [System::IO::Stream](../../../system.io/stream/) 物件或 null。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [String](../../../system/string/)
* 類別 [ExternalResourceResolver](../)
* 命名空間 [Aspose::Slides::Import](../../)
* 函式庫 [Aspose.Slides](../../../)