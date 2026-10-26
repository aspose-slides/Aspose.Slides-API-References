---
title: GetAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet på attributet med det angivna namnet.
type: docs
weight: 443
url: /sv/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) metod

Returnerar värdet på attributet med det angivna namnet.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte hittas returneras **nullptr**.

## XmlValidatingReader::GetAttribute(String, String) metod

Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI).

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namnrymdens URI för attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte hittas returneras **nullptr**. Denna metod flyttar inte läsaren.

## XmlValidatingReader::GetAttribute(int32_t) metod

Returnerar värdet på attributet med det angivna indexet.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | **int32_t** | Index för attributet. Indexet är nollbaserat. (Det första attributet har index 0.) |

### Returvärde

Värdet på det angivna attributet.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlValidatingReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)