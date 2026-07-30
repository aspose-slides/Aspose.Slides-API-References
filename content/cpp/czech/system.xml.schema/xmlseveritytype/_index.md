---
title: XmlSeverityType
second_title: Aspose.Slides pro C++ referenční příručka API
description: Reprezentuje závažnost validační události.
type: docs
weight: 1080
url: /cs/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType výčtový typ

Reprezentuje závažnost validační události.

```cpp
enum class XmlSeverityType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Error | 0 | Indikuje, že při validaci instance dokumentu došlo k validační chybě. Toto se vztahuje na definice typů dokumentů (DTDs) a XML [Schema](../) definice jazyka (XSD) schémata. World Wide [Web](../../system.web/) Consortium (W3C) omezení platnosti jsou považována za chyby. Pokud nebyl vytvořen žádný handler validační události, chyby vyvolají výjimku. |
| Warning | 1 | Indikuje, že nastala validační událost, která není chybou. Varování je typicky vydáno, když není DTD nebo XML [Schema](../) k validaci konkrétního elementu nebo atributu. Na rozdíl od chyb varování nevyvolají výjimku, pokud neexistuje handler validační události. |

## Viz také

* Jmenný prostor [System::Xml::Schema](../)
* Knihovna [Aspose.Slides](../../)