---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 參考文件
description: 從基礎 URI 和相對 URI 解析絕對 URI。
type: docs
weight: 66
url: /zh-hant/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) 方法

從基礎 URI 和相對 URI 解析絕對 URI。

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用於解析相對 URI 的基礎 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。此 URI 可以是絕對的或相對的。如果是絕對的，該值會直接取代 **baseUri** 的值。如果是相對的，則會與 **baseUri** 結合產生絕對 URI。 |

### 返回值

絕對 URI；如果無法解析相對 URI，則返回 **nullptr**。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [XmlUrlResolver](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)