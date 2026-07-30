---
title: Schemas()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací kolekci všech schémat jazyka XML Schema definition language (XSD) v XmlSchemaSet.
type: docs
weight: 248
url: /cs/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() metoda

Vrací kolekci všech schémat jazyka XML [Schema](../../) (XSD) v [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Návratová hodnota

Objekt IList obsahující všechna schémata, která byla přidána do [XmlSchemaSet](../). Pokud nebyla do [XmlSchemaSet](../) přidána žádná schémata, vrací se prázdná kolekce.

## XmlSchemaSet::Schemas(String) metoda

Vrací kolekci všech schémat jazyka XML [Schema](../../) (XSD) v [XmlSchemaSet](../), která patří do zadaného jmenného prostoru.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Vlastnost **targetNamespace** schématu. |

### Návratová hodnota

Objekt IList obsahující všechna schémata, která byla přidána do [XmlSchemaSet](../) a patří do zadaného jmenného prostoru. Pokud nebyla do [XmlSchemaSet](../) přidána žádná schémata, vrací se prázdná kolekce.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IList](../../../system.collections.generic/ilist/)
* Třída [XmlSchema](../../xmlschema/)
* Třída [XmlSchemaSet](../)
* Třída [List](../../../system.collections.generic/list/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)