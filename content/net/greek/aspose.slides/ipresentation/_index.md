---
title: IPresentation
second_title: Αναφορά API Aspose.Sildes για .NET
description: Έγγραφο παρουσίασης
type: docs
weight: 6770
url: /el/aspose.slides/ipresentation/
---
## IPresentation διασύνδεση

Έγγραφο παρουσίασης

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. Μόνο ανάγνωση [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Επιστρέφει τη διασύνδεση IDisposable. Μόνο ανάγνωση IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Επιτρέπει την λήψη της βασικής διασύνδεσης IPresentationComponent. Μόνο ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. Μόνο ανάγνωση [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Επιστρέφει τη συλλογή των συγγραφέων σχολίων. Μόνο ανάγνωση [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του αντικειμένου Presentation εξ ορισμού. Ανάγνωση/εγγραφή DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. Μόνο ανάγνωση [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιούνται για την υπογραφή της παρουσίασης. Μόνο ανάγνωση [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. Μόνο ανάγνωση [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Απεικονίζει τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. Ανάγνωση/εγγραφή Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Επιστρέφει τον διαχειριστή γραμματοσειρών. Μόνο ανάγνωση [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Επιστρέφει τον διαχειριστή HeaderFooter της παρουσίασης. Μόνο ανάγνωση [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (όχι σε master, layout, notes). Μόνο ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Μόνο ανάγνωση [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών διάταξης που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Επιστρέφει τον διαχειριστή handout master. Μόνο ανάγνωση [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Επιστρέφει τον διαχειριστή notes master. Μόνο ανάγνωση [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Επιστρέφει μια λίστα όλων των master διαφανειών που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Επιστρέφει το master θέμα της παρουσίασης. Μόνο ανάγνωση [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Επιστρέφει το αντικείμενο μεγέθους σημειώσεων διαφάνειας. Μόνο ανάγνωση [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Λαμβάνει τον διαχειριστή των αδειών για αυτήν την παρουσίαση. Μόνο ανάγνωση [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Επιστρέφει μια λίστα όλων των τμημάτων διαφανειών που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης. Μόνο ανάγνωση [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών που ορίζονται στην παρουσίαση. Μόνο ανάγνωση [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο ανάγνωση [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. Μόνο ανάγνωση [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Λαμβάνει το έργο VBA με τα μακροεντολές της παρουσίασης. Ανάγνωση/εγγραφή [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο ανάγνωση [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Λαμβάνει τις ιδιότητες προβολής όλης της παρουσίασης. Μόνο ανάγνωση [`IViewProperties`](../iviewproperties). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Επιστρέφει αντικείμενα Thumbnail Bitmap για τις καθορισμένες διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με το καθορισμένο μέγεθος. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με το καθορισμένο μέγεθος. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Επιστρέφει ένα Slide, MasterSlide ή LayoutSlide με βάση το Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Επισημαίνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Επισημαίνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Συνδέει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | Επαναφορτώνει τα δεδομένα για όλα τα διαγράμματα στην παρουσίαση από τα πηγαία φύλλα εργασίας τους. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο κείμενο. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με ένα άλλο καθορισμένο κείμενο. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν την σημειογραφία XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε μια ροή με τη καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη καθορισμένη μορφή. |

### Δείτε επίσης

* διασύνδεση [IPresentationComponent](../ipresentationcomponent)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->