---
title: TiffOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/tiffoptions/
---
## TiffOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.

**Κληρονομικότητα:**[`TiffOptions`](/slides/python-net/el/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)

Ο τύπος TiffOptions εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.export/tiffoptions/__init__/#) | Προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/tiffoptions/warning_callback/) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί.<br/>            Ανάγνωση/εγγραφή [`IWarningCallback`](/slides/python-net/el/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/tiffoptions/progress_callback/) | Αντιπροσωπεύει ένα αντικείμενο κλήσης επιστροφής για ενημερώσεις προόδου αποθήκευσης σε ποσοστό.<br/>            Δείτε [`IProgressCallback`](/slides/python-net/el/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/tiffoptions/default_regular_font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/tiffoptions/gradient_style/) | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης.<br/>            Ανάγνωση/εγγραφή [`GradientStyle`](/slides/python-net/el/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/tiffoptions/skip_java_script_links/) | Καθορίζει αν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. <br/>            Ανάγνωση/εγγραφή **bool**. Η προεπιλεγμένη τιμή είναι **false**. |
| [`ink_options`](/slides/python-net/el/aspose.slides.export/tiffoptions/ink_options/) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο.<br/>            Μόνο-ανάγνωση [`IInkOptions`](/slides/python-net/el/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/el/aspose.slides.export/tiffoptions/show_hidden_slides/) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι.<br/>            Η προεπιλεγμένη τιμή είναι `false`. |
| [`image_size`](/slides/python-net/el/aspose.slides.export/tiffoptions/image_size/) | Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF.<br/>            Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογιστούν βάσει του μεγέθους της διαφάνειας της παρουσίασης.<br/>            Ανάγνωση/εγγραφή **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/el/aspose.slides.export/tiffoptions/dpi_x/) | Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`dpi_y`](/slides/python-net/el/aspose.slides.export/tiffoptions/dpi_y/) | Καθορίζει την κατακόρυφη ανάλυση σε κουκκίδες ανά ίντσα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`compression_type`](/slides/python-net/el/aspose.slides.export/tiffoptions/compression_type/) | Καθορίζει τον τύπο συμπίεσης.<br/>            Ανάγνωση/εγγραφή [`TiffCompressionTypes`](/slides/python-net/el/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/el/aspose.slides.export/tiffoptions/pixel_format/) | Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες.<br/>            Ανάγνωση/εγγραφή [`ImagePixelFormat`](/slides/python-net/el/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/el/aspose.slides.export/tiffoptions/slides_layout_options/) | Επιστρέφει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](/slides/python-net/el/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/el/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα.<br/>            Αυτή η επιλογή θα εφαρμοστεί μόνο εάν [`TiffOptions.compression_type`](/slides/python-net/el/aspose.slides.export/tiffoptions/compression_type) <br/>            είναι ορισμένο σε [`TiffCompressionTypes.CCITT4`](/slides/python-net/el/aspose.slides.export/tiffcompressiontypes/CCITT4) ή [`TiffCompressionTypes.CCITT3`](/slides/python-net/el/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Ανάγνωση/εγγραφή [`BlackWhiteConversionMode`](/slides/python-net/el/aspose.slides.export/blackwhiteconversionmode).<br/>            Η προεπιλεγμένη τιμή είναι [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/el/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Δείτε επίσης
* κλάση [`SaveOptions`](/slides/python-net/el/aspose.slides.export/saveoptions)
* κλάση [`TiffOptions`](/slides/python-net/el/aspose.slides.export/tiffoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)