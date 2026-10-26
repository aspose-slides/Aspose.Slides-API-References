---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 參考文件
description: 透過在底層 XmlResolver 上呼叫 ResolveUri，解析基礎與相對 URI 所得到的絕對 URI。
type: docs
weight: 40
url: /zh-hant/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) 方法

透過在底層 [XmlResolver](../../xmlresolver/) 上呼叫 **ResolveUri**，解析來自基礎和相對 URI 的絕對 URI。

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用於解析相對 URI 的基礎 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。該 URI 可以是絕對的或相對的。若為絕對，則此值會取代 **baseUri** 的值。若為相對，則與 **baseUri** 結合以產生絕對 URI。 |

### 回傳值

若相對 URI 無法解析，則回傳絕對 URI 或 **nullptr**（透過在底層 [XmlResolver](../../xmlresolver/) 上呼叫 **ResolveUri** 取得）。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [XmlSecureResolver](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)