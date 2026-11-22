---
title: IFontsManager class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/ifontsmanager/
---
## IFontsManager κλάση

Διαχειρίζεται τις γραμματοσειρές σε ολόκληρη την παρουσίαση.

Ο τύπος IFontsManager εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/el/aspose.slides/ifontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering<br/>            Ανάγνωση/εγγραφή [`IFontSubstRuleCollection`](/slides/python-net/el/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/el/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Ανάγνωση/εγγραφή [`IFontFallBackRulesCollection`](/slides/python-net/el/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/el/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Specifies whether registered fonts should be preferred over embedded fonts with the same font name and style.<br/>            Όταν ενεργοποιηθεί, οι ταιριαστές ενσωματωμένες γραμματοσειρές αντικαθίστανται προσωρινά με τις αντίστοιχες καταχωρισμένες γραμματοσειρές κατά την εξαγωγή. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_substitutions/#) | Αποκτά τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |
| [`get_substitutions(self, slides)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_substitutions/#listint) | Αποκτά τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των καθορισμένων διαφανειών. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά.<br/>            Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι προστατευμένες από πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορούν να μεταφερθούν ελεύθερα σε άλλο μηχάνημα. Μια ArgumentException μπορεί να εξαχθεί εάν τα δεδομένα της γραμματοσειράς είναι None ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/el/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά<br/>            Λάβετε υπόψη όταν προσθέτετε οποιεσδήποτε γραμματοσειρές, ότι οι περισσότερες προστατεύονται από πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορούν να μεταφερθούν ελεύθερα σε άλλο μηχάνημα. Μια ArgumentException μπορεί να εξαχθεί εάν τα δεδομένα της γραμματοσειράς είναι None ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/el/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Αντικατάσταση γραμματοσειράς στην παρουσίαση |
| [`replace_font(self, subst_rule)`](/slides/python-net/el/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [`IFontSubstRule`](/slides/python-net/el/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/el/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή του [`IFontSubstRule`](/slides/python-net/el/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_fonts/#) | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |
| [`get_embedded_fonts(self)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Επιστρέφει τις γραμματοσειρές που είναι ενσωματωμένες στην παρουσίαση |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/el/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Αφαιρεί την ενσωματωμένη γραμματοσειρά |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Ανακτά τον πίνακα bytes που αντιπροσωπεύει τα δεδομένα της γραμματοσειράς για ένα καθορισμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/el/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δεδομένο πίνακα bytes και το όνομα της γραμματοσειράς. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)