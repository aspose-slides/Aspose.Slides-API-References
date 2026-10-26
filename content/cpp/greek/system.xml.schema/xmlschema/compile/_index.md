---
title: Compile()
second_title: Αναφορά API Aspose.Slides για C++
description: Συμπιέζει το XML SchemaObject Model (SOM) σε πληροφορίες σχήματος για επικύρωση. Χρησιμοποιείται για τον έλεγχο της συντακτικής και σημασιολογικής δομής του προγραμματιστικά κατασκευασμένου SOM. Η σημασιολογική επαλήθευση εκτελείται κατά τη διάρκεια της μεταγλώττισης.
type: docs
weight: 352
url: /el/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) μέθοδος

Συμπιέζει το XML [Schema](../../)[Object](../../../system/object/) Model (SOM) σε πληροφορίες σχήματος για επικύρωση. Χρησιμοποιείται για τον έλεγχο της συντακτικής και σημασιολογικής δομής του προγραμματιστικά κατασκευασμένου SOM. Η σημασιολογική επαλήθευση εκτελείται κατά τη διάρκεια της μεταγλώττισης.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Ο διαχειριστής συμβάντων επικύρωσης που λαμβάνει πληροφορίες σχετικά με σφάλματα επικύρωσης XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) μέθοδος

Συμπιέζει το XML [Schema](../../)[Object](../../../system/object/) Model (SOM) σε πληροφορίες σχήματος για επικύρωση. Χρησιμοποιείται για τον έλεγχο της συντακτικής και σημασιολογικής δομής του προγραμματιστικά κατασκευασμένου SOM. Η σημασιολογική επαλήθευση εκτελείται κατά τη διάρκεια της μεταγλώττισης.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Ο διαχειριστής συμβάντων επικύρωσης που λαμβάνει πληροφορίες σχετικά με σφάλματα επικύρωσης XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση των ονομάτων χώρου που αναφέρονται στα στοιχεία **include** και **import**. |

## Δείτε επίσης

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlSchema](../)
* Κλάση [XmlResolver](../../../system.xml/xmlresolver/)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)