---
title: Slide
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει μια διαφάνεια σε μια παρουσίαση.
type: docs
weight: 9980
url: /el/aspose.slides/slide/
---
## Slide κλάση

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Επιστρέφει το παρασκήνιο της διαφάνειας. Μόνο για ανάγνωση [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια. Μόνο για ανάγνωση [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. Μόνο για ανάγνωση [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. Ανάγνωση/Εγγραφή Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. Μόνο για ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. Ανάγνωση/Εγγραφή [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/Εγγραφή String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Επιτρέπει την πρόσβαση στη σημείωση διαφάνειας, την προσθήκη και την αφαίρεση. Μόνο για ανάγνωση [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Επιστρέφει τη διεπαφή IPresentation. Μόνο για ανάγνωση [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Επιστρέφει τα σχήματα μιας διαφάνειας. Μόνο για ανάγνωση [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Καθορίζει αν τα σχήματα στην κύρια διαφάνεια θα εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/Εγγραφή Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Επιστρέφει το ID μιας διαφάνειας. Μόνο για ανάγνωση UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [`Slides`](../presentation/slides) είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/Εγγραφή Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες για το πώς προχωρά η συγκεκριμένη διαφάνεια κατά τη διάρκεια της παρουσίασης. Μόνο για ανάγνωση [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Επιστρέφει τον διαχειριστή υπερκάλυψης θέματος. Μόνο για ανάγνωση [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Επιστρέφει το αντικείμενο χρονογράφου κίνησης. Μόνο για ανάγνωση [`IAnimationTimeLine`](../ianimationtimeline). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Καθορίζει αν τα δύο στιγμιότυπα IBaseSlide είναι ίσα. Η επιστρεφόμενη τιμή υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου. Δύο διαφάνειες είναι ίσες αν όλα τα σχήματα, τα στυλ, τα κείμενα, η κίνηση και άλλες ρυθμίσεις κλπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις τιμές μοναδικών ταυτοποιητών, π.χ. SlideId, και το δυναμικό περιεχόμενο, π.χ. τρέχουσα τιμή ημερομηνίας στο Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Επιστρέφει ένα αντικείμενο Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Επιστρέφει ένα αντικείμενο εικόνας Thumbnail tiff με τα καθορισμένα παραμέτρους. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλίμακα. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλίμαση. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Συνενώνει τα runs με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Συνενώνει τα runs με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [Remove](../../aspose.slides/slide/remove)() | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [Reset](../../aspose.slides/slide/reset)() | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στη LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [BaseSlide](../baseslide)
* διασύνδεση [ISlide](../islide)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->