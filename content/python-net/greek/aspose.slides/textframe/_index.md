---
title: TextFrame class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/textframe/
---
## TextFrame κλάση

Αναπαριστά ένα TextFrame.

Ο τύπος TextFrame εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`paragraphs`](/slides/python-net/el/aspose.slides/textframe/paragraphs/) | Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο.<br/> Μόνο για ανάγνωση [`IParagraphCollection`](/slides/python-net/el/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/el/aspose.slides/textframe/text/) | Αποκτά ή ορίζει το απλό κείμενο για ένα TextFrame.<br/> Ανάγνωση/εγγραφή **str**. |
| [`text_frame_format`](/slides/python-net/el/aspose.slides/textframe/text_frame_format/) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame.<br/> Μόνο για ανάγνωση [`ITextFrameFormat`](/slides/python-net/el/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/textframe/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους.<br/> Μόνο για ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/el/aspose.slides/textframe/slide/) | Επιστρέφει τη γονική διαφάνεια ενός TextFrame.<br/> Μόνο για ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/textframe/presentation/) | Επιστρέφει τη γονική παρουσίαση ενός TextFrame.<br/> Μόνο για ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/el/aspose.slides/textframe/parent_shape/) | Επιστρέφει το γονικό σχήμα ή None εάν το γονικό αντικείμενο δεν υλοποιεί την διεπαφή IShape<br/> Μόνο για ανάγνωση [`IShape`](/slides/python-net/el/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/el/aspose.slides/textframe/parent_cell/) | Επιστρέφει το γονικό κελί ή None εάν το γονικό αντικείμενο δεν υλοποιεί την διεπαφή ICell.<br/> Μόνο για ανάγνωση [`ICell`](/slides/python-net/el/aspose.slides/icell). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/el/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/el/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/el/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/el/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/el/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/textframe/join_portions_with_same_formatting/#) | Ενώνει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους. |
| [`split_text_by_columns(self)`](/slides/python-net/el/aspose.slides/textframe/split_text_by_columns/#) | Διχοτομεί το κειμενικό περιεχόμενο του [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, <br/> όπου κάθε στοιχείο αντιστοιχεί σε ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/el/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/el/aspose.slides/textframe/replace_regex/#str-str) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)