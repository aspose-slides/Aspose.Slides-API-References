---
title: XmlReaderSettings
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει ένα σύνολο λειτουργιών που υποστηρίζονται στο αντικείμενο XmlReader που δημιουργείται από τη μέθοδο XmlReader::Create."
type: docs
weight: 443
url: /el/system.xml/xmlreadersettings/
---
## XmlReaderSettings κλάση

Καθορίζει ένα σύνολο λειτουργιών που υποστηρίζονται στο αντικείμενο [XmlReader](../xmlreader/) που δημιουργείται από τη μέθοδο [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Δημιουργεί ένα αντίγραφο του αντικειμένου [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσοι, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσοι, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Επιστρέφει τιμή που υποδεικνύει εάν θα γίνει έλεγχος χαρακτήρων. |
| **bool** [get_CloseInput](./get_closeinput/)() | Επιστρέφει τιμή που υποδεικνύει εάν η υποκείμενη ροή ή το TextReader πρέπει να κλείσει όταν κλείνει ο αναγνώστης. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Επιστρέφει το επίπεδο συμμόρφωσης που θα τηρήσει το [XmlReader](../xmlreader/). |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Επιστρέφει τιμή που καθορίζει την επεξεργασία των DTD. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Επιστρέφει τιμή που υποδεικνύει εάν θα αγνοηθούν τα σχόλια. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Επιστρέφει τιμή που υποδεικνύει εάν θα αγνοηθούν οι οδηγίες επεξεργασίας. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Επιστρέφει τιμή που υποδεικνύει εάν θα αγνοηθεί το ασήμαντο λευκό διάστημα. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Επιστρέφει τη μετατόπιση αριθμού γραμμής του αντικειμένου [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Επιστρέφει τη μετατόπιση θέσης γραμμής του αντικειμένου [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Επιστρέφει τιμή που υποδεικνύει το μέγιστο επιτρεπτό αριθμό χαρακτήρων σε ένα έγγραφο που προκύπτει από την επέκταση των οντοτήτων. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Επιστρέφει τιμή που υποδεικνύει το μέγιστο επιτρεπτό αριθμό χαρακτήρων σε ένα XML έγγραφο. Μια τιμή μηδέν (0) σημαίνει ότι δεν υπάρχουν όρια στο μέγεθος του XML εγγράφου. Μια μη μηδενική τιμή καθορίζει το μέγιστο μέγεθος, σε χαρακτήρες. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Επιστρέφει το [XmlNameTable](../xmlnametable/) που χρησιμοποιείται για ατομικές συγκρίσεις συμβολοσειρών. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Επιστρέφει τιμή που υποδεικνύει εάν θα απαγορευθεί η επεξεργασία ορισμού τύπου εγγράφου (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Επιστρέφει το XmlSchemaSet που θα χρησιμοποιηθεί κατά την επικύρωση σχήματος. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Επιστρέφει τιμή που υποδεικνύει τις ρυθμίσεις επικύρωσης σχήματος. Αυτή η ρύθμιση εφαρμόζεται σε αντικείμενα [XmlReader](../xmlreader/) που επικυρώνουν σχήματα (η τιμή [XmlReaderSettings::get_ValidationType](./get_validationtype/) είναι [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Επιστρέφει τιμή που υποδεικνύει εάν το [XmlReader](../xmlreader/) θα εκτελέσει επικύρωση ή ανάθεση τύπου κατά την ανάγνωση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [Reset](./reset/)() | Επαναφέρει τα μέλη της κλάσης ρυθμίσεων στις προεπιλεγμένες τιμές. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Ορίζει τιμή που υποδεικνύει εάν θα γίνει έλεγχος χαρακτήρων. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Ορίζει τιμή που υποδεικνύει εάν η υποκείμενη ροή ή το TextReader πρέπει να κλείσει όταν κλείνει ο αναγνώστης. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Ορίζει το επίπεδο συμμόρφωσης που θα τηρήσει το [XmlReader](../xmlreader/). |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Ορίζει τιμή που καθορίζει την επεξεργασία των DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Ορίζει τιμή που υποδεικνύει εάν θα αγνοηθούν τα σχόλια. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Ορίζει τιμή που υποδεικνύει εάν θα αγνοηθούν οι οδηγίες επεξεργασίας. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Ορίζει τιμή που υποδεικνύει εάν θα αγνοηθεί το ασήμαντο λευκό διάστημα. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Ορίζει τη μετατόπιση αριθμού γραμμής του αντικειμένου [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Ορίζει τη μετατόπιση θέσης γραμμής του αντικειμένου [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Ορίζει τιμή που υποδεικνύει το μέγιστο επιτρεπτό αριθμό χαρακτήρων σε ένα έγγραφο που προκύπτει από την επέκταση των οντοτήτων. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Ορίζει τιμή που υποδεικνύει το μέγιστο επιτρεπτό αριθμό χαρακτήρων σε ένα XML έγγραφο. Μια τιμή μηδέν (0) σημαίνει ότι δεν υπάρχουν όρια στο μέγεθος του XML εγγράφου. Μια μη μηδενική τιμή καθορίζει το μέγιστο μέγεθος, σε χαρακτήρες. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Ορίζει το [XmlNameTable](../xmlnametable/) που χρησιμοποιείται για ατομικές συγκρίσεις συμβολοσειρών. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Ορίζει τιμή που υποδεικνύει εάν θα απαγορευθεί η επεξεργασία ορισμού τύπου εγγράφου (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Ορίζει το XmlSchemaSet που θα χρησιμοποιηθεί κατά την επικύρωση σχήματος. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Ορίζει τιμή που υποδεικνύει τις ρυθμίσεις επικύρωσης σχήματος. Η ρύθμιση αυτή εφαρμόζεται σε αντικείμενα [XmlReader](../xmlreader/) που επικυρώνουν σχήματα (η τιμή [XmlReaderSettings::get_ValidationType](./get_validationtype/) είναι [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Ορίζει τιμή που υποδεικνύει εάν το [XmlReader](../xmlreader/) θα εκτελέσει επικύρωση ή ανάθεση τύπου κατά την ανάγνωση. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Ορίζει το [XmlResolver](../xmlresolver/) που χρησιμοποιείται για πρόσβαση σε εξωτερικά έγγραφα. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Προσθέτει έναν διαχειριστή συμβάντος που εκτελείται όταν ο αναγνώστης αντιμετωπίζει σφάλματα επικύρωσης. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Αφαιρεί έναν διαχειριστή συμβάντος που εκτελείται όταν ο αναγνώστης αντιμετωπίζει σφάλματα επικύρωσης. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τυποί ορισμών

| Typedef | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη προς μια παρουσία αυτής της κλάσης. |

## Παρατηρήσεις

Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσίες αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σε σφάλματα ελέγχου. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα. 

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)