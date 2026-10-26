---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中被覆寫時，會從基礎 URI 與相對 URI 解析出絕對 URI。
type: docs
weight: 27
url: /zh-hant/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) 方法


當在衍生類別中被覆寫時，會從基礎 URI 與相對 URI 解析出絕對 URI。

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用於解析相對 URI 的基礎 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。該 URI 可以是絕對的或相對的。若為絕對，則此值實際上會取代 **baseUri** 的值。若為相對，則會與 **baseUri** 結合以形成絕對 URI。 |

### 傳回值

絕對 URI 或 **nullptr**（若無法解析相對 URI）。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [XmlResolver](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)