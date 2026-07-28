---
title: XmlSeverityType
second_title: Aspose.Slides C++ API Referencia
description: A validálási esemény súlyosságát reprezentálja.
type: docs
weight: 1080
url: /hu/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enumeráció


A validálási esemény súlyosságát reprezentálja.

```cpp
enum class XmlSeverityType
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| Error | 0 | Azt jelzi, hogy validációs hiba történt a példánydokumentum ellenőrzése során. Ez vonatkozik a dokumentumtípus-definíciókra (DTDs) és az XML [Schema](../) definíciós nyelvre (XSD) sémákra. A World Wide [Web](../../system.web/) Consortium (W3C) érvényességi szabályait hibának tekintik. Ha nincs létrehozva validációs eseménykezelő, a hibák kivételt dobnak. |
| Warning | 1 | Azt jelzi, hogy egy validációs esemény történt, ami nem hiba. A figyelmeztetést általában akkor adják ki, ha nincs DTD, vagy XML [Schema](../) a konkrét elem vagy attribútum ellenőrzéséhez. A hibáktól eltérően a figyelmeztetések nem dobnak kivételt, ha nincs validációs eseménykezelő. |

## Lásd még

* Névterület [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)