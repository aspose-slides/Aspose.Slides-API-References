---
title: get_SchemaType()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個模式類型物件。
type: docs
weight: 287
url: /zh-hant/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() 方法


傳回一個模式類型物件。

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### 回傳值

XmlSchemaDatatype、XmlSchemaSimpleType 或 XmlSchemaComplexType，取決於節點值是內建的 XML [Schema](../../../system.xml.schema/) 定義語言 (XSD) 類型，還是使用者自訂的 simpleType 或 complexType；**nullptr** 表示目前節點沒有模式類型。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)