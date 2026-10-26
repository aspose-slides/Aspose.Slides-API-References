---
title: WriteStartAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Skriver början av ett attribut med det angivna lokala namnet och namnrymds-URI:n.
type: docs
weight: 144
url: /sv/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) metod

Skriver början av ett attribut med det angivna lokala namnet och namnrymds-URI:n.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |
| ns | const [String](../../../system/string/)\& | Namnrymds-URI:n för attributet. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) metod

När den åsidosätts i en avledd klass skriver den början av ett attribut med den angivna prefixen, lokala namnet och namnrymds-URI:n.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Namnrymdsprifixet för attributet. |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |
| ns | const [String](../../../system/string/)\& | Namnrymds-URI:n för attributet. |

## XmlWriter::WriteStartAttribute(const String\&) metod

Skriver början av ett attribut med det angivna lokala namnet.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)