---
title: WriteStartAttribute()
second_title: Aspose.Slides pro C++ – reference API
description: Zapíše začátek atributu se zadaným místním názvem a URI jmenného prostoru.
type: docs
weight: 144
url: /cs/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) metoda

Zapíše začátek atributu se zadaným místním názvem a URI jmenného prostoru.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the attribute. |
| ns | const [String](../../../system/string/)\& | The namespace URI of the attribute. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) metoda

Když je přepsána v odvozené třídě, zapíše začátek atributu se zadaným prefixem, místním názvem a URI jmenného prostoru.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argumenty
| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefix jmenného prostoru atributu. |
| localName | const [String](../../../system/string/)\& | Místní název atributu. |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru pro atribut. |

## XmlWriter::WriteStartAttribute(const String\&) metoda

Zapíše začátek atributu se specifikovaným místním názvem.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Místní název atributu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlWriter](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)