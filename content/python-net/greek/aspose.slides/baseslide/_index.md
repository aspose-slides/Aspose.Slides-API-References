---
title: BaseSlide class
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/baseslide/
---
## BaseSlide κλάση

Αναπαριστά τα κοινά δεδομένα για όλους τους τύπους διαφανειών.

Ο τύπος BaseSlide εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`shapes`](/slides/python-net/el/aspose.slides/baseslide/shapes/) | Επιστρέφει τα σχήματα μιας διαφάνειας.<br/>            Μόνο ανάγνωση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/el/aspose.slides/baseslide/controls/) | Επιστρέφει τη συλλογή των ενεργών ελέγχων (ActiveX) σε μια διαφάνεια.<br/>            Μόνο ανάγνωση [`IControlCollection`](/slides/python-net/el/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/el/aspose.slides/baseslide/name/) | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`slide_id`](/slides/python-net/el/aspose.slides/baseslide/slide_id/) | Επιστρέφει το ID μιας διαφάνειας.<br/>            Μόνο ανάγνωση **int**. |
| [`custom_data`](/slides/python-net/el/aspose.slides/baseslide/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας.<br/>            Μόνο ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/el/aspose.slides/baseslide/timeline/) | Επιστρέφει το αντικείμενο χρονοδιαγράμματος κίνησης.<br/>            Μόνο ανάγνωση [`IAnimationTimeLine`](/slides/python-net/el/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/el/aspose.slides/baseslide/slide_show_transition/) | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες για<br/>            το πώς η συγκεκριμένη διαφάνεια προοδεύει κατά τη διάρκεια παρουσίασης.<br/>            Μόνο ανάγνωση [`ISlideShowTransition`](/slides/python-net/el/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/el/aspose.slides/baseslide/background/) | Επιστρέφει το παρασκήνιο της διαφάνειας.<br/>            Μόνο ανάγνωση [`IBackground`](/slides/python-net/el/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/baseslide/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους.<br/>            Μόνο ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/el/aspose.slides/baseslide/show_master_shapes/) | Καθορίζει αν τα σχήματα στην κύρια διαφάνεια θα πρέπει να εμφανίζονται σε άλλες διαφάνειες ή όχι.<br/>            Στην κύρια διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα `false`.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`presentation`](/slides/python-net/el/aspose.slides/baseslide/presentation/) | Επιστρέφει το interface IPresentation.<br/>            Μόνο ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/el/aspose.slides/baseslide/slide/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Συγχωνεύει τμημάτα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους όλα τα αποδεκτά σχήματα. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/el/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Συγχωνεύει τμημάτα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [`equals(self, slide)`](/slides/python-net/el/aspose.slides/baseslide/equals/#ibaseslide) | Καθορίζει εάν τα δύο αντικείμενα IBaseSlide είναι ίσα.<br/>            Η τιμή επιστροφής υπολογίζεται βάσει της δομής και του στατικού περιεχομένου της διαφάνειας.<br/>            Δύο διαφάνειες είναι ίσες αν όλα τα σχήματα, στυλ, κείμενα, κινήσεις και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη μοναδικές τιμές ταυτοτήτων, π.χ. SlideId, ούτε δυναμικό περιεχόμενο, π.χ. τρέχουσα τιμή ημερομηνίας σε placeholder ημερομηνίας. |
| [`create_theme_effective(self)`](/slides/python-net/el/aspose.slides/baseslide/create_theme_effective/#) | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/el/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |


### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)