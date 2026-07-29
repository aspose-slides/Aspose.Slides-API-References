---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar attributet med det angivna indexet.
type: docs
weight: 1
url: /sv/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) metod


Returnerar attributet med det angivna indexet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | **int32_t** | Index för attributet. |

### Returvärde

Attributet vid det angivna indexet.

## XmlAttributeCollection::idx_get(const String\&) metod


Returnerar attributet med det angivna namnet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Det kvalificerade namnet på attributet. |

### Returvärde

Attributet med det angivna namnet. Om attributet inte finns, returnerar denna metod **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) metod


Returnerar attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |
| namespaceURI | const [String](../../../system/string/)\& | Namnrymdens URI för attributet. |

### Returvärde

Attributet med det angivna lokala namnet och namnrymdens URI. Om attributet inte finns, returnerar denna metod **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlAttribute](../../xmlattribute/)
* Klass [XmlAttributeCollection](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)