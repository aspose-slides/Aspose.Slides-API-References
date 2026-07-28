---
title: CheckValidity()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy az XPathNavigator-ben lévő XML adatok megfelelnek a megadott XML Schema definíciós nyelv (XSD) sémának.
type: docs
weight: 755
url: /hu/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) metódus

Ellenőrzi, hogy a(z) [XPathNavigator](../)-ben lévő XML adatok megfelelnek a megadott XML [Schema](../../../system.xml.schema/) definíciós nyelv (XSD) sémának.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | Az XmlSchemaSet, amely a [XPathNavigator](../)-ban lévő XML adatok érvényesítéséhez használt sémákat tartalmazza. |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | A ValidationEventHandler, amely a séma érvényesítési figyelmeztetésekkel és hibákkal kapcsolatos információkat kapja. |

### Visszatérési érték

**true**, ha nem fordult elő séma érvényesítési hiba; egyébként **false**.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Osztály [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Osztály [XPathNavigator](../)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)