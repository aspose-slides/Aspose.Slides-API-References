---
title: ParseValue()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, valida a string especificada contra um tipo simples interno ou definido pelo usuário.
type: docs
weight: 53
url: /pt/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) método

When overridden in a derived class, validates the **string** specified against a built-in or user-defined simple type.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | [String](../../../system/string/) | A **string** a ser validada contra o tipo simples. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | O [XmlNameTable](../../../system.xml/xmlnametable/) a ser usado para atomização ao analisar a **string** se este objeto [XmlSchemaDatatype](../) representar o tipo **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | O objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) a ser usado ao analisar a **string** se este objeto [XmlSchemaDatatype](../) representar o tipo **xs:QName**. |

### Return Value

Um [Object](../../../system/object/) que pode ser convertido com segurança para o tipo retornado pela chamada [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XmlNameTable](../../../system.xml/xmlnametable/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)