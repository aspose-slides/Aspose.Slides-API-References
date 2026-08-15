---
title: GetEntity()
second_title: Aspose.Slides for C++ API 參考
description: 將 URI 映射到包含實際資源的物件。
type: docs
weight: 53
url: /zh-hant/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 方法

將 URI 映射到包含實際資源的物件。

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 從 [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) 呼叫返回的 URI。 |
| role | [String](../../../system/string/) | 目前未使用。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的物件類型。 [XmlPreloadedResolver](../) 支援對以 [String](../../../system/string/) 方式新增的 URI 的 Stream 物件和 TextReader 物件。如果解析器不支援請求的類型，將拋出例外。使用 XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) 方法來判斷解析器是否支援特定 **Type**。 |

### 返回值

對應實際來源的 Stream 或 TextReader 物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)