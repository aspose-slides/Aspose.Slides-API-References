---
title: LayoutSlide
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αναπαριστά μια διαφάνεια διάταξης.
type: docs
weight: 7640
url: /el/aspose.slides/layoutslide/
---
## LayoutSlide κλάση

Αναπαριστά μια διαφάνεια διάταξης.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Επιστρέφει το παρασκήνιο της διαφάνειας. Μόνο για ανάγνωση [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια. Μόνο για ανάγνωση [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Επιστρέφει μια συλλογή οδηγών σχεδίασης για τη διαφάνεια διάταξης. Μόνο για ανάγνωση [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτή τη διαφάνεια διάταξης. Μόνο για ανάγνωση Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας διάταξης. Μόνο για ανάγνωση [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση στους περιέχοντες υπερσυνδέσμους. Μόνο για ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Επιστρέφει τον τύπο διάταξης αυτής της διαφάνειας διάταξης. Μόνο για ανάγνωση [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Επιστρέφει ή ορίζει τη διαφάνεια master για μια διάταξη. Ανάγνωση/εγγραφή [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/εγγραφή String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Επιστρέφει τον διαχειριστή placeholder της διαφάνειας διάταξης. Μόνο για ανάγνωση [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Επιστρέφει τη διεπαφή IPresentation. Μόνο για ανάγνωση [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Επιστρέφει τα σχήματα μιας διαφάνειας. Μόνο για ανάγνωση [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Καθορίζει εάν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Επιστρέφει το ID μιας διαφάνειας. Μόνο για ανάγνωση UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες για το πώς προχωρά η συγκεκριμένη διαφάνεια κατά τη διάρκεια της παρουσίασης. Μόνο για ανάγνωση [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Επιστρέφει τον διαχειριστή του υπερκαθοριζόμενου θέματος. Μόνο για ανάγνωση [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Επιστρέφει το αντικείμενο animation timeline. Μόνο για ανάγνωση [`IAnimationTimeLine`](../ianimationtimeline). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Καθορίζει εάν τα δύο στιγμιότυπα IBaseSlide είναι ίσα. Η επιστρεφόμενη τιμή υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, στυλ, κείμενα, animation και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές ταυτοποίησης, π.χ. SlideId, και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στο Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτή τη διαφάνεια διάταξης. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Συνενώνει runs με την ίδια μορφοποίηση σε όλες τις παραγράφους όλων των αποδεκτών σχημάτων. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Συνενώνει runs με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Αφαιρεί τη διάταξη από την παρουσίαση. |

### Δείτε επίσης

* κλάση [BaseSlide](../baseslide)
* διασύνδεση [ILayoutSlide](../ilayoutslide)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->