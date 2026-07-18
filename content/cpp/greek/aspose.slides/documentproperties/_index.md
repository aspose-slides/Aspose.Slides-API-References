---
title: DocumentProperties
second_title: Aspose.Slides for C++ API Reference
description: Αντιπροσωπεί τις ιδιότητες μιας παρουσίασης.
type: docs
weight: 794
url: /el/aspose.slides/documentproperties/
---
## DocumentProperties κλάση

Αντιπροσωπεί τις ιδιότητες μιας παρουσίασης.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις builtIn ιδιότητες. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Αφαιρεί όλες τις custom ιδιότητες. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Κλωνοποιεί το τρέχον αντικείμενο |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Κλωνοποιεί το τρέχον αντικείμενο |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Ελέγχει την παρουσία μιας custom ιδιότητας με καθορισμένο όνομα. |
|  [DocumentProperties](./documentproperties/)() | Αρχικοποιεί νέα παρουσία της κλάσης [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Επιστρέφει το πρότυπο μιας εφαρμογής. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Επιστρέφει την έκδοση της εφαρμογής. Μόνο-ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Επιστρέφει τον δημιουργό μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Επιστρέφει την κατηγορία μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Επιστρέφει τα σχόλια μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Επιστρέφει την ιδιότητα εταιρείας. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Επιστρέφει την κατάσταση περιεχομένου μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Επιστρέφει τον τύπο περιεχομένου μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Επιστρέφει τον αριθμό των custom ιδιοτήτων που περιέχονται στην συλλογή. Μόνο-ανάγνωση **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Ανάγνωση [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Υποδεικνύει την ομαδοποίηση των τμημάτων του εγγράφου και τον αριθμό των τμημάτων σε κάθε ομάδα. Μόνο-ανάγνωση [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Επιστρέφει τον αριθμό των κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο-ανάγνωση **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Επιστρέφει την ιδιότητα HyperlinkBase του εγγράφου. Ανάγνωση [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Καθορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσμων με τους νέους υπερσυνδέσμους που καθορίζονται σε αυτό το τμήμα. Ανάγνωση **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Επιστρέφει τις λέξεις-κλειδιά μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Επιστρέφει την ημερομηνία κατά την οποία η παρουσίαση εκτυπώθηκε τελευταία φορά. Ανάγνωση [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Επιστρέφει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Ανάγνωση [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC. Μόνο-ανάγνωση σε περίπτωση του [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (επειδή θα ενημερωθεί εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου [IPresentation](../ipresentation/)). Μπορεί να τροποποιηθεί μέσω της παρουσίας [DocumentProperties](./) που επιστρέφεται από τη μέθοδο [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Δείχνει αν οι υπερσύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Ορίστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ενημερωμένοι. Ορίστε το σε **false** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ξεπερασμένοι. Ανάγνωση **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Επιστρέφει την ιδιότητα διαχειριστή. Ανάγνωση [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Επιστρέφει τον συνολικό αριθμό ηχητικών ή βιντεοκομματιών που υπάρχουν στο έγγραφο. Μόνο-ανάγνωση **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Επιστρέφει το όνομα της εφαρμογής. Ανάγνωση [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Επιστρέφει τον αριθμό των διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. Μόνο-ανάγνωση **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Επιστρέφει τον συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο εάν ισχύει. Μόνο-ανάγνωση **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Επιστρέφει τη προγραμματισμένη μορφή μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Επιστρέφει τον αριθμό αναθεώρησης της παρουσίασης. Ανάγνωση **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Δείχνει τη λειτουργία προβολής της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για να ενεργοποιήσετε την κλιμάκωση της μικρογραφίας του εγγράφου στην οθόνη. Ορίστε το σε **false** για να επιτρέψετε την περικοπή της μικρογραφίας ώστε να δείχνει μόνο τμήματα που ταιριάζουν στην οθόνη. Εγγραφή **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Καθορίζει αν η παρουσίαση μοιράζεται μεταξύ πολλών ατόμων. Ανάγνωση **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Επιστρέφει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο-ανάγνωση **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Επιστρέφει το θέμα μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Επιστρέφει τον τίτλο μιας παρουσίασης. Ανάγνωση [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. Αυτά τα τμήματα δεν είναι τμήματα εγγράφου αλλά εννοιολογικές αναπαραστάσεις των ενοτήτων του εγγράφου. Μόνο-ανάγνωση [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Ανάγνωση [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Επιστρέφει τον συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. Μόνο-ανάγνωση **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Επιστρέφει ένα όνομα προσαρμοσμένης ιδιότητας στο καθορισμένο δείκτη. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Λαμβάνει μια ονομαστική λογική τιμή από τις προσαρμοσμένες ιδιότητες. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Λαμβάνει μια ονομαστική ακέραια τιμή από τις προσαρμοσμένες ιδιότητες. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Λαμβάνει μια ονομαστική τιμή DateTime από τις προσαρμοσμένες ιδιότητες. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Λαμβάνει μια ονομαστική τιμή συμβολοσειράς από τις προσαρμοσμένες ιδιότητες. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Λαμβάνει μια ονομαστική τιμή float από τις προσαρμοσμένες ιδιότητες. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Λαμβάνει μια ονομαστική τιμή double από τις προσαρμοσμένες ιδιότητες. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Λαμβάνει έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Επιστρέφει την προσαρμοσμένη ιδιότητα που συσχετίζεται με ένα καθορισμένο όνομα. Ανάγνωση [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Ορίζει την προσαρμοσμένη ιδιότητα που συσχετίζεται με ένα καθορισμένο όνομα. Εγγραφή [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αποτελεί υπόδειγμα τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, απλά αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει κάτι, απλά αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική προσαρμογή του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική προσαρμογή του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειρών. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Αφαιρεί μια προσαρμοσμένη ιδιότητα που συσχετίζεται με ένα καθορισμένο όνομα. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Ορίζει το πρότυπο μιας εφαρμογής. Εγγραφή [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Ορίζει τον δημιουργό μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Ορίζει την κατηγορία μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Ορίζει τα σχόλια μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Ορίζει την ιδιότητα εταιρείας. Εγγραφή [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Εγγραφή [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Ορίζει την ιδιότητα HyperlinkBase του εγγράφου. Εγγραφή [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Καθορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσμων με τους νέους υπερσυνδέσμους που καθορίζονται σε αυτό το τμήμα. Εγγραφή **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Επιστρέφει την ημερομηνία τελευταίας εκτύπωσης μιας παρουσίασης. Εγγραφή [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Εγγραφή [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC. Μόνο-ανάγνωση σε περίπτωση του [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (επειδή θα ενημερωθεί εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου [IPresentation](../ipresentation/)). Μπορεί να τροποποιηθεί μέσω της παρουσίας [DocumentProperties](./) που επιστρέφεται από τη μέθοδο [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Δείχνει αν οι υπερσύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Ορίστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ενημερωμένοι. Ορίστε το σε **false** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ξεπερασμένοι. Εγγραφή **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Ορίζει την ιδιότητα διαχειριστή. Εγγραφή [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Ορίζει το όνομα της εφαρμογής. Εγγραφή [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Ορίζει τη προγραμματισμένη μορφή μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Ορίζει τον αριθμό αναθεώρησης της παρουσίασης. Εγγραφή **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Δείχνει τη λειτουργία προβολής της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για να ενεργοποιήσετε την κλιμάκωση της μικρογραφίας του εγγράφου στην οθόνη. Ορίστε το σε **false** για να επιτρέψετε την περικοπή της μικρογραφίας ώστε να δείχνει μόνο τμήματα που ταιριάζουν στην οθόνη. Εγγραφή **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Καθορίζει αν η παρουσίαση μοιράζεται μεταξύ πολλών ατόμων. Εγγραφή **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Ορίζει το θέμα μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Ορίζει τον τίτλο μιας παρουσίασης. Εγγραφή [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Εγγραφή [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Ορίζει μια ονομαστική λογική προσαρμοσμένη ιδιότητα. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Ορίζει μια ονομαστική ακέραια προσαρμοσμένη ιδιότητα. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Ορίζει μια ονομαστική προσαρμοσμένη ιδιότητα DateTime. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Ορίζει μια ονομαστική προσαρμοσμένη ιδιότητα συμβολοσειράς. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Ορίζει μια ονομαστική προσαρμοσμένη ιδιότητα float. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Ορίζει μια ονομαστική προσαρμοσμένη ιδιότητα double. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυναμία δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυναμία λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδυναμής αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδυναμής αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσπελάσετε τις ενσωματωμένες Ιδιότητες του PowerPoint [Presentation](../presentation/). 
```cpp
// Δημιουργία της κλάσης Presentation που αντιπροσωπεύει την παρουσίαση
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
 Το παρακάτω παράδειγμα δείχνει πώς να τροποποιήσετε τις ενσωματωμένες Ιδιότητες του PowerPoint [Presentation](../presentation/). 
```cpp
// Δημιουργία της κλάσης Presentation που αντιπροσωπεύει την Presentation
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Δημιουργία αναφοράς σε αντικείμενο IDocumentProperties που σχετίζεται με την Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Ορισμός των ενσωματωμένων ιδιοτήτων
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Αποθήκευση της παρουσίασης σε αρχείο
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IDocumentProperties](../idocumentproperties/)
* Κλάση [IGenericCloneable](../igenericcloneable/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)