---
title: MasterSlide class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/masterslide/
---
## MasterSlide κλάση

Αντιπροσωπεύει μια master διαφάνεια σε μια παρουσίαση.

**Inheritance:**[`MasterSlide`](/slides/python-net/el/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/el/aspose.slides/baseslide)

Ο τύπος MasterSlide εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`shapes`](/slides/python-net/el/aspose.slides/masterslide/shapes/) | Επιστρέφει τα σχήματα μιας διαφάνειας.<br/>            Μόνο ανάγνωση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/el/aspose.slides/masterslide/controls/) | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια.<br/>            Μόνο ανάγνωση [`IControlCollection`](/slides/python-net/el/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/el/aspose.slides/masterslide/name/) | Επιστρέφει ή ορίζει το όνομα μιας master διαφάνειας.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`slide_id`](/slides/python-net/el/aspose.slides/masterslide/slide_id/) | Επιστρέφει το ID μιας διαφάνειας.<br/>            Μόνο ανάγνωση **int**. |
| [`custom_data`](/slides/python-net/el/aspose.slides/masterslide/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας.<br/>            Μόνο ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/el/aspose.slides/masterslide/timeline/) | Επιστρέφει το αντικείμενο χρονοδιάγραμμα κίνησης.<br/>            Μόνο ανάγνωση [`IAnimationTimeLine`](/slides/python-net/el/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/el/aspose.slides/masterslide/slide_show_transition/) | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες για<br/>            το πώς η καθορισμένη διαφάνεια προχωρά κατά τη διάρκεια μιας παρουσίασης.<br/>            Μόνο ανάγνωση [`ISlideShowTransition`](/slides/python-net/el/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/el/aspose.slides/masterslide/background/) | Επιστρέφει το παρασκήνιο της διαφάνειας.<br/>            Μόνο ανάγνωση [`IBackground`](/slides/python-net/el/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/masterslide/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους.<br/>            Μόνο ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/el/aspose.slides/masterslide/show_master_shapes/) | Καθορίζει εάν τα σχήματα στη master διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι.<br/>            Για τη ίδια τη master διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα `false`.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`presentation`](/slides/python-net/el/aspose.slides/masterslide/presentation/) | Επιστρέφει τη διεπαφή IPresentation.<br/>            Μόνο ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/el/aspose.slides/masterslide/header_footer_manager/) | Επιστρέφει το διαχειριστή HeaderFooter της master διαφάνειας.<br/>            Μόνο ανάγνωση [`IMasterSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/el/aspose.slides/masterslide/title_style/) | Επιστρέφει το στυλ του κειμένου τίτλου.<br/>            Μόνο ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/el/aspose.slides/masterslide/body_style/) | Επιστρέφει το στυλ του κυρίως κειμένου.<br/>            Μόνο ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/el/aspose.slides/masterslide/other_style/) | Επιστρέφει το στυλ ενός άλλου κειμένου.<br/>            Μόνο ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/el/aspose.slides/masterslide/layout_slides/) | Επιστρέφει τη συλλογή των παιδικών διαφανειών διάταξης για αυτή τη master διαφάνεια.<br/>            Μόνο ανάγνωση [`IMasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/el/aspose.slides/masterslide/preserve/) | Καθορίζει εάν η αντίστοιχη master διαφάνεια διαγράφεται όταν όλες οι διαφάνειες που την ακολουθούν έχουν διαγραφεί.<br/>            Σημείωση: Η Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα μια αχρησιμοποίητη master, για την πραγματική αφαίρεση καλείτε **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`has_depending_slides`](/slides/python-net/el/aspose.slides/masterslide/has_depending_slides/) | Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτή τη master διαφάνεια.<br/>            Μόνο ανάγνωση **bool**. |
| [`theme_manager`](/slides/python-net/el/aspose.slides/masterslide/theme_manager/) | Επιστρέφει το διαχειριστή θέματος.<br/>            Μόνο ανάγνωση [`IMasterThemeManager`](/slides/python-net/el/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/el/aspose.slides/masterslide/drawing_guides/) | Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη master διαφάνεια.<br/>            Μόνο ανάγνωση [`IDrawingGuidesCollection`](/slides/python-net/el/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/el/aspose.slides/masterslide/slide/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Συνενώνει τα τμήματα με ίδια μορφοποίηση σε όλες τις παραγράφους όλων των αποδεκτών σχημάτων. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/el/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Συνενώνει τα τμήματα με ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [`equals(self, slide)`](/slides/python-net/el/aspose.slides/masterslide/equals/#ibaseslide) | Καθορίζει εάν οι δύο αντικείμενα IBaseSlide είναι ίσοι.<br/>            Η τιμή επιστροφής υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου.<br/>            Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, η κίνηση και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστικών, π.χ. SlideId, και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας σε Placeholder Ημερομηνίας. |
| [`create_theme_effective(self)`](/slides/python-net/el/aspose.slides/masterslide/create_theme_effective/#) | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/el/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/el/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Δημιουργεί μια νέα master διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζοντας σε αυτή ένα εξωτερικό θέμα <br/>            και εφαρμόζει τη δημιουργημένη master διαφάνεια σε όλες τις εξαρτημένες διαφάνειες. |
| [`get_depending_slides(self)`](/slides/python-net/el/aspose.slides/masterslide/get_depending_slides/#) | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτή τη master διαφάνεια. |


### Δείτε επίσης
* κλάση [`BaseSlide`](/slides/python-net/el/aspose.slides/baseslide)
* κλάση [`MasterSlide`](/slides/python-net/el/aspose.slides/masterslide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)