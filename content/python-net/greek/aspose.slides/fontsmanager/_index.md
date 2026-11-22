---
title: FontsManager class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/fontsmanager/
---
## FontsManager κλάση

Διαχειρίζεται τις γραμματοσειρές σε όλη την παρουσίαση.

Ο τύπος FontsManager εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/el/aspose.slides/fontsmanager/font_subst_rule_list/) | Αντικαταστάσεις γραμματοσειρών για χρήση κατά την απόδοση.<br/>            Ανάγνωση/εγγραφή [`IFontSubstRuleCollection`](/slides/python-net/el/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/el/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Αντιπροσωπεύει τη συλλογή ενός χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback.<br/>            Ανάγνωση/εγγραφή [`IFontFallBackRulesCollection`](/slides/python-net/el/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/el/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Καθορίζει εάν οι καταχωρημένες γραμματοσειρές πρέπει να προτιμούται έναντι των ενσωματωμένων γραμματοσειρών με το ίδιο όνομα και στυλ.<br/>            Όταν είναι ενεργό, οι αντίστοιχες ενσωματωμένες γραμματοσειρές αντικαθίστανται προσωρινά με τις αντίστοιχες καταχωρημένες γραμματοσειρές κατά την εξαγωγή. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/el/aspose.slides/fontsmanager/get_substitutions/#) | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν στην απόδοση της παρουσίασης. |
| [`get_substitutions(self, slides)`](/slides/python-net/el/aspose.slides/fontsmanager/get_substitutions/#listint) | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των καθορισμένων διαφανειών. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά<br/>            Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι προστατευμένες με πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο υπολογιστή. Ένα ArgumentException μπορεί να ριχτεί εάν τα δεδομένα της γραμματοσειράς είναι None ή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά<br/>            Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι προστατευμένες με πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο υπολογιστή. Ένα ArgumentException μπορεί να ριχτεί εάν τα δεδομένα της γραμματοσειράς είναι None ή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/el/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Αντικατάσταση γραμματοσειράς στην παρουσίαση |
| [`replace_font(self, subst_rule)`](/slides/python-net/el/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [`FontSubstRule`](/slides/python-net/el/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/el/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή των [`FontSubstRule`](/slides/python-net/el/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/el/aspose.slides/fontsmanager/get_fonts/#) | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |
| [`get_embedded_fonts(self)`](/slides/python-net/el/aspose.slides/fontsmanager/get_embedded_fonts/#) | Επιστρέφει τις γραμματοσειρές που είναι ενσωματωμένες στην παρουσίαση |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/el/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Αφαιρεί την ενσωματωμένη γραμματοσειρά |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/el/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Ανακτά τον πίνακα bytes που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα καθορισμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/el/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δοθέντα πίνακα bytes και το όνομα γραμματοσειράς. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)