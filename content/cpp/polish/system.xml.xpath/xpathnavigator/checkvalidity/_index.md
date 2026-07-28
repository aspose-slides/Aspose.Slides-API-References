---
title: CheckValidity()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Weryfikuje, czy dane XML w XPathNavigator są zgodne z dostarczonym schematem języka definicji XML Schema (XSD).
type: docs
weight: 755
url: /pl/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) metoda


Weryfikuje, że dane XML w [XPathNavigator](../) są zgodne z dostarczonym schematem języka definicji XML [Schema](../../../system.xml.schema/) (XSD).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | XmlSchemaSet zawierający schematy używane do walidacji danych XML zawartych w [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ValidationEventHandler, który otrzymuje informacje o ostrzeżeniach i błędach walidacji schematu. |

### Wartość zwracana

**true** jeśli nie wystąpiły błędy walidacji schematu; w przeciwnym razie **false**.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Klasa [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)