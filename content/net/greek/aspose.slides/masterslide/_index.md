---
title: MasterSlide
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια κύρια διαφάνεια σε μια παρουσίαση.
type: docs
weight: 8030
url: /el/aspose.slides/masterslide/
---
## MasterSlide κλάση

Αντιπροσωπεύει μια κύρια διαφάνεια σε μια παρουσίαση.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Επιστρέφει το φόντο της διαφάνειας. Μόνο για ανάγνωση [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Επιστρέφει το στυλ κειμένου σώματος. Μόνο για ανάγνωση [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια. Μόνο για ανάγνωση [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Επιστρέφει μια συλλογή οδηγών σχεδίασης για τη κύρια διαφάνεια. Μόνο για ανάγνωση [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτή τη κύρια διαφάνεια. Μόνο για ανάγνωση Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας. Μόνο για ανάγνωση [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Παρέχει εύκολη πρόσβαση στους περιεχόμενους υπερσυνδέσμους. Μόνο για ανάγνωση [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Επιστρέφει τη συλλογή των παιδικών διαφανειών διάταξης για αυτή τη κύρια διαφάνεια. Μόνο για ανάγνωση [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα μιας κύριας διαφάνειας. Ανάγνωση/εγγραφή String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Επιστρέφει το στυλ ενός άλλου κειμένου. Μόνο για ανάγνωση [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Επιστρέφει τη διεπαφή IPresentation. Μόνο για ανάγνωση [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν διαγραφούν όλες οι διαφάνειες που ακολουθούν αυτήν την κύρια διαφάνεια. Σημείωση: Aspose.Slides δεν θα αφαιρέσει ποτέ κάποια αχρησιμοποίητη κύρια διαφάνεια από μόνο του· για να αφαιρέσετε πραγματικά αχρησιμοποίητες κύριες διαφάνειες καλέστε [`RemoveUnused`](../masterslidecollection/removeunused) Ανάγνωση/εγγραφή Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Επιστρέφει τα σχήματα μιας διαφάνειας. Μόνο για ανάγνωση [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Καθορίζει εάν τα σχήματα στη κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη ίδια τη κύρια διαφάνεια αυτή η ιδιότητα πάντα επιστρέφει `false`. Ανάγνωση/εγγραφή Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Επιστρέφει το ID μιας διαφάνειας. Μόνο για ανάγνωση UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες για το πώς η συγκεκριμένη διαφάνεια προχωρά κατά τη διάρκεια μιας παρουσίασης. Μόνο για ανάγνωση [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Επιστρέφει τον διαχειριστή θέματος. Μόνο για ανάγνωση [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Επιστρέφει το αντικείμενο χρονογραμμής animation. Μόνο για ανάγνωση [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Επιστρέφει το στυλ κειμένου τίτλου. Μόνο για ανάγνωση [`ITextStyle`](../itextstyle). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Δημιουργεί μια νέα κύρια διαφάνεια βάσει της τρέχουσας, εφαρμόζοντας ένα εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτώμενες διαφάνειες. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Καθορίζει εάν οι δύο στιγμές του IBaseSlide είναι ίσες. Η τιμή επιστροφής υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, στυλ, κείμενα, animation και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη μοναδικές τιμές αναγνωριστικών, π.χ. SlideId, και δυναμικού περιεχομένου, π.χ. τρέχουσα τιμή ημερομηνίας σε Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Βρίσκει την πρώτη εμφάνιση σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτή τη κύρια διαφάνεια. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Συνενώνει run με την ίδια μορφοποίηση σε όλες τις παραγράφους όλων των αποδεκτών σχημάτων. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Συνενώνει run με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |

### Δείτε επίσης

* κλάση [BaseSlide](../baseslide)
* διεπαφή [IMasterSlide](../imasterslide)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->