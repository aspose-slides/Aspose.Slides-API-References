---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides για Python μέσω .NET αναφορά API
description: 
type: docs
url: /el/aspose.slides.export/embedallfontshtmlcontroller/
---
## Τάξη EmbedAllFontsHtmlController

Η κλάση ελεγκτή μορφοποίησης που χρησιμοποιείται για την ενσωμάτωση όλων των γραμματοσειρών παρουσίασης σε μορφή WOFF.

Ο τύπος EmbedAllFontsHtmlController αποκαλύπτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Δημιουργεί ένα νέο αντικείμενο |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Δημιουργεί ένα νέο αντικείμενο |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Καλείται για τη γραφή της κεφαλίδας του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Καλείται για τη γραφή του υποσέλιδου του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Καλείται για τη γραφή της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Καλείται για τη γραφή του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Καλείται πριν από τη απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράφει κάτι στον γεννήτρια, η τρέχουσα παραγωγή εικόνας διαφάνειας θα ολοκληρωθεί, το προστεθέν τμήμα html θα εισαχθεί και μια νέα εικόνα θα ξεκινήσει επάνω στην προηγούμενη. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Καλείται πριν από τη απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράφει κάτι στον γεννήτρια, η τρέχουσα παραγωγή εικόνας διαφάνειας θα ολοκληρωθεί, το προστεθέν τμήμα html θα εισαχθεί και μια νέα εικόνα θα ξεκινήσει επάνω στην προηγούμενη. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Γράφει όλες τις γραμματοσειρές που περιέχονται στο [`Presentation`](/slides/python-net/el/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/el/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Γράφει τα δεδομένα ως base64 στο ίδιο το έγγραφο HTML |

### See Also
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)