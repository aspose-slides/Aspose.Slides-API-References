---
title: IPresentation
second_title: Aspose.Sildes για .NET API Αναφορά
description: Έγγραφο παρουσίασης
type: docs
weight: 6750
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
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. Μόνο για ανάγνωση [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Επιστρέφει διεπαφή IDisposable. Μόνο για ανάγνωση IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. Μόνο για ανάγνωση [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Επιστρέφει τη συλλογή των σχολίων. Μόνο για ανάγνωση [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Επιστρέφει ή ορίζει ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Προεπιλογή: ώρα δημιουργίας αυτού του αντικειμένου Presentation. Ανάγνωση/εγγραφή DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. Μόνο για ανάγνωση [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιήθηκαν για την υπογραφή της παρουσίασης. Μόνο για ανάγνωση [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. Μόνο για ανάγνωση [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Εκπροσωπεί τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. Ανάγνωση/εγγραφή Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Επιστρέφει τον διαχειριστή γραμματοσειρών. Μόνο για ανάγνωση [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Επιστρέφει τον διαχειριστή HeaderFooter της παρουσίασης. Μόνο για ανάγνωση [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (όχι σε master, layout, notes). Μόνο για ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Μόνο για ανάγνωση [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών διάταξης που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Επιστρέφει τον διαχειριστή handout master. Μόνο για ανάγνωση [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Επιστρέφει τον διαχειριστή notes master. Μόνο για ανάγνωση [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Επιστρέφει μια λίστα όλων των master slides που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Επιστρέφει το master theme της παρουσίασης. Μόνο για ανάγνωση [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Επιστρέφει το αντικείμενο μεγέθους notes slide. Μόνο για ανάγνωση [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Λαμβάνει το διαχειριστή των δικαιωμάτων για αυτήν την παρουσίαση. Μόνο για ανάγνωση [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Επιστρέφει μια λίστα όλων των τμημάτων διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης. Μόνο για ανάγνωση [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Επιστρέφει μια λίστα όλων των διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο για ανάγνωση [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. Μόνο για ανάγνωση [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Λαμβάνει το έργο VBA με τα μακροεντολές της παρουσίασης. Ανάγνωση/εγγραφή [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο για ανάγνωση [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Λαμβάνει τις ιδιότητες προβολής ολόκληρης της παρουσίασης. Μόνο για ανάγνωση [`IViewProperties`](../iviewproperties). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Επιστρέφει αντικείμενα Thumbnail Bitmap για τις καθορισμένες διαφάνειες μιας παρουσίασης. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με το καθορισμένο μέγεθος. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με το καθορισμένο μέγεθος. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Επιστρέφει Slide, MasterSlide ή LayoutSlide κατά Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Επισημαίνει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Επισημαίνει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Ενώνει τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους όλων των αποδεκτών σχημάτων σε όλες τις διαφάνειες. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Αντικαθιστά όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο κείμενο. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή. |

### Δείτε επίσης

* διασύνδεση [IPresentationComponent](../ipresentationcomponent)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->