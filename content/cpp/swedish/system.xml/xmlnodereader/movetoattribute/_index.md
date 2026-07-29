---
title: MoveToAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar till attributet med det angivna namnet.
type: docs
weight: 300
url: /sv/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) metod

Flyttar till attributet med det angivna namnet.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

**true** om attributet hittas; annars **false**. Om **false** ändras inte läsarens position.

## XmlNodeReader::MoveToAttribute(String, String) metod

Flyttar till attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namnrymdens URI för attributet. |

### Returvärde

**true** om attributet hittas; annars **false**. Om **false** ändras inte läsarens position.

## XmlNodeReader::MoveToAttribute(int32_t) metod

Flyttar till attributet med det angivna indexet.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeIndex | **int32_t** | Index för attributet. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)