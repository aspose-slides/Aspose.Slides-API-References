---
title: ValidateText()
second_title: Aspose.Slides for C++ API referenciája
description: Érvényesíti, hogy a megadott szövegkarakterlánc megengedett-e az aktuális elem kontextusában, és összegyűjti a szöveget az érvényesítéshez, ha az aktuális elem egyszerű tartalommal rendelkezik.
type: docs
weight: 183
url: /hu/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) metódus


Érvényesíti, hogy a megadott **string** szöveg megengedett-e az aktuális elem kontextusában, és összegyűjti a szöveget az érvényesítéshez, ha az aktuális elem egyszerű tartalommal rendelkezik.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Az aktuális elem kontextusában validálandó szöveg **string**. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) metódus


Érvényesíti, hogy a megadott XmlValueGetter objektum által visszaadott szöveg megengedett-e az aktuális elem kontextusában, és összegyűjti a szöveget az érvényesítéshez, ha az aktuális elem egyszerű tartalommal rendelkezik.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Egy XmlValueGetter visszahívás, amely a szövegértéket egy, az XML [Schema](../../) Definíciós Nyelv (XSD) attribútum típusával kompatibilis típusban adja át. |

## Lásd még

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSchemaValidator](../)
* Névterület [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)