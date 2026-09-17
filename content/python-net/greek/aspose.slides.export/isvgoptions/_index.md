---
title: ISVGOptions class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.export/isvgoptions/
---
## ISVGOptions κλάση

Αντιπροσωπεύει τις επιλογές SVG.

Ο τύπος ISVGOptions εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/el/aspose.slides.export/isvgoptions/vectorize_text/) | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/el/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Επιστρέφει ή ορίζει το κατώτατο όριο ανάλυσης για rasterization μετααρχείου.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`disable_3d_text`](/slides/python-net/el/aspose.slides.export/isvgoptions/disable_3d_text/) | Καθορίζει αν το 3D κείμενο είναι απενεργοποιημένο στο SVG.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`disable_gradient_split`](/slides/python-net/el/aspose.slides.export/isvgoptions/disable_gradient_split/) | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/el/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για σημαδία.<br/>            Η μηχανή εγγραφής SVG της Aspose.Slides έχει παρακάτω λύση για αυτό το πρόβλημα:<br/>            κόβει το τέλος της γραμμής με το βέλος, έτσι η γραμμή δεν επικαλύπτει τις σημαδίες.<br/>            Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`jpeg_quality`](/slides/python-net/el/aspose.slides.export/isvgoptions/jpeg_quality/) | Καθορίζει την ποιότητα κωδικοποίησης JPEG.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`shape_formatting_controller`](/slides/python-net/el/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος.<br/>            Ανάγνωση/εγγραφή [`ISvgShapeFormattingController`](/slides/python-net/el/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/el/aspose.slides.export/isvgoptions/pictures_compression/) | Αντιπροσωπεύει το επίπεδο συμπίεσης των εικόνων<br/>            Ανάγνωση/εγγραφή [`ISVGOptions.pictures_compression`](/slides/python-net/el/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/el/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Μια λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Αν είναι true, τα περικομμένα <br/>            τμήματα θα αφαιρεθούν· αν είναι false, θα σειριοποιηθούν στο έγγραφο (που μπορεί ενδεχομένως να οδηγήσει σε <br/>            μεγαλύτερο αρχείο)<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`use_frame_size`](/slides/python-net/el/aspose.slides.export/isvgoptions/use_frame_size/) | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι.<br/>            Ανάγνωση/εγγραφή **bool**.<br/>            Η προεπιλεγμένη τιμή είναι false. |
| [`use_frame_rotation`](/slides/python-net/el/aspose.slides.export/isvgoptions/use_frame_rotation/) | Καθορίζει αν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι.<br/>            Ανάγνωση/εγγραφή **bool**.<br/>            Η προεπιλεγμένη τιμή είναι true. |
| [`external_fonts_handling`](/slides/python-net/el/aspose.slides.export/isvgoptions/external_fonts_handling/) | Καθορίζει τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών.<br/>            Ανάγνωση/εγγραφή [`SvgExternalFontsHandling`](/slides/python-net/el/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/el/aspose.slides.export/isvgoptions/ink_options/) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο.<br/>            Μόνο ανάγνωση [`IInkOptions`](/slides/python-net/el/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/el/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση λιγίων.<br/>            Όταν οριστεί σε `true`, οι λιγίες θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε `false`. |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)