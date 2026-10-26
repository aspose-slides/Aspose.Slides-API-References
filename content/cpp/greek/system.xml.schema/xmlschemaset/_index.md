---
title: XmlSchemaSet
second_title: Aspose.Slides για C++ – Αναφορά API
description: Περιέχει μια κρυφή μνήμη σχημάτων XML Schema definition language (XSD).
type: docs
weight: 781
url: /el/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet κλάση

Contains a cache of XML [Schema](../) definition language (XSD) schemas.

```cpp
class XmlSchemaSet : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | Προσθέτει το σχήμα XML [Schema](../) γλώσσα ορισμού (XSD) στη διεύθυνση URL που καθορίζεται στο [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Προσθέτει το σχήμα XML [Schema](../) γλώσσα ορισμού (XSD) που περιέχεται στο [XmlReader](../../system.xml/xmlreader/) στο [XmlSchemaSet](./). |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | Προσθέτει όλα τα σχήματα XML [Schema](../) γλώσσας ορισμού (XSD) στο δεδομένο [XmlSchemaSet](./) στο [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Προσθέτει το δεδομένο [XmlSchema](../xmlschema/) στο [XmlSchemaSet](./). |
| void [Compile](./compile/)() | Συγκεντρώνει τα σχήματα XML [Schema](../) γλώσσα ορισμού (XSD) που προστέθηκαν στο [XmlSchemaSet](./) σε ένα λογικό σχήμα. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | Δηλώνει εάν ένα σχήμα XML [Schema](../) γλώσσα ορισμού (XSD) με το καθορισμένο URI του χώρου ονομάτων προορισμού βρίσκεται στο [XmlSchemaSet](./). |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Δηλώνει εάν το καθορισμένο αντικείμενο XML [Schema](../) γλώσσα ορισμού (XSD) [XmlSchema](../xmlschema/) βρίσκεται στο [XmlSchemaSet](./). |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | Αντιγράφει όλα τα αντικείμενα [XmlSchema](../xmlschema/) από το [XmlSchemaSet](./) στον δεδομένο πίνακα, αρχίζοντας από το δεδομένο δείκτη. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με το στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με το στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση διπλής ακρίβειας σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | Επιστρέφει το [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) για το [XmlSchemaSet](./). |
| **int32_t** [get_Count](./get_count/)() | Επιστρέφει τον αριθμό των λογικών σχημάτων XML [Schema](../) γλώσσα ορισμού (XSD) στο [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | Επιστρέφει όλα τα καθολικά χαρακτηριστικά σε όλα τα σχήματα XML [Schema](../) γλώσσα ορισμού (XSD) στο [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | Επιστρέφει όλα τα καθολικά στοιχεία σε όλα τα σχήματα XML [Schema](../) γλώσσα ορισμού (XSD) στο [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | Επιστρέφει όλους τους καθολικούς απλούς και σύνθετους τύπους σε όλα τα σχήματα XML [Schema](../) γλώσσα ορισμού (XSD) στο [XmlSchemaSet](./). |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Επιστρέφει τιμή που υποδεικνύει εάν τα σχήματα XML [Schema](../) γλώσσα ορισμού (XSD) στο [XmlSchemaSet](./) έχουν συναρτηθεί. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Επιστρέφει το προεπιλεγμένο [XmlNameTable](../../system.xml/xmlnametable/) που χρησιμοποιείται από το [XmlSchemaSet](./) κατά τη φόρτωση νέων σχημάτων XML [Schema](../) γλώσσα ορισμού (XSD). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών με αντιγραφή. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών με αντιγραφή. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφοράς αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειρών. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Αφαιρεί το καθορισμένο σχήμα XML [Schema](../) γλώσσα ορισμού (XSD) από το [XmlSchemaSet](./). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστης αναφοράς κατά την καθορισμένη τιμή. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Αφαιρεί το καθορισμένο σχήμα XML [Schema](../) γλώσσα ορισμού (XSD) και όλα τα σχήματα που εισάγει από το [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | Επεξεργάζεται εκ νέου ένα σχήμα XML [Schema](../) γλώσσα ορισμού (XSD) που υπάρχει ήδη στο [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | Επιστρέφει μια συλλογή όλων των σχημάτων XML [Schema](../) γλώσσα ορισμού (XSD) στο [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | Επιστρέφει μια συλλογή όλων των σχημάτων XML [Schema](../) γλώσσα ορισμού (XSD) στο [XmlSchemaSet](./) που ανήκουν στον δοθέντα χώρο ονομάτων. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | Ορίζει το [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) για το [XmlSchemaSet](./). |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Ορίζει το [XmlResolver](../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση χώρων ονομάτων ή τοποθεσιών που αναφέρονται στα στοιχεία include και import ενός σχήματος. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύνατη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύνατη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Προσθέτει χειριστή συμβάντος για λήψη πληροφοριών σχετικά με σφάλματα επαλήθευσης σχήματος XML [Schema](../) γλώσσα ορισμού (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Αφαιρεί χειριστή συμβάντος για λήψη πληροφοριών σχετικά με σφάλματα επαλήθευσης σχήματος XML [Schema](../) γλώσσα ορισμού (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
|  [XmlSchemaSet](./xmlschemaset/)() | Αρχικοποιεί νέο στιγμιότυπο της κλάσης [XmlSchemaSet](./). |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | Αρχικοποιεί νέο στιγμιότυπο της κλάσης [XmlSchemaSet](./) με το καθορισμένο [XmlNameTable](../../system.xml/xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τύποι

| Τύπος | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για δείκτη κοινής χρήσης προς ένα στιγμιότυπο αυτής της κλάσης. |

## Παρατηρήσεις

Τα αντικείμενα αυτής της κλάσης θα πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπα αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως παράμετρο. 

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Ονομαχώρος [System::Xml::Schema](../)
* Βιβλιοθήκη [Aspose.Slides](../../)