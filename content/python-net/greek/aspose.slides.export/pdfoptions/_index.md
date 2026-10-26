---
title: PdfOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/pdfoptions/
---
## PdfOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Pdf.

**Κληρονομικότητα:**[`PdfOptions`](/slides/python-net/el/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)

Ο τύπος PdfOptions εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.export/pdfoptions/__init__/#) | Προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/pdfoptions/warning_callback/) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί.<br/>            Ανάγνωση/εγγραφή [`IWarningCallback`](/slides/python-net/el/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/pdfoptions/progress_callback/) | Αντιπροσωπεύει ένα αντικείμενο κλήσης επιστροφής για ενημερώσεις προόδου αποθήκευσης σε ποσοστό.<br/>            Δείτε [`IProgressCallback`](/slides/python-net/el/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/pdfoptions/default_regular_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά.<br/>            Ανάγνωση-εγγραφή **str**. |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/pdfoptions/gradient_style/) | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης.<br/>            Ανάγνωση/εγγραφή [`GradientStyle`](/slides/python-net/el/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/pdfoptions/skip_java_script_links/) | Καθορίζει εάν θα παραλειφθούν οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης.<br/>            Ανάγνωση/εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| [`slides_layout_options`](/slides/python-net/el/aspose.slides.export/pdfoptions/slides_layout_options/) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τα διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](/slides/python-net/el/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/el/aspose.slides.export/pdfoptions/ink_options/) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο.<br/>            Μόνο-ανάγνωση [`IInkOptions`](/slides/python-net/el/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/el/aspose.slides.export/pdfoptions/show_hidden_slides/) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι.<br/>            Η προεπιλογή είναι `false`. |
| [`text_compression`](/slides/python-net/el/aspose.slides.export/pdfoptions/text_compression/) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου.<br/>            Ανάγνωση/εγγραφή [`PdfTextCompression`](/slides/python-net/el/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/el/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Δηλώνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται <br/>αυτόματα. Εάν οριστεί σε **bool**.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, με αποτέλεσμα το μικρότερο μέγεθος του παραγόμενου εγγράφου PDF. <br/>Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και καταναλώνει <br/>επιπλέον μνήμη RAM, και αυτή η επιλογή είναι **bool**.false εξ ορισμού. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/el/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Καθορίζει αν το Aspose.Slides θα ενσωματώνει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδίκων 33..127).<br/>            Οι γραμματοσειρές για κωδικούς χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα.<br/>            Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές του PDF και επιπλέον γραμματοσειρές που ορίζει ο χρήστης.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`additional_common_font_families`](/slides/python-net/el/aspose.slides.export/pdfoptions/additional_common_font_families/) | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών που ορίζονται από τον χρήστη και τα οποία το Aspose.Slides θα θεωρήσει κοινά.<br/>            Ανάγνωση/εγγραφή **str**[]. |
| [`embed_full_fonts`](/slides/python-net/el/aspose.slides.export/pdfoptions/embed_full_fonts/) | Καθορίζει αν πρέπει να ενσωματωθούν όλοι οι χαρακτήρες της γραμματοσειράς ή μόνο το χρησιμοποιούμενο υποσύνολο.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/el/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Δηλώνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση.<br/>            Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`jpeg_quality`](/slides/python-net/el/aspose.slides.export/pdfoptions/jpeg_quality/) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`compliance`](/slides/python-net/el/aspose.slides.export/pdfoptions/compliance/) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF.<br/>            Ανάγνωση/εγγραφή [`PdfCompliance`](/slides/python-net/el/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/el/aspose.slides.export/pdfoptions/password/) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`access_permissions`](/slides/python-net/el/aspose.slides.export/pdfoptions/access_permissions/) | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγούνται όταν το έγγραφο ανοίγει<br/>με πρόσβαση χρήστη. Δείτε [`PdfAccessPermissions`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/el/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Αληθές για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`sufficient_resolution`](/slides/python-net/el/aspose.slides.export/pdfoptions/sufficient_resolution/) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF.<br/>            <br/>Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.<br/><br/><br/>Η προεπιλεγμένη τιμή είναι **96** .<br/><br/><br/>            Ανάγνωση/εγγραφή **float**. |
| [`draw_slides_frame`](/slides/python-net/el/aspose.slides.export/pdfoptions/draw_slides_frame/) | Αληθές για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`image_transparent_color`](/slides/python-net/el/aspose.slides.export/pdfoptions/image_transparent_color/) | Λαμβάνει ή ορίζει το διαυγές χρώμα της εικόνας. |
| [`apply_image_transparent`](/slides/python-net/el/aspose.slides.export/pdfoptions/apply_image_transparent/) | Εφαρμόζει το καθορισμένο διαυγές χρώμα σε μια εικόνα εάν `true`. |
| [`include_ole_data`](/slides/python-net/el/aspose.slides.export/pdfoptions/include_ole_data/) | Αληθές για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF.<br/>            Ανάγνωση/εγγραφή **bool**. |

### Δείτε επίσης
* κλάση [`PdfOptions`](/slides/python-net/el/aspose.slides.export/pdfoptions)
* κλάση [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)