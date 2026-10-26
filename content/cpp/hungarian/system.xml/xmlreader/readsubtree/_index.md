---
title: ReadSubtree()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy új XmlReader példányt, amely felhasználható az aktuális csomópont és minden leszármazottjának olvasására.
type: docs
weight: 963
url: /hu/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() metódus

Visszaad egy új [XmlReader](../) példányt, amely felhasználható az aktuális csomópont és minden leszármazottjának olvasására.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Visszatérési érték

Egy új XML-olvasó példány, amely [ReadState::Initial](../../readstate/)-ra van beállítva. A [XmlReader::Read](../read/) metódus hívása a új olvasót arra a csomópontra helyezi, amely a [XmlReader::ReadSubtree](./) metódus hívása előtt aktuális volt.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)