---
title: XmlWriter
second_title: Aspose.Slides για το API C++
description: Αναπαριστά έναν συγγραφέα που παρέχει έναν γρήγορο, μη προσωρινής αποθήκευσης, μόνο-προς-μπροστά τρόπο για τη δημιουργία ροών ή αρχείων που περιέχουν δεδομένα XML.
type: docs
weight: 573
url: /el/system.xml/xmlwriter/
---
## XmlWriter κατηγορία

Αναπαριστά έναν συγγραφέα που παρέχει έναν γρήγορο, μη κρυμμένο, μόνο-προς-μπροστά τρόπο για τη δημιουργία ροών ή αρχείων που περιέχουν δεδομένα XML.

```cpp
class XmlWriter : public System::IDisposable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [Close](./close/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, κλείνει αυτή τη ροή και την υποκείμενη ροή. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας το καθορισμένο όνομα αρχείου. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας το όνομα αρχείου και το αντικείμενο [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας τη καθορισμένη ροή. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας τη ροή και το αντικείμενο [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας τον καθορισμένο TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας το TextWriter και τα αντικείμενα [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας το καθορισμένο [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας τα αντικείμενα [Text::StringBuilder](../../system.text/stringbuilder/) και [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας το καθορισμένο αντικείμενο [XmlWriter](./). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Δημιουργεί ένα νέο αντικείμενο [XmlWriter](./) χρησιμοποιώντας τα καθορισμένα αντικείμενα [XmlWriter](./) και [XmlWriterSettings](../xmlwritersettings/). |
| void [Dispose](./dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί η τρέχουσα παρουσία της κλάσης [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual void [Flush](./flush/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, εκκενώνει ό,τι υπάρχει στην ενδιάμεση μνήμη προς τις υποκείμενες ροές και επίσης εκκενώνει την υποκείμενη ροή. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Επιστρέφει το αντικείμενο [XmlWriterSettings](../xmlwritersettings/) που χρησιμοποιήθηκε για τη δημιουργία της παρουσίασης [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, λαμβάνει την κατάσταση του συγγραφέα. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, λαμβάνει το τρέχον πεδίο **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, λαμβάνει ένα XmlSpace που αντιπροσωπεύει το τρέχον πεδίο **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσίαση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλειδώση της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, επιστρέφει το πλησιέστερο προαλλαγή που ορίζεται στο τρέχον πεδίο ονομάτων για το URI του χώρου ονομάτων. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεσ/operator ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση του string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα του προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει όλα τα χαρακτηριστικά που βρέθηκαν στην τρέχουσα θέση στο [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει ένα χαρακτηριστικό με το καθορισμένο τοπικό όνομα, το URI του ονοματοχώρου και την τιμή. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το χαρακτηριστικό με το καθορισμένο τοπικό όνομα και τιμή. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το χαρακτηριστικό με το καθορισμένο προαλλάγος, τοπικό όνομα, URI ονοματοχώρου και τιμή. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, κωδικοποιεί τα καθορισμένα δυαδικά byte ως Base64 και γράφει το προκύπτον κείμενο. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, κωδικοποιεί τα καθορισμένα δυαδικά byte ως **BinHex** και γράφει το προκύπτον κείμενο. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει ένα τμήμα **...** που περιέχει το καθορισμένο κείμενο. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, εξαναγκάζει τη δημιουργία μιας οντότητας χαρακτήρα για την καθορισμένη τιμή Unicode χαρακτήρα. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει κείμενο ένα buffer τη φορά. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει ένα σχόλιο **** που περιέχει το καθορισμένο κείμενο. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει τη δήλωση DOCTYPE με το καθορισμένο όνομα και προαιρετικά χαρακτηριστικά. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Γράφει ένα στοιχείο με το καθορισμένο τοπικό όνομα και τιμή. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Γράφει ένα στοιχείο με το καθορισμένο τοπικό όνομα, URI του ονοματοχώρου και τιμή. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Γράφει ένα στοιχείο με το καθορισμένο προαλλάγος, τοπικό όνομα, URI του ονοματοχώρου και τιμή. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, κλείνει την προηγούμενη κλήση XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, κλείνει τυχόν ανοιχτά στοιχεία ή χαρακτηριστικά και επαναφέρει το συγγραφέα στην κατάσταση Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, κλείνει ένα στοιχείο και αφαιρεί το αντίστοιχο πεδίο ονομάτων. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλήση, γράφει μια αναφορά οντότητας ως **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, κλείνει ένα στοιχείο και αφαιρίζει το αντίστοιχο πεδίο ονομάτων. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το καθορισμένο όνομα, διασφαλίζοντας ότι είναι έγκυρο όνομα σύμφωνα με τη σύσταση W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωμη κλάση, γράφει το καθορισμένο όνομα, διασφαλίζοντας ότι είναι έγκυρο NmToken σύμφωνα με τη σύσταση W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, αντιγράφει όλα από τον αναγνώστη στον συγγραφέα και μετακινεί τον αναγνώστη στην αρχή του επόμενου αδελφού. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Αντιγράφει όλα από το αντικείμενο XPathNavigator στον συγγραφέα. Η θέση του XPathNavigator παραμένει αμετάβλητη. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει μια οδηγία επεξεργασίας με κενό μεταξύ του ονόματος και του κειμένου ως εξής: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το όνομα με προθήκη ονοματοχώρου. Αυτή η μέθοδος αναζητά το προαλλάγος που ισχύει για το δεδομένο χώρο ονομάτων. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει ακατέργαστο markup χειροκίνητα από μία ενδιάμεση μνήμη χαρακτήρων. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει ακατέργαστο markup χειροκίνητα από μια συμβολοσειρά. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Γράφει την αρχή ενός χαρακτηριστικού με το καθορισμένο τοπικό όνομα και URI ονοματοχώρου. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει την αρχή ενός χαρακτηριστικού με το καθορισμένο προαλλάγος, τοπικό όνομα και URI ονοματοχώρου. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Γράφει την αρχή ενός χαρακτηριστικού με το καθορισμένο τοπικό όνομα. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει τη δήλωση XML με την έκδοση "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει τη δήλωση XML με την έκδοση "1.0" και το χαρακτηριστικό standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το καθορισμένο ετικέτα εκκίνησης και το συνδέει με το δεδομένο χώρο ονομάτων. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το καθορισμένο ετικέτα εκκίνησης και το συνδέει με τον δεδομένο χώρο ονομάτων και προαλλάγος. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει μια ετικέτα εκκίνησης με το καθορισμένο τοπικό όνομα. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το δεδομένο περιεχόμενο κειμένου. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, δημιουργεί και γράφει την οντότητα χαρακτήρα υποκατάστασης για το ζεύγος χαρακτήρων υποκατάστασης. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Γράφει την τιμή του αντικειμένου. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Γράφει μια τιμή [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Γράφει μια τιμή [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Γράφει μια τιμή [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Γράφει μια τιμή [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Γράφει μια τιμή [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Γράφει έναν αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Γράφει μια τιμή [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Γράφει μια τιμή [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Γράφει μια τιμή [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Όταν αντικατασταθεί σε μια παράγωγη κλάση, γράφει το δεδομένο λευκό διάστημα. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Τύπος | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη προς μια παρουσίαση αυτής της κλάσης. |

## Δείτε επίσης

* Κατηγορία [IDisposable](../../system/idisposable/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)