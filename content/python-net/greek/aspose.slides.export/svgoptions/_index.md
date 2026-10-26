---
title: SVGOptions class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.export/svgoptions/
---
## SVGOptions κλάση

Αντιπροσωπεύει επιλογές SVG.

**Κληρονομικότητα:**[`SVGOptions`](/slides/python-net/el/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)

Ο τύπος SVGOptions εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.export/svgoptions/__init__/#) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/el/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SVGOptions καθορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμων. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/svgoptions/warning_callback/) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα τερματιστεί.<br/>            Ανάγνωση/εγγραφή [`IWarningCallback`](/slides/python-net/el/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/svgoptions/progress_callback/) | Αντιπροσωπεύει ένα αντικείμενο κλήσης επιστροφής για αποθήκευση ενημερώσεων προόδου σε ποσοστό.<br/>            Δείτε [`IProgressCallback`](/slides/python-net/el/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/svgoptions/default_regular_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγή γραμματοσειράς δεν βρεθεί.<br/>            Ανάγνωση-εγγραφή **str**. |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/svgoptions/gradient_style/) | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης.<br/>            Ανάγνωση/εγγραφή [`GradientStyle`](/slides/python-net/el/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/svgoptions/skip_java_script_links/) | Καθορίζει εάν θα παραλείπεται οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. <br/>            Ανάγνωση/εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| [`ink_options`](/slides/python-net/el/aspose.slides.export/svgoptions/ink_options/) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο.<br/>            Μόνο ανάγνωση [`IInkOptions`](/slides/python-net/el/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/el/aspose.slides.export/svgoptions/use_frame_size/) | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι.<br/>            Ανάγνωση/εγγραφή **bool**.<br/>            Η προεπιλεγμένη τιμή είναι false. |
| [`use_frame_rotation`](/slides/python-net/el/aspose.slides.export/svgoptions/use_frame_rotation/) | Καθορίζει εάν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι.<br/>            Ανάγνωση/εγγραφή **bool**.<br/>            Η προεπιλεγμένη τιμή είναι true. |
| [`vectorize_text`](/slides/python-net/el/aspose.slides.export/svgoptions/vectorize_text/) | Καθορίζει εάν το κείμενο στη διαφάνεια θα αποθηκευτεί ως γραφικά.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/el/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Επιστρέφει ή ορίζει το κατώτατο όριο ανάλυσης για rasterization μετααρχείου.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`disable_3d_text`](/slides/python-net/el/aspose.slides.export/svgoptions/disable_3d_text/) | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο στο SVG.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`disable_gradient_split`](/slides/python-net/el/aspose.slides.export/svgoptions/disable_gradient_split/) | Απενεργοποιεί το διαχωρισμό των διαβαθμίσεων FromCornerX και FromCenter.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/el/aspose.slides.export/svgoptions/disable_line_end_cropping/) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για σημεία.<br/>            Η μηχανή εγγραφής SVG του Aspose.Slides έχει λύση για αυτό το πρόβλημα:<br/>            περικόπτει το άκρο της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τα σημεία.<br/>            Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`default`](/slides/python-net/el/aspose.slides.export/svgoptions/default/) | Επιστρέφει τις προεπιλεγμένες ρυθμίσεις.<br/>            Μόνο ανάγνωση [`SVGOptions`](/slides/python-net/el/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/el/aspose.slides.export/svgoptions/simple/) | Επιστρέφει ρυθμίσεις για τη δημιουργία του πιο απλού και μικρότερου αρχείου SVG.<br/>            Μόνο ανάγνωση [`SVGOptions`](/slides/python-net/el/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/el/aspose.slides.export/svgoptions/wysiwyg/) | Επιστρέφει ρυθμίσεις για τη δημιουργία του πιο ακριβούς αρχείου SVG.<br/>            Μόνο ανάγνωση [`SVGOptions`](/slides/python-net/el/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/el/aspose.slides.export/svgoptions/jpeg_quality/) | Καθορίζει την ποιότητα κωδικοποίησης JPEG.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`shape_formatting_controller`](/slides/python-net/el/aspose.slides.export/svgoptions/shape_formatting_controller/) | Επιστρέφει και ορίζει μια διεπαφή κλήσης επιστροφής που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος.<br/>            Ανάγνωση/εγγραφή [`ISvgShapeFormattingController`](/slides/python-net/el/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/el/aspose.slides.export/svgoptions/pictures_compression/) | Αντιπροσωπεύει το επίπεδο συμπίεσης των εικόνων |
| [`delete_pictures_cropped_areas`](/slides/python-net/el/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Μία λογική σημαία δείχνει εάν τα περικομμένα μέρη παραμένουν μέρος του εγγράφου. Εάν είναι true, τα περικομμένα <br/>            μέρη θα αφαιρεθούν, εάν είναι false θα σειριοποιηθούν στο έγγραφο (που μπορεί ενδεχομένως να οδηγήσει σε <br/>            μεγαλύτερο αρχείο). |
| [`external_fonts_handling`](/slides/python-net/el/aspose.slides.export/svgoptions/external_fonts_handling/) | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών.<br/>            Ανάγνωση/εγγραφή [`SvgExternalFontsHandling`](/slides/python-net/el/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/el/aspose.slides.export/svgoptions/disable_font_ligatures/) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λιγκατών.<br/>            Όταν οριστεί σε `true`, οι λιγκατίνες θα απενεργοποιηθούν στην αποδοθήσα έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε `false`. |

### Δείτε επίσης
* κλάση [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)
* κλάση [`SVGOptions`](/slides/python-net/el/aspose.slides.export/svgoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)