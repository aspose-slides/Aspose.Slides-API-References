---
title: ToString()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja az XmlQualifiedName karakterlánc értékét.
type: docs
weight: 79
url: /hu/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const metódus

Visszaadja a [XmlQualifiedName](../) karakterlánc értékét.

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### Visszatérési érték

A [XmlQualifiedName](../) karakterláncértéke **namespace:localname** formátumban. Ha az objektumnak nincs definiált névtere, ez a metódus csak a helyi nevet adja vissza.

## XmlQualifiedName::ToString(const String\&, const String\&) metódus

Visszaadja a [XmlQualifiedName](../) karakterlánc értékét.

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Az objektum neve. |
| ns | const [String](../../../system/string/)\& | Az objektum névtere. |

### Visszatérési érték

A [XmlQualifiedName](../) karakterláncértéke **namespace:localname** formátumban. Ha az objektumnak nincs definiált névtere, ez a metódus csak a helyi nevet adja vissza.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlQualifiedName](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)