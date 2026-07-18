---
title: XmlWriterSettings
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει ένα σύνολο λειτουργιών που υποστηρίζονται στο αντικείμενο XmlWriter που δημιουργείται από τη μέθοδο XmlWriter::Create."
type: docs
weight: 586
url: /el/system.xml/xmlwritersettings/
---
## XmlWriterSettings κλάση

Καθορίζει ένα σύνολο λειτουργιών που υποστηρίζονται στο αντικείμενο [XmlWriter](../xmlwriter/) που δημιουργείται από τη μέθοδο [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Δημιουργεί ένα αντίγραφο του αντικειμένου [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν ο XML writer πρέπει να ελέγχει ώστε όλοι οι χαρακτήρες στο έγγραφο να συμμορφώνονται με την ενότητα "2.2 Characters" του W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν το [XmlWriter](../xmlwriter/) πρέπει επίσης να κλείσει τη βασική ροή ή το TextWriter όταν κληθεί η μέθοδος [XmlWriter::Close](../xmlwriter/close/). |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Επιστρέφει το επίπεδο συμμόρφωσης που ελέγχει ο XML writer στην έξοδο XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν το [XmlWriter](../xmlwriter/) δεν διαφύγει τα χαρακτηριστικά URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Επιστρέφει τον τύπο κωδικοποίησης κειμένου που θα χρησιμοποιηθεί. |
| **bool** [get_Indent](./get_indent/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν θα πρέπει να εσοχές στα στοιχεία. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Επιστρέφει τη συμβολοσειρά χαρακτήρων που θα χρησιμοποιηθεί για εσοχή. Αυτή η ρύθμιση χρησιμοποιείται όταν η τιμή [XmlWriterSettings::set_Indent](./set_indent/) είναι **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν το [XmlWriter](../xmlwriter/) πρέπει να αφαιρέσει τις διπλές δηλώσεις χώρου ονομάτων κατά τη δημιουργία περιεχομένου XML. Η προεπιλεγμένη συμπεριφορά είναι ο writer να εξάγει όλες τις δηλώσεις χώρου ονομάτων που υπάρχουν στον επιλυτή χώρου ονομάτων του writer. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Επιστρέφει τη συμβολοσειρά χαρακτήρων που θα χρησιμοποιηθεί για αλλαγές γραμμής. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν θα πρέπει να κανονικοποιηθούν οι αλλαγές γραμμής στην έξοδο. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν θα γραφούν τα χαρακτηριστικά σε νέα γραμμή. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν θα παραλειφθεί η δήλωση XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Επιστρέφει τη μέθοδο που χρησιμοποιείται για την σειριοποίηση της εξόδου [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν το [XmlWriter](../xmlwriter/) θα προσθέσει ετικέτες κλεισίματος σε όλες τις ανοιχτές ετικέτες στοιχείων όταν κληθεί η μέθοδος [XmlWriter::Close](../xmlwriter/close/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της C# [Object.GetHashCode()](../../system/object/gethashcode/) μεθόδου. Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου εποπτείας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) μεθόδου. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με αναφορά προς nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [Reset](./reset/)() | Επαναφέρει τα μέλη της κλάσης ρυθμίσεων στις προεπιλεγμένες τιμές. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν ο XML writer πρέπει να ελέγχει ώστε όλοι οι χαρακτήρες στο έγγραφο να συμμορφώνονται με την ενότητα "2.2 Characters" του W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Ορίζει μια τιμή που υποδηλώνει εάν το [XmlWriter](../xmlwriter/) πρέπει επίσης να κλείσει την υποκείμενη ροή ή το TextWriter όταν κληθεί η μέθοδος [XmlWriter::Close](../xmlwriter/close/). |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Ορίζει το επίπεδο συμμόρφωσης για το οποίο ο XML writer ελέγχει την έξοδο XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν το [XmlWriter](../xmlwriter/) δεν διαφύγει τα χαρακτηριστικά URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Ορίζει τον τύπο κωδικοποίησης κειμένου που θα χρησιμοποιηθεί. |
| void [set_Indent](./set_indent/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν θα γίνει εσοχή των στοιχείων. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Ορίζει τη συμβολοσειρά χαρακτήρων που θα χρησιμοποιηθεί για εσοχή. Αυτή η ρύθμιση χρησιμοποιείται όταν η τιμή [XmlWriterSettings::set_Indent](./set_indent/) είναι **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Ορίζει μια τιμή που υποδεικνύει εάν το [XmlWriter](../xmlwriter/) πρέπει να αφαιρέσει τις διπλές δηλώσεις χώρου ονομάτων κατά τη δημιουργία περιεχομένου XML. Η προεπιλεγμένη συμπεριφορά είναι ο writer να εξάγει όλες τις δηλώσεις χώρου ονομάτων που υπάρχουν στον επιλυτή χώρου ονομάτων του writer. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Ορίζει τη συμβολοσειρά χαρακτήρων που θα χρησιμοποιηθεί για αλλαγές γραμμής. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Ορίζει μια τιμή που υποδεικνύει εάν θα πρέπει να κανονικοποιηθούν οι αλλαγές γραμμής στην έξοδο. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν θα γραφούν τα χαρακτηριστικά σε νέα γραμμή. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν θα παραλειφθεί η δήλωση XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν το [XmlWriter](../xmlwriter/) θα προσθέσει ετικέτες κλεισίματος σε όλες τις ανοιχτές ετικέτες στοιχείων όταν κληθεί η μέθοδος [XmlWriter::Close](../xmlwriter/close/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε περιεχόμενα σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της C# [Object.ToString()](../../system/object/tostring/) μεθόδου. Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δήλωση C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου εποπτείας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδυνατών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδυνατών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [XmlWriterSettings](./xmlwritersettings/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη προς μια παρουσία αυτής της κλάσης. |

## Σχόλια

Τα αντικείμενα αυτής της κλάσης θα πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσίες αυτού του τύπου στο στοίβο ή με τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή αποτυχίες ελέγχου. Πάντα περιβάλλετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα. 

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)