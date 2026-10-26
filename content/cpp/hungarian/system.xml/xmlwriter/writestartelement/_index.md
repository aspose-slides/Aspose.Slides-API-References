---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API Referencia
description: Ha egy leszármazott osztályban felülírják, a megadott nyitóelemet írja ki, és az adott névtérrel társítja.
type: docs
weight: 92
url: /hu/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) metódus

Amikor felülírják egy származtatott osztályban, a megadott nyitóelemet írja ki, és az adott névtérrel társítja.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az elem helyi neve. |
| ns | const [String](../../../system/string/)\& | Az elemhez társítandó névtér URI. Ha ez a névtér már létezik a hatókörben és van hozzá tartozó előtag, a író automatikusan azt is kiírja. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) metódus

Amikor felülírják egy származtatott osztályban, a megadott nyitóelemet írja ki, és az adott névtérrel és előtaggal társítja.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az elem névtér előtagja. |
| localName | const [String](../../../system/string/)\& | Az elem helyi neve. |
| ns | const [String](../../../system/string/)\& | Az elemhez társítandó névtér URI. |

## XmlWriter::WriteStartElement(const String\&) metódus

Amikor felülírják egy származtatott osztályban, a megadott helyi névvel egy nyitóelemet ír ki.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az elem helyi neve. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlWriter](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)