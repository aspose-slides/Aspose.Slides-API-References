---
title: ITextFrame class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/itextframe/
---
## ITextFrame κλάση

Αναπαριστά ένα TextFrame.

Ο τύπος ITextFrame εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/el/aspose.slides/itextframe/paragraphs/) | Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο.<br/>            Μόνο για ανάγνωση [`IParagraphCollection`](/slides/python-net/el/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/el/aspose.slides/itextframe/text/) | Λαμβάνει ή ορίζει το απλό κείμενο για ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`text_frame_format`](/slides/python-net/el/aspose.slides/itextframe/text_frame_format/) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame.<br/>            Μόνο για ανάγνωση [`ITextFrameFormat`](/slides/python-net/el/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/itextframe/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση σε ενσωματωμένους υπερσυνδέσμους.<br/>            Μόνο για ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/el/aspose.slides/itextframe/parent_shape/) | Επιστρέφει το γονικό σχήμα ή None εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή IShape<br/>            Μόνο για ανάγνωση [`IShape`](/slides/python-net/el/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/el/aspose.slides/itextframe/parent_cell/) | Επιστρέφει το γονικό κελί ή None εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή ICell.<br/>            Μόνο για ανάγνωση [`ICell`](/slides/python-net/el/aspose.slides/icell). |
| [`slide`](/slides/python-net/el/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/itextframe/presentation/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/el/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/el/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/el/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/el/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/el/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Συγχωνεύει τα runs με την ίδια μορφοποίηση σε όλα τα παραγράφων. |
| [`split_text_by_columns(self)`](/slides/python-net/el/aspose.slides/itextframe/split_text_by_columns/#) | Διαιρεί το κείμενο του [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών,  <br/>            όπου κάθε στοιχείο αντιστοιχεί σε ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/el/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/el/aspose.slides/itextframe/replace_regex/#str-str) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)