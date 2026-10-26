---
title: MoveToAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar till attributet med det angivna namnet.
type: docs
weight: 456
url: /sv/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) metod

Flyttar till attributet med det angivna namnet.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

**true** om attributet hittas; annars **false**. Om **false** förändras inte läsarens position.

## XmlValidatingReader::MoveToAttribute(String, String) metod

Flyttar till attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namnområdets URI för attributet. |

### Returvärde

**true** om attributet hittas; annars **false**. Om **false** förändras inte läsarens position.

## XmlValidatingReader::MoveToAttribute(int32_t) metod

Flyttar till attributet med det angivna indexet.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | **int32_t** | Indexet för attributet. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlValidatingReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)