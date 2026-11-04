---
title: IDocumentProperties
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά τις ιδιότητες μιας παρουσίασης.
type: docs
weight: 5730
url: /el/aspose.slides/idocumentproperties/
---
## IDocumentProperties διασύνδεση

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Ιδιότητες

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. Ανάγνωση/Εγγραφή String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Επιστρέφει την έκδοση της εφαρμογής. Μόνο για ανάγνωση String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Επιστρέφει ή ορίζει τον συγγραφέα μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. Ανάγνωση/Εγγραφή String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιέχονται στη συλλογή. Μόνο για ανάγνωση Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Ανάγνωση/Εγγραφή DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Δείχνει την ομαδοποίηση των τμημάτων του εγγράφου και τον αριθμό των τμημάτων σε κάθε ομάδα. Μόνο για ανάγνωση IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Καθορίζει τον αριθμό των κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο για ανάγνωση Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. Ανάγνωση/Εγγραφή String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Καθορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσμων με τους νέους υπερσυνδέσμους που καθορίζονται σε αυτό το τμήμα. Ανάγνωση/Εγγραφή Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που συνδέεται με ένα συγκεκριμένο όνομα. Ανάγνωση/Εγγραφή Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Επιστρέφει την ημερομηνία που η παρουσίαση εκτυπώθηκε τελευταία φορά. Ανάγνωση/Εγγραφή DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Ανάγνωση/Εγγραφή String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC. Μόνο για ανάγνωση σε περίπτωση Presentation.DocumentProperties (επειδή ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω της παρουσίας DocumentProperties που επιστρέφεται από τη μέθοδο [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Δείτε το παράδειγμα στη σύνοψη μεθόδου [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Δείχνει αν οι υπερσύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Ορίστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ενημερωμένοι. Ορίστε αυτό το στοιχείο σε **false** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι παρωχημένοι. Ανάγνωση/Εγγραφή Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Επιστρέφει ή ορίζει την ιδιότητα manager. Ανάγνωση/Εγγραφή String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Καθορίζει τον συνολικό αριθμό των ηχητικών ή βίντεο κλιπ που υπάρχουν στο έγγραφο. Μόνο για ανάγνωση Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. Ανάγνωση/Εγγραφή String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Καθορίζει τον αριθμό των διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. Μόνο για ανάγνωση Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Καθορίζει τον συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο, εάν είναι εφαρμόσιμο. Μόνο για ανάγνωση Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Επιστρέφει ή ορίζει τη μορφή που προορίζεται για μια παρουσίαση. Ανάγνωση/Εγγραφή String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. Ανάγνωση/Εγγραφή Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Δείχνει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για να ενεργοποιήσετε την κλιμάκωση της μικρογραφίας του εγγράφου στην οθόνη. Ορίστε αυτό το στοιχείο σε **false** για να ενεργοποιήσετε την περικοπή της μικρογραφίας του εγγράφου ώστε να εμφανίζονται μόνο τα τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/Εγγραφή Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Καθορίζει αν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών ατόμων. Ανάγνωση/Εγγραφή Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Καθορίζει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο για ανάγνωση Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. Ανάγνωση/Εγγραφή String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. Αυτά τα τμήματα δεν είναι τμήματα εγγράφου αλλά εννοιολογικές αναπαραστάσεις των ενοτήτων του εγγράφου. Μόνο για ανάγνωση string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Ανάγνωση/Εγγραφή TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Καθορίζει τον συνολικό αριθμό λέξων που περιέχονται σε ένα έγγραφο. Μόνο για ανάγνωση Int32. |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Απαλείφει και ορίζει τιμές προεπιλογής για όλες τις ενσωματωμένες ιδιότητες. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με συγκεκριμένο όνομα. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στη συγκεκριμένη θέση. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Αποκτά μια ονομαστική τιμή boolean από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Αποκτά μια ονομαστική τιμή DateTime από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Αποκτά μια ονομαστική τιμή double από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Αποκτά μια ονομαστική τιμή float από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Αποκτά μια ονομαστική τιμή integer από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Αποκτά μια ονομαστική τιμή string από τις προσαρμοσμένες ιδιότητες. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Αποκτά έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Αφαιρεί μια προσαρμοσμένη ιδιότητα που συνδέεται με ένα συγκεκριμένο όνομα. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Ορίζει μια ονομαστική boolean προσαρμοσμένη ιδιότητα. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Ορίζει μια ονομαστική DateTime προσαρμοσμένη ιδιότητα. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Ορίζει μια ονομαστική double προσαρμοσμένη ιδιότητα. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Ορίζει μια ονομαστική float προσαρμοσμένη ιδιότητα. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Ορίζει μια ονομαστική integer προσαρμοσμένη ιδιότητα. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Ορίζει μια ονομαστική string προσαρμοσμένη ιδιότητα. |

### Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->