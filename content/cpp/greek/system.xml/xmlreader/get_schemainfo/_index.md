---
title: get_SchemaInfo()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει τις πληροφορίες σχήματος που έχουν ανατεθεί στον τρέχοντα κόμβο ως αποτέλεσμα της επικύρωσης σχήματος.
type: docs
weight: 196
url: /el/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() μέθοδος


Επιστρέφει τις πληροφορίες σχήματος που έχουν ανατεθεί στον τρέχοντα κόμβο ως αποτέλεσμα της επικύρωσης σχήματος.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### Τιμή επιστροφής

Ένα αντικείμενο IXmlSchemaInfo που περιέχει τις πληροφορίες σχήματος για τον τρέχοντα κόμβο. [Schema](../../../system.xml.schema/) πληροφορίες μπορούν να οριστούν σε στοιχεία, χαρακτηριστικά ή σε κόμβους κειμένου με μη μηδενική τιμή [XmlReader::get_ValueType](../get_valuetype/). Αν ο τρέχων κόμβος δεν είναι ένας από τους παραπάνω τύπους κόμβων, ή αν η παρουσία [XmlReader](../) δεν αναφέρει πληροφορίες σχήματος, αυτή η μέθοδος επιστρέφει **nullptr**. Αν αυτή η μέθοδος κληθεί από ένα αντικείμενο [XmlTextReader](../../xmltextreader/) ή ένα αντικείμενο [XmlValidatingReader](../../xmlvalidatingreader/), αυτή η μέθοδος πάντα επιστρέφει **nullptr**. Αυτές οι υλοποιήσεις [XmlReader](../) δεν εκθέτουν πληροφορίες σχήματος μέσω της μεθόδου get_SchemaInfo.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)