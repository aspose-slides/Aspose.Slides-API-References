---
title: MarkdownSaveOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions κλάση

Αναπαριστά τις επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.

**Κληρονομικότητα:**[`MarkdownSaveOptions`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)

Ο τύπος MarkdownSaveOptions εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/warning_callback/) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί.<br/>            Ανάγνωση/εγγραφή [`IWarningCallback`](/slides/python-net/el/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/progress_callback/) | Αντιπροσωπεύει ένα αντικείμενο callback για ενημερώσεις προόδου αποθήκευσης σε ποσοστό.<br/>            Δείτε [`IProgressCallback`](/slides/python-net/el/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η γραμματοσειρά προέλευσης.<br/>            Ανάγνωση-εγγραφή **str**. |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/gradient_style/) | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης.<br/>            Ανάγνωση/εγγραφή [`GradientStyle`](/slides/python-net/el/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Καθορίζει αν θα παραλειφθούν οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. <br/>            Ανάγνωση/εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| [`export_type`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/export_type/) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης.<br/>            Η προεπιλογή είναι `TextOnly`. |
| [`base_path`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/base_path/) | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους.<br/>            Η προεπιλογή είναι ο τρέχων φάκελος της εφαρμογής. |
| [`images_save_folder_name`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Καθορίζει το όνομα του φακέλου για την αποθήκευση των εικόνων.<br/>            Η προεπιλογή είναι `Images`. |
| [`new_line_type`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/new_line_type/) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows).<br/>            Η προεπιλογή είναι `Unix`. |
| [`show_comments`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/show_comments/) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι.<br/>            Η προεπιλογή είναι `false`. |
| [`show_hidden_slides`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι.<br/>            Η προεπιλογή είναι `false`. |
| [`show_slide_number`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι.<br/>            Η προεπιλογή είναι `false`. |
| [`flavor`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/flavor/) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης.<br/>            Η προεπιλογή είναι `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Επιστρέφει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown.<br/>            Η μορφή πρέπει να περιλαμβάνει το σύμβολο κράτησης θέσης "{0}", το οποίο θα αντικατασταθεί με το δείκτη της διαφάνειας κατά την εξαγωγή.<br/>            Παράδειγμα: "# Slide {0}" θα παράγει "# Slide 1", "# Slide 2", κ.λπ. |
| [`handle_repeated_spaces`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Αν οριστεί σε `true`, αφαιρεί κενές ή γραμμές που περιέχουν μόνο λευκούς χαρακτήρες από την τελική έξοδο Markdown.<br/>            Η προεπιλογή είναι `false`. |

### Δείτε επίσης
* κλάση [`MarkdownSaveOptions`](/slides/python-net/el/aspose.slides.export/markdownsaveoptions)
* κλάση [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)