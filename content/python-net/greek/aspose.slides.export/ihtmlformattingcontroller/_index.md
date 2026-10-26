---
title: IHtmlFormattingController class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController κλάση

Ελέγχει τη δημιουργία αρχείου html.

Ο τύπος IHtmlFormattingController εκθέτει τα παρακάτω μέλη:

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/el/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Καλείται για τη δημιουργία της κεφαλίδας του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/el/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Καλείται για τη δημιουργία του υποσέλιδου του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/el/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Καλείται για τη δημιουργία της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/el/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Καλείται για τη δημιουργία του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/el/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράψει κάτι στον δημιουργό, η δημιουργία της εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, το προστεθέν τμήμα html θα ενσωματωθεί και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/el/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράψει κάτι στον δημιουργό, η δημιουργία της εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, το προστεθέν τμήμα html θα ενσωματωθεί και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη. |


### Δείτε επίσης
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)