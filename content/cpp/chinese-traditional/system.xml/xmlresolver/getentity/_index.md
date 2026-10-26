---
title: GetEntity()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中覆寫時，將 URI 映射到包含實際資源的物件。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method


當在衍生類別中覆寫時，將 URI 對映到包含實際資源的物件。

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI returned from [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) call. |
| role | [String](../../../system/string/) | Currently not used. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | The type of object to return. The current version only returns Stream objects. |

### Return Value

若指定非 stream 類型，則返回 stream 物件或 **nullptr**。

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [XmlResolver](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)