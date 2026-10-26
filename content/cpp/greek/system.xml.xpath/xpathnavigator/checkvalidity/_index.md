---
title: CheckValidity()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επαληθεύει ότι τα δεδομένα XML στον XPathNavigator συμμορφώνονται με το παρεχόμενο σχήμα γλώσσας ορισμού XML Schema (XSD).
type: docs
weight: 755
url: /el/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method

Επαληθεύει ότι τα δεδομένα XML στο [XPathNavigator](../) συμμορφώνονται με τη γλώσσα ορισμού XML [Schema](../../../system.xml.schema/) (XSD) σχήμα που παρέχεται.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | Το XmlSchemaSet που περιέχει τα σχήματα που χρησιμοποιούνται για την επικύρωση των δεδομένων XML που περιέχονται στο [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Το ValidationEventHandler που λαμβάνει πληροφορίες σχετικά με προειδοποιήσεις και σφάλματα επικύρωσης σχήματος. |

### Τιμή Επιστροφής

**true** εάν δεν προέκυψαν σφάλματα επικύρωσης σχήματος· διαφορετικά, **false**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Κλάση [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Κλάση [XPathNavigator](../)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)