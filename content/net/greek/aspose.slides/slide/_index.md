---
title: Slide
second_title: Aspose.Sildes για .NET API Reference
description: Αντιπροσωπεύει μια διαφάνεια σε μια παρουσίαση.
type: docs
weight: 9940
url: /el/aspose.slides/slide/
---
## Slide κλάση

Αντιπροσωπεύει μια διαφάνεια σε μια παρουσίαση.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Επιστρέφει το παρασκήνιο της διαφάνειας. Μόνο ανάγνωση [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια. Μόνο ανάγνωση [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Επιστρέφει το διαχειριστή HeaderFooter της διαφάνειας. Μόνο ανάγνωση [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Καθορίζει αν η καθορισμένη διαφάνεια είναι κρυφή κατά τη διάρκεια παρουσίασης διαφάνειας. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση σε ενσωματωμένους υπερσυνδέσμους. Μόνο ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για τη τρέχουσα διαφάνεια. Ανάγνωση/εγγραφή [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/εγγραφή String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και αφαίρεση. Μόνο ανάγνωση [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Επιστρέφει τη διεπαφή IPresentation. Μόνο ανάγνωση [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Επιστρέφει τα σχήματα μιας διαφάνειας. Μόνο ανάγνωση [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Καθορίζει αν τα σχήματα στη κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Επιστρέφει το αναγνωριστικό μιας διαφάνειας. Μόνο ανάγνωση UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [`Slides`](../presentation/slides) είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/εγγραφή Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες για το πώς προχωρά η καθορισμένη διαφάνεια κατά τη διάρκεια παρουσίασης. Μόνο ανάγνωση [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Επιστρέφει τον διαχειριστή αναπροσαρμοζόμενου θέματος. Μόνο ανάγνωση [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Επιστρέφει το αντικείμενο χρονοδιαγράμματος animation. Μόνο ανάγνωση [`IAnimationTimeLine`](../ianimationtimeline). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Καθορίζει αν τα δύο αντικείμενα IBaseSlide είναι ίσα. Η τιμή επιστροφής υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, τα animation και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστών, π.χ. SlideId, καθώς και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στο Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Βρίσκει την πρώτη εμφάνιση σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Επιστρέφει ένα αντικείμενο Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Επιστρέφει ένα αντικείμενο Thumbnail tiff image με τις καθορισμένες παραμέτρους. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Επιστρέφει όλα τα σχόλια της διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Συμπτύσσει τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Συμπτύσσει τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [Remove](../../aspose.slides/slide/remove)() | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [Reset](../../aspose.slides/slide/reset)() | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στη LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [BaseSlide](../baseslide)
* διεπαφή [ISlide](../islide)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->