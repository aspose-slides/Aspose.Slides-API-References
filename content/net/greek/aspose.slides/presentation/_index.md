---
title: Presentation
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια παρουσίαση Microsoft PowerPoint.
type: docs
weight: 9570
url: /el/aspose.slides/presentation/
---
## Presentation κλάση

Αντιπροσωπεύει μία παρουσίαση Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Presentation](presentation#constructor)() | Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή. Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή. Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια. |
| [Presentation](presentation#constructor_2)(Stream) | Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Παρουσίασης. |
| [Presentation](presentation#constructor_4)(string) | Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή του αρχείου προέλευσης από την οποία διαβάζονται τα περιεχόμενα της Παρουσίασης. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Παρουσίασης. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή του αρχείου προέλευσης από την οποία διαβάζονται τα περιεχόμενα της Παρουσίασης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Επιστρέφει όλα τα προσαρμοσμένα μέρη δεδομένων στην παρουσίαση. Μόνο ανάγνωση [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. Μόνο ανάγνωση [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Επιστρέφει τη συλλογή των συγγραφέων σχολίων. Μόνο ανάγνωση [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του αντικειμένου Presentation από προεπιλογή. Ανάγνωση/Εγγραφή DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. Μόνο ανάγνωση [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιούνται για την υπογραφή της παρουσίασης. Μόνο ανάγνωση [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. Μόνο ανάγνωση [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Επιστρέφει τον διαχειριστή γραμματοσειρών. Μόνο ανάγνωση [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Επιστρέφει τον τρέχοντα διαχειριστή Κεφαλίδας/Υποσέλιδου. Μόνο ανάγνωση [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση σε όλες τις υπερσυνδέσεις που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (όχι στις κύριες, διατάξεις, διαφάνειες σημειώσεων). Μόνο ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Μόνο ανάγνωση [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών διάταξης που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Επιστρέφει τον διαχειριστή κυρίως φυλλαδίου. Μόνο ανάγνωση [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Επιστρέφει τον διαχειριστή κυρίων σημειώσεων. Μόνο ανάγνωση [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Επιστρέφει μια λίστα όλων των κύριων διαφανειών που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Επιστρέφει το κύριο θέμα. Μόνο ανάγνωση [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων. Μόνο ανάγνωση [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Αποκτά τον διαχειριστή των δικαιωμάτων για αυτήν την παρουσίαση. Μόνο ανάγνωση [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Επιστρέφει μια λίστα όλων των ενοτήτων διαφανειών που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο της παρουσίασης. Μόνο ανάγνωση [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Επιστρέφει τις ρυθμίσεις προβολής διαφανειών για την παρουσίαση. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο ανάγνωση [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. Μόνο ανάγνωση [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Αποκτά ή ορίζει το έργο VBA με μακροεντολές παρουσίασης. Ανάγνωση/Εγγραφή [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο ανάγνωση [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Αποκτά τις ιδιότητες προβολής σε όλη την παρουσίαση. Μόνο ανάγνωση [`IViewProperties`](../iviewproperties). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Αποδεσμεύει όλους τους πόρους που χρησιμοποιεί αυτό το αντικείμενο Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Επιστρέφει αντικείμενα Image για όλες τις διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Επιστρέφει αντικείμενα Thumbnail Image για τις προσαρμοσμένες διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με το καθορισμένο μέγεθος. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Επιστρέφει αντικείμενα Thumbnail Image για τις προσαρμοσμένες διαφάνειες μιας παρουσίασης με το καθορισμένο μέγεθος. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Επιστρέφει αντικείμενα Thumbnail Image για τις προσαρμοσμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Επιστρέφει ένα Slide, MasterSlide ή LayoutSlide με βάση το Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Συνδέει τμήματα με το ίδιο μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο κείμενο. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με ένα άλλο καθορισμένο κείμενο. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν το σήμανση XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη καθορισμένη μορφή. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη καθορισμένη μορφή. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε μια παρουσίαση PowerPoint.

```csharp
[C#]
// Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation presentation = new Presentation())
{
    // Λαμβάνει την πρώτη διαφάνεια
    ISlide slide = presentation.Slides[0];
    // Προσθέτει αυτόματο σχήμα τύπου γραμμή
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Αποθηκεύει το αρχείο παρουσίασης.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να ανοίξετε και να αποθηκεύσετε μια Presentation.

```csharp
[C#]
// Φορτώνει οποιοδήποτε υποστηριζόμενο αρχείο στην Presentation, π.χ. ppt, pptx, odp κ.λπ.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Αποθηκεύει το αρχείο παρουσίασης.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διασύνδεση [IPresentation](../ipresentation)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συστατικό [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->