---
title: HtmlOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/htmloptions/
---
## HtmlOptions κλάση

Αναπαριστά επιλογές εξαγωγής HTML.

**Κληρονομικότητα:**[`HtmlOptions`](/slides/python-net/el/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)

Ο τύπος HtmlOptions εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/el/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Δημιουργεί ένα νέο αντικείμενο HtmlOptions που καθορίζει την callback. |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.export/htmloptions/__init__/#) | Δημιουργεί ένα νέο αντικείμενο HtmlOptions για αποθήκευση σε ένα μόνο αρχείο HTML. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/htmloptions/warning_callback/) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί.<br/>            Ανάγνωση/Εγγραφή [`IWarningCallback`](/slides/python-net/el/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/htmloptions/progress_callback/) | Αναπαριστά ένα αντικείμενο callback για αποθήκευση ενημερώσεων προόδου σε ποσοστό.<br/>            Δείτε [`IProgressCallback`](/slides/python-net/el/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/htmloptions/default_regular_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί.<br/>            Ανάγνωση-Εγγραφή **str**. |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/htmloptions/gradient_style/) | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης.<br/>            Ανάγνωση/Εγγραφή [`GradientStyle`](/slides/python-net/el/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/htmloptions/skip_java_script_links/) | Καθορίζει αν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης.<br/>            Ανάγνωση/Εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| [`slides_layout_options`](/slides/python-net/el/aspose.slides.export/htmloptions/slides_layout_options/) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](/slides/python-net/el/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/el/aspose.slides.export/htmloptions/ink_options/) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαχθέν έγγραφο.<br/>            Μόνο ανάγνωση [`IInkOptions`](/slides/python-net/el/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/el/aspose.slides.export/htmloptions/show_hidden_slides/) | Καθορίζει αν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι.<br/>            Η προεπιλεγμένη τιμή είναι `false`. |
| [`html_formatter`](/slides/python-net/el/aspose.slides.export/htmloptions/html_formatter/) | Επιστρέφει ή ορίζει το πρότυπο HTML.<br/>            Ανάγνωση/Εγγραφή [`IHtmlFormatter`](/slides/python-net/el/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/el/aspose.slides.export/htmloptions/disable_font_ligatures/) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο θα αποδιδόμενα χωρίς χρήση λογώσεων.<br/>            Όταν οριστεί σε `true`, οι λογώσες θα απενεργοποιηθούν στην αποδιδόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε `false`. |
| [`slide_image_format`](/slides/python-net/el/aspose.slides.export/htmloptions/slide_image_format/) | Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας.<br/>            Ανάγνωση/Εγγραφή [`ISlideImageFormat`](/slides/python-net/el/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/el/aspose.slides.export/htmloptions/jpeg_quality/) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF.<br/>            Ανάγνωση-Εγγραφή **int**. |
| [`pictures_compression`](/slides/python-net/el/aspose.slides.export/htmloptions/pictures_compression/) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |
| [`delete_pictures_cropped_areas`](/slides/python-net/el/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Μία λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα διατηρούνται ως μέρος του εγγράφου. Εάν είναι true, τα περικομμένα<br/>            τμήματα θα αφαιρεθούν, εάν είναι false θα σειριακοποιηθούν στο έγγραφο (που μπορεί ενδεχομένως να οδηγήσει σε<br/>            μεγαλύτερο αρχείο) |
| [`svg_responsive_layout`](/slides/python-net/el/aspose.slides.export/htmloptions/svg_responsive_layout/) | True για να εξαλειφθούν τα χαρακτηριστικά πλάτους και ύψους από το δοχείο svg - αυτό θα κάνει τη διάταξη ανταποκρινόμενη. False - διαφορετικά.<br/>            Ανάγνωση/Εγγραφή **bool**. |

### Δείτε επίσης
* κλάση [`HtmlOptions`](/slides/python-net/el/aspose.slides.export/htmloptions)
* κλάση [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)