---
title: WriteAttributeString()
second_title: Aspose.Slides för C++ API-referens
description: När den överskuggas i en avledd klass skriver den ett attribut med det angivna lokala namnet, namnrymds-URI:n och värdet.
type: docs
weight: 131
url: /sv/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) metod

När den överskuggas i en avledd klass skriver den ett attribut med det angivna lokala namnet, namnrymds-URI:n och värdet.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |
| ns | const [String](../../../system/string/)\& | Namnutrymmes-URI:n att associera med attributet. |
| value | const [String](../../../system/string/)\& | Värdet på attributet. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) metod

När den överskuggas i en avledd klass skriver den ut attributet med det angivna lokala namnet och värdet.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |
| value | const [String](../../../system/string/)\& | Värdet på attributet. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) metod

När den överskuggas i en avledd klass skriver den ut attributet med det angivna prefixet, lokala namnet, namnrymds-URI:n och värdet.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Namnutrymmesprefixet för attributet. |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |
| ns | const [String](../../../system/string/)\& | Namnutrymmes-URI:n för attributet. |
| value | const [String](../../../system/string/)\& | Värdet på attributet. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)