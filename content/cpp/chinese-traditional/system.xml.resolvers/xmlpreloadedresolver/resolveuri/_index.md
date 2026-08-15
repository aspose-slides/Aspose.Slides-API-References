---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 參考手冊
description: 從基礎 URI 和相對 URI 解析出絕對 URI。
type: docs
weight: 40
url: /zh-hant/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) method

從基礎 URI 和相對 URI 解析出絕對 URI。

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用於解析相對 URI 的基礎 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。該 URI 可以是絕對的或相對的。若為絕對，則此值會實際取代 **baseUri**。若為相對，則會與 **baseUri** 結合形成絕對 URI。 |

### Return Value

[Uri](../../../system/uri/) 代表絕對 URI，若無法解析相對 URI，則返回 **nullptr**。

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [XmlPreloadedResolver](../)
* 命名空間 [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)