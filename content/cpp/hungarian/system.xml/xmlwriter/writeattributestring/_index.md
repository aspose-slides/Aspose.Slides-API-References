---
title: WriteAttributeString()
second_title: Aspose.Slides C++ API referencia
description: Ha egy származtatott osztályban felül van definiálva, akkor egy attribútumot ír ki a megadott helyi név, névtér URI és érték alapján.
type: docs
weight: 131
url: /hu/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String&, const String&, const String&) metódus

Ha egy származtatott osztályban felül van definiálva, akkor egy attribútumot ír ki a megadott helyi név, névtér URI és érték alapján.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |
| ns | const [String](../../../system/string/)\& | Az attribútumhoz társítandó névtér URI. |
| value | const [String](../../../system/string/)\& | Az attribútum értéke. |

## XmlWriter::WriteAttributeString(const String&, const String&) metódus

Ha egy származtatott osztályban felül van definiálva, akkor kiírja az attribútumot a megadott helyi név és érték alapján.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |
| value | const [String](../../../system/string/)\& | Az attribútum értéke. |

## XmlWriter::WriteAttributeString(const String&, const String&, const String&, const String&) metódus

Ha egy származtatott osztályban felül van definiálva, akkor kiírja az attribútumot a megadott előtag, helyi név, névtér URI és érték alapján.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az attribútum névtér előtagja. |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |
| ns | const [String](../../../system/string/)\& | Az attribútum névtér URI-ja. |
| value | const [String](../../../system/string/)\& | Az attribútum értéke. |

## Lásd még

* osztály [String](../../../system/string/)
* osztály [XmlWriter](../)
* névtér [System::Xml](../../)
* könyvtár [Aspose.Slides](../../../)