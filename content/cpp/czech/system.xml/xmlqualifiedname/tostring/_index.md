---
title: ToString()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací řetězcovou hodnotu XmlQualifiedName.
type: docs
weight: 79
url: /cs/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const metoda


Vrací řetězcovou hodnotu [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Návratová hodnota

Řetězcová hodnota [XmlQualifiedName](../) ve formátu **namespace:localname**. Pokud objekt nemá definovaný jmenný prostor, tato metoda vrátí pouze místní název.

## XmlQualifiedName::ToString(const String\&, const String\&) metoda


Vrací řetězcovou hodnotu [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název objektu. |
| ns | const [String](../../../system/string/)\& | Jmenný prostor objektu. |

### Návratová hodnota

Řetězcová hodnota [XmlQualifiedName](../) ve formátu **namespace:localname**. Pokud objekt nemá definovaný jmenný prostor, tato metoda vrátí pouze místní název.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlQualifiedName](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)