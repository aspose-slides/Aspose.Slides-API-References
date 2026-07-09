---
title: IDocumentProperties
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά ιδιότητες μιας παρουσίασης.
type: docs
weight: 5710
url: /el/aspose.slides/idocumentproperties/
---
## IDocumentProperties διασύνδεση

Αναπαριστά ιδιότητες μιας παρουσίασης.

```csharp
public interface IDocumentProperties
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. Ανάγνωση/εγγραφή String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Επιστρέφει την έκδοση της εφαρμογής. Μόνο-ανάγνωση String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Επιστρέφει ή ορίζει τον συγγραφέα μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. Ανάγνωση/εγγραφή String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιλαμβάνονται στην συλλογή. Μόνο-ανάγνωση Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Ανάγνωση/εγγραφή DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Δείχνει τον ομαδοποιημένο τρόπο των τμημάτων του εγγράφου και τον αριθμό των τμημάτων σε κάθε ομάδα. Μόνο-ανάγνωση IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Καθορίζει τον αριθμό των κρυμμένων διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο-ανάγνωση Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Επιστρέφει ή ορίζει την ιδιότητα HyperlinkBase του εγγράφου. Ανάγνωση/εγγραφή String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Καθορίζει ότι ένας ή περισσότεροι σύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις των συνδέσμων με τους νέους συνδέσμους που καθορίζονται σε αυτό το τμήμα. Ανάγνωση/εγγραφή Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που συσχετίζεται με ένα συγκεκριμένο όνομα. Ανάγνωση/εγγραφή Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Επιστρέφει την ημερομηνία που η παρουσίαση εκτυπώθηκε τελευταία φορά. Ανάγνωση/εγγραφή DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Ανάγνωση/εγγραφή String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Επιστρέφει την ημερομηνία που μια παρουσίαση τροποποιήθηκε τελευταία φορά. Οι τιμές είναι σε UTC. Μόνο-ανάγνωση στην περίπτωση Presentation.DocumentProperties (επειδή ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω του αντικειμένου DocumentProperties που επιστρέφεται από τη μέθοδο [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Δείτε το παράδειγμα στην περίληψη της μεθόδου [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Δείχνει εάν οι σύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Ορίστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι σύνδεσμοι είναι ενημερωμένοι. Ορίστε το σε **false** για να υποδείξετε ότι οι σύνδεσμοι είναι παλαιοί. Ανάγνωση/εγγραφή Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Επιστρέφει ή ορίζει την ιδιότητα manager. Ανάγνωση/εγγραφή String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Καθορίζει το συνολικό αριθμό των ήχων ή βίντεο κλιπ που περιέχονται στο έγγραφο. Μόνο-ανάγνωση Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. Ανάγνωση/εγγραφή String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Καθορίζει τον αριθμό των διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. Μόνο-ανάγνωση Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Καθορίζει το συνολικό αριθμό των παραγράφων που βρέθηκαν σε ένα έγγραφο, εάν εφαρμόζεται. Μόνο-ανάγνωση Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό έκδοσης της παρουσίασης. Ανάγνωση/εγγραφή Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Δείχνει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. Ορίστε το στοιχείο σε **true** για να ενεργοποιήσετε την κλιμάκωση της μικρογραφίας ώστε να ταιριάζει στην οθόνη. Ορίστε το σε **false** για να επιτρέψετε την περικοπή της μικρογραφίας ώστε να εμφανίζονται μόνο τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/εγγραφή Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Καθορίζει εάν η παρουσίαση μοιράζεται μεταξύ πολλών χρηστών. Ανάγνωση/εγγραφή Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Καθορίζει το συνολικό αριθμό των διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο-ανάγνωση Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. Ανάγνωση/εγγραφή String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. Αυτά τα τμήματα δεν είναι τμήματα εγγράφου αλλά εννοιολογικές αναπαραστάσεις ενοτήτων του εγγράφου. Μόνο-ανάγνωση string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Ανάγνωση/εγγραφή TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Καθορίζει το συνολικό αριθμό των λέξεων που περιέχονται σε ένα έγγραφο. Μόνο-ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις ενσωματωμένες ιδιότητες. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με συγκεκριμένο όνομα. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στη συγκεκριμένη θέση. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Αποκτά μια ονομαστική τιμή Boolean από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Αποκτά μια ονομαστική τιμή DateTime από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Αποκτά μια ονομαστική τιμή double από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Αποκτά μια ονομαστική τιμή float από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Αποκτά μια ονομαστική τιμή integer από τις προσαρμοσμένες ιδιότητες. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Αποκτά μια ονομαστική τιμή string από τις προσαρμοσμένες ιδιότητες. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Αποκτά έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Αφαιρεί μια προσαρμοσμένη ιδιότητα που συσχετίζεται με ένα συγκεκριμένο όνομα. |
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