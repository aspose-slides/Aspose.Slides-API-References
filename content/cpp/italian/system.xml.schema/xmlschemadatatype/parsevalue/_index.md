---
title: ParseValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, convalida la stringa specificata rispetto a un tipo semplice incorporato o definito dall'utente.
type: docs
weight: 53
url: /it/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) metodo

Quando sovrascritto in una classe derivata, convalida la **stringa** specificata rispetto a un tipo semplice incorporato o definito dall'utente.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | [String](../../../system/string/) | La **stringa** da convalidare rispetto al tipo semplice. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | Il [XmlNameTable](../../../system.xml/xmlnametable/) da utilizzare per l'atomizzazione durante l'analisi della **stringa** se questo oggetto [XmlSchemaDatatype](../) rappresenta il tipo **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Il [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) da utilizzare durante l'analisi della **stringa** se questo oggetto [XmlSchemaDatatype](../) rappresenta il tipo **xs:QName**. |

### Valore di ritorno

Un [Object](../../../system/object/) che può essere convertito in modo sicuro al tipo restituito dalla chiamata [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XmlNameTable](../../../system.xml/xmlnametable/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)