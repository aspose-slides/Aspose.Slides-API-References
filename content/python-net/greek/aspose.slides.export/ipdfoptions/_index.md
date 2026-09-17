---
title: IPdfOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/ipdfoptions/
---
## IPdfOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Pdf.

Ο τύπος IPdfOptions εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`text_compression`](/slides/python-net/el/aspose.slides.export/ipdfoptions/text_compression/) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο.<br/>            Ανάγνωση/Εγγραφή [`PdfTextCompression`](/slides/python-net/el/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/el/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Υποδεικνύει εάν η πιο αποδοτική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται <br/>            αυτόματα. Εάν οριστεί σε **bool**.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, που θα οδηγήσει σε μικρότερο μέγεθος του τελικού εγγράφου PDF. <br/>            Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά δαπανηρή και απαιτεί <br/>            επιπλέον ποσότητα RAM, και αυτή η επιλογή είναι **bool**.false από προεπιλογή. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/el/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Αληθές για ενσωμάτωση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127.<br/>            Οι γραμματοσειρές για κωδικούς χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_hidden_slides`](/slides/python-net/el/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι.<br/>            Η προεπιλογή είναι `false`. |
| [`additional_common_font_families`](/slides/python-net/el/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα γραμματοσειρών καθορισμένα από τον χρήστη που η Aspose.Slides θα πρέπει να θεωρεί κοινά.<br/>            Ανάγνωση/Εγγραφή **str**[]. |
| [`embed_full_fonts`](/slides/python-net/el/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Καθορίζει εάν όλοι οι χαρακτήρες της γραμματοσειράς θα ενσωματωθούν ή μόνο ένα υποσύνολο.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/el/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Υποδεικνύει εάν το κείμενο πρέπει να ραστεροποιηθεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση.<br/>            Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο τελικό PDF για ορισμένες γραμματοσειρές.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`jpeg_quality`](/slides/python-net/el/aspose.slides.export/ipdfoptions/jpeg_quality/) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF.<br/>            Ανάγνωση/Εγγραφή **int**. |
| [`compliance`](/slides/python-net/el/aspose.slides.export/ipdfoptions/compliance/) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF.<br/>            Ανάγνωση/Εγγραφή [`PdfCompliance`](/slides/python-net/el/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/el/aspose.slides.export/ipdfoptions/password/) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. <br/>            Ανάγνωση/Εγγραφή **str**. |
| [`access_permissions`](/slides/python-net/el/aspose.slides.export/ipdfoptions/access_permissions/) | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγεται<br/>            με πρόσβαση χρήστη. Δείτε [`PdfAccessPermissions`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/el/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Αληθές για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`sufficient_resolution`](/slides/python-net/el/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF.<br/>
            <br/>Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.<br/><br/><br/>Η προεπιλεγμένη τιμή είναι **96** .<br/><br/><br/>            Ανάγνωση/Εγγραφή **float**. |
| [`draw_slides_frame`](/slides/python-net/el/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Αληθές για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια.<br/>             Ανάγνωση/Εγγραφή **bool**. |
| [`slides_layout_options`](/slides/python-net/el/aspose.slides.export/ipdfoptions/slides_layout_options/) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](/slides/python-net/el/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/el/aspose.slides.export/ipdfoptions/image_transparent_color/) | Λαμβάνει ή ορίζει το διαφανές χρώμα της εικόνας. |
| [`apply_image_transparent`](/slides/python-net/el/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν `true`. |
| [`ink_options`](/slides/python-net/el/aspose.slides.export/ipdfoptions/ink_options/) | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο.<br/>            Μόνο-ανάγνωση [`IInkOptions`](/slides/python-net/el/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/el/aspose.slides.export/ipdfoptions/include_ole_data/) | Αληθές για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |


### Δείτε επίσης
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)