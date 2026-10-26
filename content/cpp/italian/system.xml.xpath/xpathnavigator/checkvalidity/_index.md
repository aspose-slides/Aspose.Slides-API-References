---
title: CheckValidity()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica che i dati XML nel XPathNavigator siano conformi al linguaggio di definizione XML Schema (XSD) fornito.
type: docs
weight: 755
url: /it/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) metodo

Verifica che i dati XML in [XPathNavigator](../) siano conformi al linguaggio di definizione XML [Schema](../../../system.xml.schema/) (XSD) fornito.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | Il XmlSchemaSet contenente gli schemi usati per convalidare i dati XML contenuti nel [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Il ValidationEventHandler che riceve informazioni sugli avvisi e sugli errori di convalida dello schema. |

### Valore di ritorno

**true** se non si sono verificati errori di convalida dello schema; altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Classe [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)