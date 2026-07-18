---
title: XmlParserContext()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης XmlParserContext με τις καθορισμένες τιμές XmlNameTable, XmlNamespaceManager, xml:lang, και xml:space."
type: docs
weight: 261
url: /el/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmlParserContext](../) με τις καθορισμένες [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, και **xml:space** τιμές.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί για την ατομικοποίηση των συμβολοσειρών. Εάν αυτό είναι **nullptr**, χρησιμοποιείται ο πίνακας ονομάτων που χρησιμοποιήθηκε για τη δημιουργία του **nsMgr**. Για περισσότερες πληροφορίες σχετικά με τις ατομικοποιημένες συμβολοσειρές, δείτε [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Το [XmlNamespaceManager](../../xmlnamespacemanager/) που θα χρησιμοποιηθεί για την αναζήτηση πληροφοριών χώρου ονομάτων, ή **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Η εμβέλεια **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Μια τιμή XmlSpace που υποδεικνύει την εμβέλεια **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmlParserContext](../) με τις καθορισμένες [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, και κωδικοποίηση.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί για την ατομικοποίηση των συμβολοσειρών. Εάν αυτό είναι **nullptr**, χρησιμοποιείται ο πίνακας ονομάτων που δημιουργήθηκε για το **nsMgr**. Για περισσότερες πληροφορίες σχετικά με τις ατομικοποιημένες συμβολοσειρές, δείτε [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Το [XmlNamespaceManager](../../xmlnamespacemanager/) που θα χρησιμοποιηθεί για την αναζήτηση πληροφοριών χώρου ονομάτων, ή **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Η εμβέλεια **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Μια τιμή XmlSpace που υποδεικνύει την εμβέλεια **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Ένα αντικείμενο Encoding που υποδεικνύει τη ρύθμιση κωδικοποίησης. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmlParserContext](../) με τις καθορισμένες [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, και τιμές τύπου εγγράφου.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί για την ατομικοποίηση των συμβολοσειρών. Εάν αυτό είναι **nullptr**, χρησιμοποιείται ο πίνακας ονομάτων του **nsMgr**. Για περισσότερες πληροφορίες σχετικά με τις ατομικοποιημένες συμβολοσειρές, δείτε [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Το [XmlNamespaceManager](../../xmlnamespacemanager/) που θα χρησιμοποιηθεί για την αναζήτηση πληροφοριών χώρου ονομάτων, ή **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Το όνομα της δήλωσης τύπου εγγράφου. |
| pubId | const [String](../../../system/string/)\& | Ο δημόσιος ταυτοποιητής. |
| sysId | const [String](../../../system/string/)\& | Ο ταυτοποιητής συστήματος. |
| internalSubset | const [String](../../../system/string/)\& | Το εσωτερικό υποσύνολο DTD. Το υποσύνολο DTD χρησιμοποιείται για την ανάλυση οντοτήτων, όχι για την επικύρωση εγγράφου. |
| baseURI | const [String](../../../system/string/)\& | Το βασικό URI για το απόσπασμα XML (η θέση από την οποία φορτώθηκε το απόσπασμα). |
| xmlLang | const [String](../../../system/string/)\& | Η εμβέλεια **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Μια τιμή XmlSpace που υποδεικνύει την εμβέλεια **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmlParserContext](../) με τις καθορισμένες [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, κωδικοποίηση και τιμές τύπου εγγράφου.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί για την ατομικοποίηση των συμβολοσειρών. Εάν αυτό είναι **nullptr**, χρησιμοποιείται ο πίνακας ονομάτων του **nsMgr**. Για περισσότερες πληροφορίες σχετικά με τις ατομικοποιημένες συμβολοσειρές, δείτε [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Το [XmlNamespaceManager](../../xmlnamespacemanager/) που θα χρησιμοποιηθεί για την αναζήτηση πληροφοριών χώρου ονομάτων, ή **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Το όνομα της δήλωσης τύπου εγγράφου. |
| pubId | const [String](../../../system/string/)\& | Ο δημόσιος ταυτοποιητής. |
| sysId | const [String](../../../system/string/)\& | Ο ταυτοποιητής συστήματος. |
| internalSubset | const [String](../../../system/string/)\& | Το εσωτερικό υποσύνολο DTD. Το DTD χρησιμοποιείται για την ανάλυση οντοτήτων, όχι για την επικύρωση εγγράφου. |
| baseURI | const [String](../../../system/string/)\& | Το βασικό URI για το απόσπασμα XML (η θέση από την οποία φορτώθηκε το απόσπασμα). |
| xmlLang | const [String](../../../system/string/)\& | Η εμβέλεια **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Μια τιμή XmlSpace που υποδεικνύει την εμβέλεια **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Ένα αντικείμενο Encoding που υποδεικνύει τη ρύθμιση κωδικοποίησης. |

## Δείτε επίσης

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)