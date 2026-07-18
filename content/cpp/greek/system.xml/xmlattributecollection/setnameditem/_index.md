---
title: SetNamedItem()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: "Προσθέτει ένα XmlNode χρησιμοποιώντας το αποτέλεσμα του XmlNode::get_Name."
type: docs
weight: 14
url: /el/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) μέθοδος


Προσθέτει ένα [XmlNode](../../xmlnode/) χρησιμοποιώντας το [XmlNode::get_Name](../../xmlnode/get_name/) αποτέλεσμα.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Ένας attribute node για αποθήκευση σε αυτή τη συλλογή. Ο node θα είναι αργότερα προσβάσιμος μέσω του ονόματος του node. Εάν υπάρχει ήδη ένας node με αυτό το όνομα στη συλλογή, αντικαθίσταται από τον νέο· διαφορετικά, ο node προσαρτάται στο τέλος της συλλογής. |

### Τιμή Επιστροφής

Αν το **node** αντικαταστήσει έναν υπάρχοντα node με το ίδιο όνομα, ο παλιός node επιστρέφεται· διαφορετικά, επιστρέφεται ο προστιθέμενος node.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlAttributeCollection](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)