---
title: ChangeType()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的值，其類型是由 XmlSchemaDatatype 表示的 XML 架構類型的有效表示之一，轉換為指定的執行時類型。
type: docs
weight: 66
url: /zh-hant/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) 方法

將指定的值（其類型是由 [XmlSchemaDatatype](../) 表示的 XML 架構類型的有效表示之一）轉換為指定的執行時類型。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要轉換為指定類型的輸入值。 |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 要將輸入值轉換為的目標類型。 |

### 返回值

已轉換的輸入值。

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法

將指定的值（其類型是由 [XmlSchemaDatatype](../) 表示的 XML 架構類型的有效表示之一）轉換為使用 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 指定的執行時類型（如果 [XmlSchemaDatatype](../) 表示 **xs:QName** 類型或其衍生類型）。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要轉換為指定類型的輸入值。 |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 要將輸入值轉換為的目標類型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用於解析命名空間前置詞的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)。僅在 [XmlSchemaDatatype](../) 表示 **xs:QName** 類型或其衍生類型時才有用。 |

### 返回值

已轉換的輸入值。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [XmlSchemaDatatype](../)
* 類別 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)