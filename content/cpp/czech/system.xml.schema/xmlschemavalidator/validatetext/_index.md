---
title: ValidateText()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Ověřuje, zda je zadaný textový řetězec povolen v aktuálním kontextu elementu, a shromažďuje text pro validaci, pokud má aktuální element jednoduchý obsah.
type: docs
weight: 183
url: /cs/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) method

Ověřuje, zda je zadaný text **string** povolen v aktuálním kontextu elementu, a shromažďuje text pro validaci, pokud má aktuální element jednoduchý obsah.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Textová **string** k validaci v aktuálním kontextu elementu. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) method

Ověřuje, zda je text vrácený objektem XmlValueGetter povolen v aktuálním kontextu elementu, a shromažďuje text pro validaci, pokud má aktuální element jednoduchý obsah.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Callback XmlValueGetter používaný k předání hodnoty textu jako typu kompatibilního s typem XML [Schema](../../) Definition Language (XSD) atributu. |

## Viz také

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Třída [String](../../../system/string/)
* Třída [XmlSchemaValidator](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)