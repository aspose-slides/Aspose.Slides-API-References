---
title: Schemas()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy gyűjteményt az összes XML Schema definíciós nyelv (XSD) sémáról az XmlSchemaSet-ben.
type: docs
weight: 248
url: /hu/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() módszer


Visszaad egy gyűjteményt az összes XML [Schema](../../) definíciós nyelv (XSD) sémáról a [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### Visszatérési érték

Egy IList objektum, amely tartalmazza az összes sémát, amely a [XmlSchemaSet](../)-hez lett hozzáadva. Ha a [XmlSchemaSet](../)-hez nem lett semmilyen séma hozzáadva, egy üres gyűjtemény kerül visszaadásra.

## XmlSchemaSet::Schemas(String) módszer


Visszaad egy gyűjteményt az összes XML [Schema](../../) definíciós nyelv (XSD) sémáról a [XmlSchemaSet](../)-ben, amely az adott névtérhez tartozik.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | A séma **targetNamespace** tulajdonsága. |

### Visszatérési érték

Egy IList objektum, amely tartalmazza az összes sémát, amely a [XmlSchemaSet](../)-hez lett hozzáadva, és az adott névtérhez tartozik. Ha a [XmlSchemaSet](../)-hez nem lett semmilyen séma hozzáadva, egy üres gyűjtemény kerül visszaadásra.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IList](../../../system.collections.generic/ilist/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [XmlSchemaSet](../)
* Osztály [List](../../../system.collections.generic/list/)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)