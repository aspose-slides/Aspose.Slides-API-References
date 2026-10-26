---
title: WriteStartElement()
second_title: Aspose.Slides pro C++ API Reference
description: Když je přepsána v odvozené třídě, zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru.
type: docs
weight: 92
url: /cs/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) metoda

Když je přepsána v odvozené třídě, zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Lokální název prvku. |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru, který se má přiřadit k prvku. Pokud je tento jmenný prostor již v rozsahu a má přiřazenou předponu, zapisovač automaticky zapíše i tuto předponu. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) metoda

Když je přepsána v odvozené třídě, zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru a předponě.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Předpona jmenného prostoru prvku. |
| localName | const [String](../../../system/string/)\& | Lokální název prvku. |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru, který se má přiřadit k prvku. |

## XmlWriter::WriteStartElement(const String\&) metoda

Když je přepsána v odvozené třídě, zapíše úvodní tag se zadaným lokálním názvem.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Lokální název prvku. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlWriter](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)