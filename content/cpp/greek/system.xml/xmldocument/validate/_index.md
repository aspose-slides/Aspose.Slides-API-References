---
title: Validate()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Επικυρώνει το XmlDocument έναντι των σχημάτων XML Schema Definition Language (XSD) που περιέχονται στη λίστα XmlDocument::get_Schemas."
type: docs
weight: 573
url: /el/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) μέθοδος

Επικυρώνει το [XmlDocument](../) έναντι των σχημάτων XML [Schema](../../../system.xml.schema/) Definition Language (XSD) που περιέχονται στη λίστα [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Το αντικείμενο [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) που λαμβάνει πληροφορίες για προειδοποιήσεις και σφάλματα επικύρωσης σχήματος. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) μέθοδος

Επικυρώνει το συγκεκριμένο αντικείμενο [XmlNode](../../xmlnode/) έναντι των σχημάτων XML [Schema](../../../system.xml.schema/) Definition Language (XSD) που βρίσκονται στη λίστα [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Το αντικείμενο [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) που λαμβάνει πληροφορίες για προειδοποιήσεις και σφάλματα επικύρωσης σχήματος. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Το αντικείμενο [XmlNode](../../xmlnode/) που δημιουργήθηκε από ένα [XmlDocument](../) για την επικύρωση. |

## Δείτε επίσης

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlDocument](../)
* Κλάση [XmlNode](../../xmlnode/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)