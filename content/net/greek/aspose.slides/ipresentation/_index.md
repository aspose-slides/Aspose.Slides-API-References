---
title: IPresentation
second_title: Aspose.Sildes για .NET API Αναφορά
description: Έγγραφο παρουσίασης
type: docs
weight: 6730
url: /el/aspose.slides/ipresentation/
---
## IPresentation διεπαφή

Presentation document

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. Μόνο για ανάγνωση [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Επιστρέφει τη διεπαφή IDisposable. Μόνο για ανάγνωση IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Επιτρέπει την λήψη της βάσης διεπαφής IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. Μόνο για ανάγνωση [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Επιστρέφει τη συλλογή των συγγραφέων σχολίων. Μόνο για ανάγνωση [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του αντικειμένου Presentation από προεπιλογή. Ανάγνωση/εγγραφή DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. Μόνο για ανάγνωση [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Επιστρέφει τη συλλογή υπογραφών που χρησιμοποιούνται για την υπογραφή της παρουσίασης. Μόνο για ανάγνωση [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. Μόνο για ανάγνωση [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Αντιπροσωπεύει τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. Ανάγνωση/εγγραφή Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Επιστρέφει το διαχειριστή γραμματοσειρών. Μόνο για ανάγνωση [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Επιστρέφει το διαχειριστή HeaderFooter της παρουσίασης. Μόνο για ανάγνωση [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (εκτός master, layout, notes slides). Μόνο για ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Μόνο για ανάγνωση [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών διάταξης που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Επιστρέφει το διαχειριστή handout master. Μόνο για ανάγνωση [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Επιστρέφει το διαχειριστή notes master. Μόνο για ανάγνωση [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Επιστρέφει μια λίστα όλων των master διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Επιστρέφει το master theme της παρουσίασης. Μόνο για ανάγνωση [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων. Μόνο για ανάγνωση [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Λαμβάνει το διαχειριστή των αδειών για αυτήν την παρουσίαση. Μόνο για ανάγνωση [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Επιστρέφει μια λίστα όλων των τμημάτων διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Επιστρέφει τη συλλογή ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης. Μόνο για ανάγνωση [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο για ανάγνωση [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. Μόνο για ανάγνωση [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Λαμβάνει το πρότζεκτ VBA με μακροεντολές παρουσίασης. Ανάγνωση/εγγραφή [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο για ανάγνωση [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Λαμβάνει τις ιδιότητες προβολής για όλη την παρουσίαση. Μόνο για ανάγνωση [`IViewProperties`](../iviewproperties). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Επιστρέφει αντικείμενα Thumbnail Bitmap για τις καθορισμένες διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με το συγκεκριμένο μέγεθος. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με το συγκεκριμένο μέγεθος. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Επιστρέφει ένα Slide, MasterSlide ή LayoutSlide με βάση το Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Επισημαίνει όλα τα ταιρία της κανονικής έκφρασης με το συγκεκριμένο χρώμα. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Επισημαίνει όλα τα ταιρία του κειμένου δείγματος με το συγκεκριμένο χρώμα. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Επισημαίνει όλα τα ταιρία του κειμένου δείγματος με το συγκεκριμένο χρώμα. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Συνδέει τις ακολουθίες με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Αντικαθιστά όλα τα ταιρία της κανονικής έκφρασης με το συγκεκριμένο συμβολοσειρά. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Αντικαθιστά όλες τις εμφανίσεις του συγκεκριμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν το σήμανση XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή. |

### Δείτε επίσης

* διεπαφή [IPresentationComponent](../ipresentationcomponent)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->