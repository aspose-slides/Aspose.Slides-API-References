---
title: WriteStartAttribute()
second_title: Aspose.Slides C++ API referencia
description: Az attribútum kezdetét írja a megadott helyi név és névtér URI alapján.
type: docs
weight: 144
url: /hu/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) metódus

Az attribútum kezdetét írja a megadott helyi név és névtér URI alapján.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |
| ns | const [String](../../../system/string/)\& | Az attribútum névtér URI-ja. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) metódus

Ha egy származtatott osztályban felül van definiálva, az attribútum kezdetét írja a megadott előtaggal, helyi névvel és névtér URI-val.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az attribútum névtérelőtagja. |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |
| ns | const [String](../../../system/string/)\& | Az attribútum névtér URI-ja. |

## XmlWriter::WriteStartAttribute(const String\&) metódus

Az attribútum kezdetét írja a megadott helyi névvel.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |

## Kapcsolódó információk

* Osztály [String](../../../system/string/)
* Osztály [XmlWriter](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)