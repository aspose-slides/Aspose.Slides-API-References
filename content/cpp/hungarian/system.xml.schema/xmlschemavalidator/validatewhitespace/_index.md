---
title: ValidateWhitespace()
second_title: Aspose.Slides for C++ API referencia
description: Ellenőrzi, hogy a megadott karakterláncban lévő fehér szóköz megengedett-e az aktuális elemkörnyezetben, és ha az aktuális elem egyszerű tartalommal rendelkezik, összegyűjti a fehér szóközt az érvényesítéshez.
type: docs
weight: 196
url: /hu/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) metódus

Ellenőrzi, hogy a megadott **karakterlánc** fehér szóköze megengedett-e az aktuális elemkörnyezetben, és összegyűjti a fehér szóközt az érvényesítéshez, ha az aktuális elem egyszerű tartalommal rendelkezik.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Az aktuális elemkörnyezetben ellenőrzendő fehér szóköz **karakterlánc**. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) metódus

Érvényesíti, hogy a megadott XmlValueGetter objektum által visszaadott fehér szóköz megengedett-e az aktuális elemkörnyezetben, és összegyűjti a fehér szóközt az érvényesítéshez, ha az aktuális elem egyszerű tartalommal rendelkezik.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Egy XmlValueGetter visszahívás, amely a fehér szóköz értékét egy olyan típusként adja át, amely kompatibilis az XML [Schema](../../) Definition Language (XSD) attribútum típusával. |

## Lásd még

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSchemaValidator](../)
* Névtér [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)