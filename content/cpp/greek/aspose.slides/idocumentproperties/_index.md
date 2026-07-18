---
title: IDocumentProperties
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά τις ιδιότητες μιας παρουσίασης.
type: docs
weight: 1977
url: /el/aspose.slides/idocumentproperties/
---
## IDocumentProperties κλάση

Αναπαριστά τις ιδιότητες μιας παρουσίασης.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις builtIn ιδιότητες. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Ελέγχει αν υπάρχει προσαρμοσμένη ιδιότητα με καθορισμένο όνομα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Επιστρέφει το πρότυπο μιας εφαρμογής. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Επιστρέφει την έκδοση της εφαρμογής. Μόνο για ανάγνωση [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Επιστρέφει τον δημιουργό μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Επιστρέφει την κατηγορία μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Επιστρέφει τα σχόλια μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Επιστρέφει την ιδιότητα εταιρείας. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Επιστρέφει την κατάσταση περιεχομένου μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Επιστρέφει τον τύπο περιεχομένου μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιέχονται στην συλλογή. Μόνο για ανάγνωση **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Διαβάστε [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Δηλώνει την ομαδοποίηση των τμημάτων εγγράφου και τον αριθμό τμημάτων σε κάθε ομάδα. Μόνο για ανάγνωση [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Καθορίζει τον αριθμό των κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο για ανάγνωση **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Επιστρέφει την ιδιότητα εγγράφου HyperlinkBase. Διαβάστε [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Καθορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσμων με τους νέους υπερσυνδέσμους που ορίζονται σε αυτό το τμήμα. Διαβάστε **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Επιστρέφει τις λέξεις-κλειδιά μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Επιστρέφει την ημερομηνία της τελευταίας εκτύπωσης μιας παρουσίασης. Διαβάστε [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Επιστρέφει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Διαβάστε [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC. Μόνο για ανάγνωση στην περίπτωση του Presentation.DocumentProperties (επειδή θα ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου [IPresentation](../ipresentation/)). Μπορεί να αλλάξει μέσω της παρουσίας [DocumentProperties](../documentproperties/) που επιστρέφεται από τη μέθοδο [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Δηλώνει αν οι υπερσύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Θέστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ενημερωμένοι. Θέστε το σε **false** για να υποδείξετε ότι είναι ξεπερασμένοι. Διαβάστε **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Επιστρέφει την ιδιότητα διαχειριστή. Διαβάστε [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Καθορίζει τον συνολικό αριθμό των ήχων ή βίντεο που υπάρχουν στο έγγραφο. Μόνο για ανάγνωση **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Επιστρέφει το όνομα της εφαρμογής. Διαβάστε [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Καθορίζει τον αριθμό των διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. Μόνο για ανάγνωση **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Καθορίζει τον συνολικό αριθμό των παραγράφων που βρέθηκαν σε ένα έγγραφο, εφόσον είναι εφαρμόσιμο. Μόνο για ανάγνωση **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Επιστρέφει την προοριζόμενη μορφή μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Επιστρέφει τον αριθμό αναθεώρησης της παρουσίασης. Διαβάστε **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Δηλώνει τη λειτουργία προβολής της μικρογραφίας του εγγράφου. Θέστε αυτό το στοιχείο σε **true** για να ενεργοποιήσετε την κλίμακα της μικρογραφίας ώστε να ταιριάζει στην οθόνη. Θέστε το σε **false** για να ενεργοποιήσετε την περικοπή της μικρογραφίας ώστε να εμφανίζονται μόνο τμήματα που ταιριάζουν στην οθόνη. Διαβάστε **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Καθορίζει αν η παρουσίαση είναι κοινή μεταξύ πολλών ατόμων. Διαβάστε **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Καθορίζει τον συνολικό αριθμό των διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο για ανάγνωση **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Επιστρέφει το θέμα μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Επιστρέφει τον τίτλο μιας παρουσίασης. Διαβάστε [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. Αυτά τα τμήματα δεν είναι τμήματα εγγράφου αλλά εννοιολογικές αναπαραστάσεις των ενοτήτων του εγγράφου. Μόνο για ανάγνωση [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Διαβάστε [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Καθορίζει τον συνολικό αριθμό των λέξεων που περιέχονται σε ένα έγγραφο. Μόνο για ανάγνωση **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στον καθορισμένο δείκτη. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Λαμβάνει μια ονομαστική λογική τιμή από τις προσαρμοσμένες ιδιότητες. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Λαμβάνει μια ονομαστική ακέραια τιμή από τις προσαρμοσμένες ιδιότητες. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Λαμβάνει μια ονομαστική τιμή DateTime από τις προσαρμοσμένες ιδιότητες. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Λαμβάνει μια ονομαστική τιμή συμβολοσειράς από τις προσαρμοσμένες ιδιότητες. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Λαμβάνει μια ονομαστική τιμή float από τις προσαρμοσμένες ιδιότητες. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Λαμβάνει μια ονομαστική τιμή double από τις προσαρμοσμένες ιδιότητες. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Λαμβάνει έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Επιστρέφει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα καθορισμένο όνομα. Διαβάστε [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα καθορισμένο όνομα. Γράψτε [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου όπως περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία υποκατηγοριών με αντιγραφή. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία υποκατηγοριών με αντιγραφή. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Αφαιρεί μια προσαρμοσμένη ιδιότητα που σχετίζεται με ένα καθορισμένο όνομα. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Ορίζει το πρότυπο μιας εφαρμογής. Γράψτε [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Ορίζει τον δημιουργό μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Ορίζει την κατηγορία μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Ορίζει τα σχόλια μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Ορίζει την ιδιότητα εταιρείας. Γράψτε [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Γράψτε [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Ορίζει την ιδιότητα εγγράφου HyperlinkBase. Γράψτε [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Καθορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσμων με τους νέους υπερσυνδέσμους που ορίζονται σε αυτό το τμήμα. Γράψτε **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Επιστρέφει την ημερομηνία της τελευταίας εκτύπωσης μιας παρουσίασης. Γράψτε [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Γράψτε [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC. Μόνο για ανάγνωση στην περίπτωση του Presentation.DocumentProperties (επειδή θα ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου [IPresentation](../ipresentation/)). Μπορεί να αλλάξει μέσω της παρουσίας [DocumentProperties](../documentproperties/) που επιστρέφεται από τη μέθοδο [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Δηλώνει αν οι υπερσύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Θέστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ενημερωμένοι. Θέστε το σε **false** για να υποδείξετε ότι είναι ξεπερασμένοι. Γράψτε **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Ορίζει την ιδιότητα διαχειριστή. Γράψτε [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Ορίζει το όνομα της εφαρμογής. Γράψτε [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Ορίζει την προοριζόμενη μορφή μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Ορίζει τον αριθμό αναθεώρησης της παρουσίασης. Γράψτε **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Δηλώνει τη λειτουργία προβολής της μικρογραφίας του εγγράφου. Θέστε αυτό το στοιχείο σε **true** για να ενεργοποιήσετε την κλίμακα της μικρογραφίας ώστε να ταιριάζει στην οθόνη. Θέστε το σε **false** για να ενεργοποιήσετε την περικοπή της μικρογραφίας ώστε να εμφανίζονται μόνο τμήματα που ταιριάζουν στην οθόνη. Γράψτε **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Καθορίζει αν η παρουσίαση είναι κοινή μεταξύ πολλών ατόμων. Γράψτε **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Ορίζει το θέμα μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Ορίζει τον τίτλο μιας παρουσίασης. Γράψτε [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Γράψτε [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Ορίζει μια ονομαστική λογική προσαρμοσμένη ιδιότητα. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Ορίζει μια ονομαστική ακέραια προσαρμοσμένη ιδιότητα. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Ορίζει μια ονομαστική τιμή DateTime προσαρμοσμένη ιδιότητα. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Ορίζει μια ονομαστική συμβολοσειρά προσαρμοσμένη ιδιότητα. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Ορίζει μια ονομαστική float προσαρμοσμένη ιδιότητα. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Ορίζει μια ονομαστική double προσαρμοσμένη ιδιότητα. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα πρότυπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)