---
title: ISlide class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/islide/
---
## ISlide κλάση

Αντιπροσωπεί μια διαφάνεια σε μια παρουσίαση.

Ο τύπος ISlide εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/el/aspose.slides/islide/header_footer_manager/) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας.<br/>            Μόνο ανάγνωση [`ISlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/el/aspose.slides/islide/slide_number/) | Επιστρέφει έναν αριθμό διαφάνειας.<br/>            Ο δείκτης της διαφάνειας στη συλλογή [`IPresentation.slides`](/slides/python-net/el/aspose.slides/ipresentation/slides) είναι πάντα ίσος με SlideNumber - 1.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`hidden`](/slides/python-net/el/aspose.slides/islide/hidden/) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της προβολής διαφανειών.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`layout_slide`](/slides/python-net/el/aspose.slides/islide/layout_slide/) | Επιστρέφει ή ορίζει τη διάταξη διαφάνειας για την τρέχουσα διαφάνεια.<br/>            Ανάγνωση/εγγραφή [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/el/aspose.slides/islide/notes_slide_manager/) | Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και την αφαίρεσή της.<br/>            Μόνο ανάγνωση [`INotesSlideManager`](/slides/python-net/el/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/el/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/el/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/el/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/el/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/el/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/el/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/el/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/el/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/el/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/el/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/el/aspose.slides/islide/theme_manager/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/islide/get_image/#float-float) | Επιστρέφει ένα αντικείμενο εικόνας με προσαρμοσμένη κλίμακα. |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/islide/get_image/#) | Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους). |
| [`get_image(self, image_size)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposepydrawingsize) | Επιστρέφει ένα αντικείμενο εικόνας με συγκεκριμένο μέγεθος. |
| [`get_image(self, options)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Επιστρέφει ένα αντικείμενο Thumbnail tiff bitmap με συγκεκριμένες παραμέτρους. |
| [`get_image(self, options)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Επιστρέφει ένα αντικείμενο Thumbnail Bitmap. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Επιστρέφει ένα αντικείμενο Thumbnail Bitmap με προσαρμοσμένη κλίμακα. |
| [`get_image(self, options, image_size)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Επιστρέφει ένα αντικείμενο Thumbnail Bitmap με συγκεκριμένο μέγεθος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/islide/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/el/aspose.slides/islide/get_slide_comments/#icommentauthor) | Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |
| [`write_as_emf(self, stream)`](/slides/python-net/el/aspose.slides/islide/write_as_emf/#iorawiobase) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [`remove(self)`](/slides/python-net/el/aspose.slides/islide/remove/#) | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [`reset(self)`](/slides/python-net/el/aspose.slides/islide/reset/#) | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στο LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/el/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/el/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/el/aspose.slides/islide/create_theme_effective/#) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)