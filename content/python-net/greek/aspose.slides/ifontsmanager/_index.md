---
title: IFontsManager class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ifontsmanager/
---
## IFontsManager κλάση

Διαχειρίζεται τις γραμματοσειρές σε όλη την παρουσίαση.

Ο τύπος IFontsManager εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/el/aspose.slides/ifontsmanager/font_subst_rule_list/) | Αντικαταστάσεις γραμματοσειρών για χρήση κατά την απόδοση<br/>            Ανάγνωση/εγγραφή [`IFontSubstRuleCollection`](/slides/python-net/el/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/el/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω λειτουργίας fallback<br/>            Ανάγνωση/εγγραφή [`IFontFallBackRulesCollection`](/slides/python-net/el/aspose.slides/ifontfallbackrulescollection). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_substitutions/#) | Αποκτά τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |
| [`get_substitutions(self, slides)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_substitutions/#listint) | Αποκτά τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των καθορισμένων διαφανειών. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά.<br/>            Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι προστατευμένες από πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και επιβεβαιώστε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο μηχάνημα. Μπορεί να προκληθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι None ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά.<br/>            Λάβετε υπόψη ότι όταν προσθέτετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι προστατευμένες από πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και επιβεβαιώστε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο μηχάνημα. Μπορεί να προκληθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι None ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/el/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Αντικατάσταση γραμματοσειράς στην παρουσίαση |
| [`replace_font(self, subst_rule)`](/slides/python-net/el/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [`IFontSubstRule`](/slides/python-net/el/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/el/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή του [`IFontSubstRule`](/slides/python-net/el/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_fonts/#) | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |
| [`get_embedded_fonts(self)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Επιστρέφει τις γραμματοσειρές που είναι ενσωματωμένες στην παρουσίαση |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/el/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Αφαιρεί την ενσωματωμένη γραμματοσειρά |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Αποκτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα συγκεκριμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δοθέντα πίνακα byte και το όνομα γραμματοσειράς. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)