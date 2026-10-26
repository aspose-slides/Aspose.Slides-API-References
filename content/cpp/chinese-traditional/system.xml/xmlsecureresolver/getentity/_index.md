---
title: GetEntity()
second_title: Aspose.Slides C++ API 參考文件
description: 將 URI 對映至包含實際資源的物件。
type: docs
weight: 27
url: /zh-hant/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 方法

將 URI 對映至包含實際資源的物件。

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 從 [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) 呼叫所回傳的 URI。 |
| role | [String](../../../system/string/) | 目前未使用。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 要回傳的物件類型。目前的版本僅回傳 Stream 物件。 |

### 回傳值

透過在底層 [XmlResolver](../../xmlresolver/) 上呼叫 **GetEntity** 所回傳的串流。若指定的類型不是 Stream，則此方法回傳 **nullptr**。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [XmlSecureResolver](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)