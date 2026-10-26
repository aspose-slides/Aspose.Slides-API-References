---
title: ISwfOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/iswfoptions/
---
## ISwfOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή SWF.

Ο τύπος ISwfOptions εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`compressed`](/slides/python-net/el/aspose.slides.export/iswfoptions/compressed/) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι.<br/>            Η προεπιλογή είναι `true`. |
| [`viewer_included`](/slides/python-net/el/aspose.slides.export/iswfoptions/viewer_included/) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι.<br/>            Η προεπιλογή είναι `true`. |
| [`show_page_border`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_page_border/) | Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι true. |
| [`show_hidden_slides`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_hidden_slides/) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι.<br/>            Η προεπιλογή είναι `false`. |
| [`show_full_screen`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_full_screen/) | Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι true. |
| [`show_page_stepper`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_page_stepper/) | Εμφάνιση/απόκρυψη μεταβλήτη σελίδας. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι true. |
| [`show_search`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_search/) | Εμφάνιση/απόκρυψη ενότητας αναζήτησης. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι true. |
| [`show_top_pane`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_top_pane/) | Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι true. |
| [`show_bottom_pane`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_bottom_pane/) | Εμφάνιση/απόκρυψη κάτω περιοχής. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι true. |
| [`show_left_pane`](/slides/python-net/el/aspose.slides.export/iswfoptions/show_left_pane/) | Εμφάνιση/απόκρυψη αριστερής περιοχής. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι true. |
| [`start_open_left_pane`](/slides/python-net/el/aspose.slides.export/iswfoptions/start_open_left_pane/) | Έναρξη με ανοιχτή αριστερής περιοχή. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι false. |
| [`enable_context_menu`](/slides/python-net/el/aspose.slides.export/iswfoptions/enable_context_menu/) | Ενεργοποίηση/απενεργοποίηση του μενού περιβάλλοντος. Η προεπιλογή είναι true. |
| [`logo_image_bytes`](/slides/python-net/el/aspose.slides.export/iswfoptions/logo_image_bytes/) | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα.             <br/>            Η εικόνα πρέπει να είναι PNG 32x64 εικονοστοιχεία, αλλιώς το λογότυπο μπορεί να εμφανιστεί εσφαλμένα. |
| [`logo_link`](/slides/python-net/el/aspose.slides.export/iswfoptions/logo_link/) | Λαμβάνει ή ορίζει τη πλήρη διεύθυνση υπερσύνδεσμου για ένα λογότυπο.<br/>            Έχει επίδραση μόνο εάν έχει οριστεί ένα [`ISwfOptions.logo_image_bytes`](/slides/python-net/el/aspose.slides.export/iswfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/el/aspose.slides.export/iswfoptions/jpeg_quality/) | Καθορίζει την ποιότητα των εικόνων JPEG.             <br/>            Η προεπιλογή είναι 95. |
| [`slides_layout_options`](/slides/python-net/el/aspose.slides.export/iswfoptions/slides_layout_options/) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](/slides/python-net/el/aspose.slides.export/islideslayoutoptions).<br/>            Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου `Aspose.Slides.Export.HandoutLayoutingOptions` |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/iswfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/iswfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/iswfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/iswfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/iswfoptions/skip_java_script_links/) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)