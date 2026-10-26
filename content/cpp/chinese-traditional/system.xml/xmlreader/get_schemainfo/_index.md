---
title: get_SchemaInfo()
second_title: Aspose.Slides for C++ API 參考
description: 返回已因結構驗證而指派給目前節點的結構資訊。
type: docs
weight: 196
url: /zh-hant/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() 方法


傳回已因結構驗證而指派給目前節點的結構資訊。

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### 傳回值

一個 IXmlSchemaInfo 物件，包含目前節點的結構資訊。 [Schema](../../../system.xml.schema/) 資訊可以設定在元素、屬性，或具有非空 [XmlReader::get_ValueType](../get_valuetype/) 值的文字節點上。 如果目前節點不是上述節點類型之一，或 [XmlReader](../) 實例未回報結構資訊，則此方法傳回 **nullptr**。 如果此方法從 [XmlTextReader](../../xmltextreader/) 或 [XmlValidatingReader](../../xmlvalidatingreader/) 物件呼叫，則此方法總是傳回 **nullptr**。 這些 [XmlReader](../) 實作不會透過 get_SchemaInfo 方法公開結構資訊。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)