---
title: MoveToFirst()
second_title: Aspose.Slides pro C++ API Reference
description: Přesune XPathNavigator na první sourozenecký uzel aktuálního uzlu.
type: docs
weight: 612
url: /cs/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() metoda


Přesune [XPathNavigator](../) na první sourozenecký uzel aktuálního uzlu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšné přesunutí na první sourozenecký uzel aktuálního uzlu; **false** pokud neexistuje první sourozenec, nebo pokud je [XPathNavigator](../) v současnosti umístěn na uzlu atributu. Pokud je [XPathNavigator](../) již umístěn na první sourozenec, [XPathNavigator](../) vrátí **true** a jeho pozice se nezmění. Pokud [XPathNavigator::MoveToFirst](./) vrátí **false**, protože neexistuje první sourozenec, nebo pokud je [XPathNavigator](../) v současnosti umístěn na atribut, pozice [XPathNavigator](../) zůstane nezměněna.

## Viz také

* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)