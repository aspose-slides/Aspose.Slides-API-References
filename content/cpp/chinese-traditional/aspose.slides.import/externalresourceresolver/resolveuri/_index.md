---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 參考
description: 從基礎 URI 和相對 URI 解析出絕對 URI。
type: docs
weight: 1
url: /zh-hant/aspose.slides.import/externalresourceresolver/resolveuri/
---
## ExternalResourceResolver::ResolveUri(System::String, System::String) 方法

從基礎 URI 和相對 URI 解析出絕對 URI。

```cpp
System::String Aspose::Slides::Import::ExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | 連結物件的基礎 URI |
| relativeUri | [System::String](../../../system/string/) | 指向已連結物件的相對 URI |

### 返回值

若無法解析相對 URI，則返回絕對 URI 或 null。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [ExternalResourceResolver](../)
* 命名空間 [Aspose::Slides::Import](../../)
* 程式庫 [Aspose.Slides](../../../)