---
title: MoveTo()
second_title: Aspose.Slides C++ API referencia
description: Ha egy származtatott osztályban felülírják, a XPathNavigator-t a megadott XPathNavigator-rel megegyező pozícióba helyezi.
type: docs
weight: 664
url: /hu/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) metódus

Amikor felülírják egy származtatott osztályban, a [XPathNavigator](../)-t a megadott [XPathNavigator](../)-val azonos pozícióba viszi.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | A [XPathNavigator](../) a csomóponton, amelyre át szeretnél lépni. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen áthelyeződik a megadott [XPathNavigator](../)-val azonos pozícióba; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathNavigator](../)
* Névtér [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)