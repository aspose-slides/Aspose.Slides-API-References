---
title: GetEntity()
second_title: Aspose.Slides for C++ API 參考
description: 將 URI 對映到包含實際資源的物件。
type: docs
weight: 53
url: /zh-hant/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 方法

將 URI 對映到包含實際資源的物件。

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 從 [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) 呼叫返回的 URI。 |
| role | [String](../../../system/string/) | 目前未使用。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的物件類型。目前的實作僅返回 Stream 物件。 |

### 傳回值

若指定的類型不是 stream，則返回 stream 物件或 **nullptr**。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [XmlUrlResolver](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)