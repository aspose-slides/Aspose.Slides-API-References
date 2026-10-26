---
title: AddSort()
second_title: Αναφορά API του Aspose.Slides για C++
description: Όταν υπερκαλύπτεται σε μια παράγωγη κλάση, ταξινομεί τους κόμβους που επιλέγονται από την έκφραση XPath σύμφωνα με το καθορισμένο αντικείμενο IComparer.
type: docs
weight: 27
url: /el/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) μέθοδος

When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the specified IComparer object.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Ένα αντικείμενο που αντιπροσωπεύει το κλειδί ταξινόμησης. Αυτό μπορεί να είναι η τιμή **string** του κόμβου ή ένα αντικείμενο [XPathExpression](../) με μια μεταγλωττισμένη έκφραση [XPath](../../). |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Ένα αντικείμενο IComparer που παρέχει τις συγκεκριμένες συγκρίσεις τύπου δεδομένων για τη σύγκριση δύο αντικειμένων για ισοδυναμία. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) μέθοδος

When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the supplied parameters.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Ένα αντικείμενο που αντιπροσωπεύει το κλειδί ταξινόμησης. Αυτό μπορεί να είναι η τιμή **string** του κόμβου ή ένα αντικείμενο [XPathExpression](../) με μια μεταγλωττισμένη έκφραση [XPath](../../). |
| order | [XmlSortOrder](../../xmlsortorder/) | Μια τιμή XmlSortOrder που υποδεικνύει τη σειρά ταξινόμησης. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Μια τιμή XmlCaseOrder που υποδεικνύει πώς να ταξινομηθούν τα κεφαλαία και πεζά γράμματα. |
| lang | [String](../../../system/string/) | Η γλώσσα που θα χρησιμοποιηθεί για τη σύγκριση. Χρησιμοποιεί την κλάση [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) που μπορεί να περαστεί στη μέθοδο [String::Compare](../../../system/string/compare/) για τους τύπους γλώσσας, για παράδειγμα, \"us-en\" για τα αγγλικά Η.Π.Α. Εάν δοθεί κενό κείμενο, το σύστημα περιβάλλοντος χρησιμοποιείται για τον προσδιορισμό του [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Μια τιμή XmlDataType που υποδεικνύει τη σειρά ταξινόμησης για τον τύπο δεδομένων. |

## Δείτε επίσης

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)