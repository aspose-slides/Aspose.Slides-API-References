---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 參考
description: 從基礎 URI 與相對 URI 解析絕對 URI。
type: docs
weight: 1
url: /zh-hant/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) 方法

從基礎 URI 和相對 URI 解析絕對 URI。

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | 鏈接對象的基礎 URI |
| relativeUri | [System::String](../../../system/string/) | 指向鏈接對象的相對 URI。 |

### 返回值

如果無法解析相對 URI，則返回絕對 URI 或 null。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IExternalResourceResolver](../)
* 命名空間 [Aspose::Slides::Import](../../)
* 函式庫 [Aspose.Slides](../../../)