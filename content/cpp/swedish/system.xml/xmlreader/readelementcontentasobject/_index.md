---
title: ReadElementContentAsObject()
second_title: Aspose.Slides för C++ API-referens
description: Läser det aktuella elementet och returnerar innehållet som ett Object.
type: docs
weight: 469
url: /sv/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() metod

Läser det aktuella elementet och returnerar innehållet som en [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Returvärde

Ett paketobjekt av den mest lämpliga typen. [XmlReader::get_ValueType](../get_valuetype/)-värdet bestämmer den lämpliga typen. Om innehållet är av en listtyp returnerar denna metod en array av paketerade objekt av den lämpliga typen.

## XmlReader::ReadElementContentAsObject(String, String) metod

Kontrollerar att det angivna lokala namnet och namnrymd-URI:n matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som en [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på elementet. |
| namespaceURI | [String](../../../system/string/) | Namnområdets URI för elementet. |

### Returvärde

Ett paketobjekt av den mest lämpliga typen. [XmlReader::get_ValueType](../get_valuetype/)-värdet bestämmer den lämpliga typen. Om innehållet är av en listtyp returnerar denna metod en array av paketerade objekt av den lämpliga typen.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [XmlReader](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)