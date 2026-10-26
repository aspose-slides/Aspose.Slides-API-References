---
title: IBaseSlide class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/ibaseslide/
---
## IBaseSlide κλάση

Αντιπροσωπεύει κοινά δεδομένα για όλους τους τύπους διαφανειών.

Ο τύπος IBaseSlide εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/el/aspose.slides/ibaseslide/shapes/) | Επιστρέφει τα σχήματα μιας διαφάνειας.<br/>            Μόνο για ανάγνωση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/el/aspose.slides/ibaseslide/controls/) | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια.<br/>            Μόνο για ανάγνωση [`IControlCollection`](/slides/python-net/el/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/el/aspose.slides/ibaseslide/name/) | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`slide_id`](/slides/python-net/el/aspose.slides/ibaseslide/slide_id/) | Επιστρέφει το ID μιας διαφάνειας.<br/>            Μόνο για ανάγνωση **int**. |
| [`custom_data`](/slides/python-net/el/aspose.slides/ibaseslide/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/el/aspose.slides/ibaseslide/timeline/) | Επιστρέφει το αντικείμενο χρονοδιάγραμμα κίνησης.<br/>            Μόνο για ανάγνωση [`IAnimationTimeLine`](/slides/python-net/el/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/el/aspose.slides/ibaseslide/slide_show_transition/) | Επιστρέφει το αντικείμενο TransitionEx που περιέχει πληροφορίες σχετικά με<br/>            το πώς η συγκεκριμένη διαφάνεια προχωρά κατά τη διάρκεια παρουσίασης.<br/>            Μόνο για ανάγνωση [`ISlideShowTransition`](/slides/python-net/el/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/el/aspose.slides/ibaseslide/background/) | Επιστρέφει το παρασκήνιο της διαφάνειας.<br/>            Μόνο για ανάγνωση [`IBackground`](/slides/python-net/el/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/ibaseslide/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους.<br/>            Μόνο για ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/el/aspose.slides/ibaseslide/show_master_shapes/) | Καθορίζει εάν τα σχήματα στη μητρική διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι.<br/>            Για τη μητρική διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα `false`.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`slide`](/slides/python-net/el/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/ibaseslide/presentation/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/el/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το συγκεκριμένο εναλλακτικό κείμενο. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Συγχωνεύει τα τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [`equals(self, slide)`](/slides/python-net/el/aspose.slides/ibaseslide/equals/#ibaseslide) | Καθορίζει εάν τα δύο αντικείμενα IBaseSlide είναι ίσα.<br/>            Η επιστρεφόμενη τιμή υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου.<br/>            Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, η κίνηση και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστικού, π.χ. SlideId και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στο Placeholder Ημερομηνίας. |
| [`create_theme_effective(self)`](/slides/python-net/el/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)