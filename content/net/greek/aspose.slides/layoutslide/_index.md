---
title: LayoutSlide
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αναπαριστά μια διαφάνεια διάταξης.
type: docs
weight: 7620
url: /el/aspose.slides/layoutslide/
---
## LayoutSlide κλάση

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Επιστρέφει το φόντο της διαφάνειας. Μόνο ανάγνωση [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια. Μόνο ανάγνωση [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια διάταξης. Μόνο ανάγνωση [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Επιστρέφει true εάν υπάρχει τουλάχιστον μια διαφάνεια που εξαρτάται από αυτή τη διαφάνεια διάταξης. Μόνο ανάγνωση Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Επιστρέφει το διαχειριστή HeaderFooter της διαφάνειας διάταξης. Μόνο ανάγνωση [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. Μόνο ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Επιστρέφει τον τύπο διάταξης αυτής της διαφάνειας διάταξης. Μόνο ανάγνωση [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Επιστρέφει ή ορίζει τη κύρια διαφάνεια για μια διάταξη. Ανάγνωση/Εγγραφή [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/Εγγραφή String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Επιστρέφει το διαχειριστή placeholders της διαφάνειας διάταξης. Μόνο ανάγνωση [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Επιστρέφει τη διεπαφή IPresentation. Μόνο ανάγνωση [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Επιστρέφει τα σχήματα μιας διαφάνειας. Μόνο ανάγνωση [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Καθορίζει εάν τα σχήματα στη κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/Εγγραφή Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Επιστρέφει το αναγνωριστικό (ID) μιας διαφάνειας. Μόνο ανάγνωση UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες για το πώς προχωρά η συγκεκριμένη διαφάνεια κατά τη διάρκεια παρουσίασης. Μόνο ανάγνωση [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Επιστρέφει το διαχειριστή του υπερκαλύπτοντος θέματος. Μόνο ανάγνωση [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Επιστρέφει το αντικείμενο animation timeline. Μόνο ανάγνωση [`IAnimationTimeLine`](../ianimationtimeline). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Καθορίζει εάν τα δύο στιγμιότυπα IBaseSlide είναι ίσα. Η τιμή επιστροφής υπολογίζεται με βάση τη δομή της διαφάνειας και το στατικό περιεχόμενο. Δύο διαφάνειες είναι ίσες αν όλα τα σχήματα, τα στυλ, τα κείμενα, οι κινούμενες εικόνες και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστικών, π.χ. SlideId, και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στο Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτή τη διαφάνεια διάταξης. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Συγχωνεύει τμήματα με την ίδια μορφοποίηση σε όλα τα παραγράφια όλων των αποδεκτών σχημάτων. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Συγχωνεύει τμήματα με την ίδια μορφοποίηση σε όλα τα παραγράφια σε όλα τα αποδεκτά σχήματα. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Αφαιρεί τη διάταξη από την παρουσίαση. |

### Δείτε επίσης

* κλάση [BaseSlide](../baseslide)
* διασύνδεση [ILayoutSlide](../ilayoutslide)
* χωροσυνολο [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->