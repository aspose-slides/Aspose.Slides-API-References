---
title: WriteStartElement()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, zapisuje określony znacznik początkowy i powiązuje go z podaną przestrzenią nazw.
type: docs
weight: 92
url: /pl/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String&, const String&) metoda


Gdy jest przesłonięta w klasie pochodnej, zapisuje określony znacznik początkowy i powiązuje go z podaną przestrzenią nazw.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nazwa lokalna elementu. |
| ns | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw powiązany z elementem. Jeśli ta przestrzeń nazw jest już w zasięgu i ma powiązany prefiks, pisarz automatycznie zapisze również ten prefiks. |

## XmlWriter::WriteStartElement(const String&, const String&, const String&) metoda


Gdy jest przesłonięta w klasie pochodnej, zapisuje określony znacznik początkowy i powiązuje go z podaną przestrzenią nazw oraz prefiksem.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks przestrzeni nazw elementu. |
| localName | const [String](../../../system/string/)\& | Nazwa lokalna elementu. |
| ns | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw powiązany z elementem. |

## XmlWriter::WriteStartElement(const String&) metoda


Gdy jest przesłonięta w klasie pochodnej, zapisuje znacznik początkowy z określoną nazwą lokalną.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nazwa lokalna elementu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)