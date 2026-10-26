---
title: MoveTo()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Při přepsání v odvozené třídě přesune XPathNavigator na stejnou pozici jako zadaný XPathNavigator.
type: docs
weight: 664
url: /cs/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) metoda

Při přepsání v odvozené třídě přesune [XPathNavigator](../) na stejnou pozici jako určený [XPathNavigator](../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | The [XPathNavigator](../) umístěný na uzlu, na který se chcete přesunout. |

### Návratová hodnota

**true** if the [XPathNavigator](../) is successful moving to the same position as the specified [XPathNavigator](../); otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)