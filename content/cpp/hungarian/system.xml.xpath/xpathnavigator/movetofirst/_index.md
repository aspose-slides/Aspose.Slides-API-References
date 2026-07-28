---
title: MoveToFirst()
second_title: Aspose.Slides C++ API-referencia
description: Áthelyezi az XPathNavigator-t a jelenlegi csomópont első testvércsomópontjára.
type: docs
weight: 612
url: /hu/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() metódus

Áthelyezi a [XPathNavigator](../)-t az aktuális csomópont első testvércsomópontjára.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### Visszatérési érték

**true**, ha a [XPathNavigator](../) sikeresen áthelyeződik az aktuális csomópont első testvércsomópontjára; **false**, ha nincs első testvér, vagy ha a [XPathNavigator](../) jelenleg attribútumcsomóponton áll. Ha a [XPathNavigator](../) már az első testvérnél helyezkedik el, [XPathNavigator](../) **true**-t ad vissza, és nem változtatja meg a pozícióját. Ha [XPathNavigator::MoveToFirst](./) **false**-t ad vissza, mert nincs első testvér, vagy ha [XPathNavigator](../) jelenleg attribútumon áll, a [XPathNavigator](../) pozíciója változatlan marad.

## Lásd még

* Osztály [XPathNavigator](../)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)