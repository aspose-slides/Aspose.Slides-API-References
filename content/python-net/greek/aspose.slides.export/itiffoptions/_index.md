---
title: ITiffOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/itiffoptions/
---
## ITiffOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.

Ο τύπος ITiffOptions εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/el/aspose.slides.export/itiffoptions/image_size/) | Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF.<br/>            Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογιστούν βάσει της τιμής μεγέθους της διαφάνειας της παρουσίασης.<br/>            Ανάγνωση/εγγραφή [`Size`](/slides/python-net/el/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/el/aspose.slides.export/itiffoptions/dpi_x/) | Καθορίζει την οριζόντια ανάλυση σε κουκίδες ανά ίντσα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`dpi_y`](/slides/python-net/el/aspose.slides.export/itiffoptions/dpi_y/) | Καθορίζει την κάθετη ανάλυση σε κουκίδες ανά ίντσα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`show_hidden_slides`](/slides/python-net/el/aspose.slides.export/itiffoptions/show_hidden_slides/) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι.<br/>            Η προεπιλογή είναι `false`. |
| [`compression_type`](/slides/python-net/el/aspose.slides.export/itiffoptions/compression_type/) | Καθορίζει τον τύπο συμπίεσης.<br/>            Ανάγνωση/εγγραφή [`TiffCompressionTypes`](/slides/python-net/el/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/el/aspose.slides.export/itiffoptions/pixel_format/) | Καθορίζει τη μορφή εικονοστοιχείων για τις παραγόμενες εικόνες.<br/>            Ανάγνωση/εγγραφή [`ImagePixelFormat`](/slides/python-net/el/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/el/aspose.slides.export/itiffoptions/slides_layout_options/) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](/slides/python-net/el/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/el/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε εικόνα ασπρόμαυρη.<br/>            Η επιλογή αυτή θα εφαρμοστεί μόνο εάν [`ITiffOptions.compression_type`](/slides/python-net/el/aspose.slides.export/itiffoptions/compression_type) <br/>            ορίζεται στο [`TiffCompressionTypes.CCITT4`](/slides/python-net/el/aspose.slides.export/tiffcompressiontypes/CCITT4) ή [`TiffCompressionTypes.CCITT3`](/slides/python-net/el/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Ανάγνωση/εγγραφή [`BlackWhiteConversionMode`](/slides/python-net/el/aspose.slides.export/blackwhiteconversionmode).<br/>            Η προεπιλογή είναι [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/el/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/el/aspose.slides.export/itiffoptions/ink_options/) | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαχθέν έγγραφο.<br/>            Μόνο ανάγνωση [`IInkOptions`](/slides/python-net/el/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/el/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/el/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/el/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/el/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/el/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)