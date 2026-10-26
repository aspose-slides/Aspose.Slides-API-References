---
title: XmlNodeChangedEventArgs()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί ένα νέο αντικείμενο της κλάσης XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /el/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) Κατασκευαστής

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Το [XmlNode](../../xmlnode/) που δημιούργησε το συμβάν. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Ο παλιός γονέας [XmlNode](../../xmlnode/) του [XmlNode](../../xmlnode/) που δημιούργησε το συμβάν. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Ο νέος γονέας [XmlNode](../../xmlnode/) του [XmlNode](../../xmlnode/) που δημιούργησε το συμβάν. |
| oldValue | const [String](../../../system/string/)\& | Η παλιά τιμή του [XmlNode](../../xmlnode/) που δημιούργησε το συμβάν. |
| newValue | const [String](../../../system/string/)\& | Η νέα τιμή του [XmlNode](../../xmlnode/) που δημιούργησε το συμβάν. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | Το XmlNodeChangedAction. |

## Δείτε επίσης

* Απαρίθμηση [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlNodeChangedEventArgs](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)