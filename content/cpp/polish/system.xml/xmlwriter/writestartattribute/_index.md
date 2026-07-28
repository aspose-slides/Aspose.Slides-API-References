---
title: WriteStartAttribute()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zapisuje początek atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.
type: docs
weight: 144
url: /pl/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) metoda

Zapisuje początek atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nazwa lokalna atrybutu. |
| ns | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw atrybutu. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) metoda

Gdy zostanie przesłonięta w klasie pochodnej, zapisuje początek atrybutu z określonym prefiksem, nazwą lokalną i identyfikatorem URI przestrzeni nazw.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks przestrzeni nazw atrybutu. |
| localName | const [String](../../../system/string/)\& | Nazwa lokalna atrybutu. |
| ns | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw atrybutu. |

## XmlWriter::WriteStartAttribute(const String\&) metoda

Zapisuje początek atrybutu o określonej nazwie lokalnej.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nazwa lokalna atrybutu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)