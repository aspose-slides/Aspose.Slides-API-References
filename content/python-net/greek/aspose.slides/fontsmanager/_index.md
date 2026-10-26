---
title: FontsManager class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/fontsmanager/
---
## FontsManager κλάση

Διαχειρίζεται τις γραμματοσειρές σε όλη την παρουσίαση.

Ο τύπος FontsManager εμφανίζει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/el/aspose.slides/fontsmanager/font_subst_rule_list/) | Αντικαταστάσεις γραμματοσειρών που θα χρησιμοποιηθούν κατά την απόδοση.<br/>            Ανάγνωση/εγγραφή [`IFontSubstRuleCollection`](/slides/python-net/el/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/el/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω λειτουργίας fallback<br/>            Ανάγνωση/εγγραφή [`IFontFallBackRulesCollection`](/slides/python-net/el/aspose.slides/ifontfallbackrulescollection). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/el/aspose.slides/fontsmanager/get_substitutions/#) | Λαμβάνει τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |
| [`get_substitutions(self, slides)`](/slides/python-net/el/aspose.slides/fontsmanager/get_substitutions/#listint) | Λαμβάνει τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των καθορισμένων διαφανειών. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Προσθέτει τη ενσωματωμένη γραμματοσειρά<br/>            Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι προστατευμένες πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο υπολογιστή. Μπορεί να προκληθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι None ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Προσθέτει τη ενσωματωμένη γραμματοσειρά<br/>            Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι προστατευμένες πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο υπολογιστή. Μπορεί να προκληθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι None ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/el/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση |
| [`replace_font(self, subst_rule)`](/slides/python-net/el/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [`FontSubstRule`](/slides/python-net/el/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/el/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται σε μια συλλογή του [`FontSubstRule`](/slides/python-net/el/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/el/aspose.slides/fontsmanager/get_fonts/#) | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |
| [`get_embedded_fonts(self)`](/slides/python-net/el/aspose.slides/fontsmanager/get_embedded_fonts/#) | Επιστρέφει τις γραμματοσειρές που είναι ενσωματωμένες στην παρουσίαση |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/el/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Αφαιρεί τη ενσωματωμένη γραμματοσειρά |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/el/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα καθορισμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/el/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δεδομένο πίνακα byte και το όνομα της γραμματοσειράς. |


### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)