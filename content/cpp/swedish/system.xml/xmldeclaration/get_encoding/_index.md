---
title: get_Encoding()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar kodningsnivån för XML-dokumentet.
type: docs
weight: 14
url: /sv/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() metod

Returnerar kodningsnivån för XML-dokumentet.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Returvärde

Det giltiga teckenkodningsnamnet.
## Anmärkningar

De mest vanligt stödjade teckenkodningsnamnen för XML är följande:

| Kategori | Kodningsnamn |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (där "n" är en siffra från 1 till 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Detta värde är valfritt. Om inget värde är angivet returnerar denna metod [String::Empty](../../../system/string/empty/). Om ett kodningsattribut inte inkluderas antas UTF-8-kodning när dokumentet skrivs eller sparas.
## Se även

* Klass [String](../../../system/string/)
* Klass [XmlDeclaration](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)