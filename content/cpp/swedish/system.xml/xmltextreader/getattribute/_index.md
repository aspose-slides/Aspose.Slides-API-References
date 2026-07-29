---
title: GetAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet på attributet med det angivna namnet.
type: docs
weight: 495
url: /sv/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) metod

Returnerar värdet på attributet med det angivna namnet.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte hittas, **nullptr** returneras.

## XmlTextReader::GetAttribute(String, String) metod

Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Attributets namnrymds-URI. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte hittas, **nullptr** returneras. Denna metod flyttar inte läsaren.

## XmlTextReader::GetAttribute(int32_t) metod

Returnerar värdet på attributet med det angivna indexet.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | **int32_t** | Indexet för attributet. Indexet är nollbaserat. (Det första attributet har index 0.) |

### Returvärde

Värdet på det angivna attributet.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)