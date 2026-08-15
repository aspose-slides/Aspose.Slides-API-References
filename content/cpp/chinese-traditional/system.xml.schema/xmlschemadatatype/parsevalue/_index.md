---
title: ParseValue()
second_title: Aspose.Slides C++ API 參考文件
description: 當在衍生類別中被覆寫時，驗證指定的字串是否符合內建或使用者自訂的簡單型別。
type: docs
weight: 53
url: /zh-hant/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) method

當在衍生類別中被覆寫時，驗證指定的 **string** 是否符合內建或使用者自訂的簡單型別。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | [String](../../../system/string/) | 用於驗證簡單型別的 **string**。 |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | 在解析 **string** 時使用的 [XmlNameTable](../../../system.xml/xmlnametable/)，如果此 [XmlSchemaDatatype](../) 物件表示 **xs:NCName** 型別。 |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 在解析 **string** 時使用的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件，如果此 [XmlSchemaDatatype](../) 物件表示 **xs:QName** 型別。 |

### 返回值

一個 [Object](../../../system/object/)，可安全轉型為 [XmlSchemaDatatype::get_ValueType](../get_valuetype/) 呼叫所返回的型別。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [String](../../../system/string/)
* 類別 [XmlNameTable](../../../system.xml/xmlnametable/)
* 類別 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 類別 [XmlSchemaDatatype](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)