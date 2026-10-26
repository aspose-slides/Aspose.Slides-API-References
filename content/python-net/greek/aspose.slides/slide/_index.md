---
title: Slide class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/slide/
---
## Slide κλάση

Αντιπροσωπεύει μια διαφάνεια σε μια παρουσίαση.

**Κληρονομικότητα:**[`Slide`](/slides/python-net/el/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/el/aspose.slides/baseslide)

Ο τύπος Slide εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/el/aspose.slides/slide/shapes/) | Επιστρέφει τα σχήματα μιας διαφάνειας.<br/>            Μόνο για ανάγνωση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/el/aspose.slides/slide/controls/) | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια.<br/>            Μόνο για ανάγνωση [`IControlCollection`](/slides/python-net/el/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/el/aspose.slides/slide/name/) | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`slide_id`](/slides/python-net/el/aspose.slides/slide/slide_id/) | Επιστρέφει το αναγνωριστικό (ID) μιας διαφάνειας.<br/>            Μόνο για ανάγνωση **int**. |
| [`custom_data`](/slides/python-net/el/aspose.slides/slide/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/el/aspose.slides/slide/timeline/) | Επιστρέφει το αντικείμενο χρονοδιάγραμμα κίνησης.<br/>            Μόνο για ανάγνωση [`IAnimationTimeLine`](/slides/python-net/el/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/el/aspose.slides/slide/slide_show_transition/) | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες σχετικά με<br/>            το πώς η συγκεκριμένη διαφάνεια προχωράει κατά τη διάρκεια της παρουσίασης.<br/>            Μόνο για ανάγνωση [`ISlideShowTransition`](/slides/python-net/el/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/el/aspose.slides/slide/background/) | Επιστρέφει το φόντο της διαφάνειας.<br/>            Μόνο για ανάγνωση [`IBackground`](/slides/python-net/el/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/slide/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους.<br/>            Μόνο για ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/el/aspose.slides/slide/show_master_shapes/) | Καθορίζει εάν τα σχήματα στη διαφάνεια master θα εμφανίζονται στις διαφάνειες ή όχι.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`presentation`](/slides/python-net/el/aspose.slides/slide/presentation/) | Επιστρέφει τη διεπαφή IPresentation.<br/>            Μόνο για ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/el/aspose.slides/slide/header_footer_manager/) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας.<br/>            Μόνο για ανάγνωση [`ISlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/el/aspose.slides/slide/theme_manager/) | Επιστρέφει τον διαχειριστή υπερκαλύπτοντος θέματος.<br/>            Μόνο για ανάγνωση [`IOverrideThemeManager`](/slides/python-net/el/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/el/aspose.slides/slide/slide_number/) | Επιστρέφει έναν αριθμό διαφάνειας.<br/>            Ο δείκτης της διαφάνειας στη συλλογή [`Presentation.slides`](/slides/python-net/el/aspose.slides/presentation/slides) είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber.<br/>            Ανάγνωση/Εγγραφή **int**. |
| [`hidden`](/slides/python-net/el/aspose.slides/slide/hidden/) | Καθορίζει εάν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`layout_slide`](/slides/python-net/el/aspose.slides/slide/layout_slide/) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια.<br/>            Ανάγνωση/Εγγραφή [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/el/aspose.slides/slide/notes_slide_manager/) | Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και αφαίρεσή της.<br/>            Μόνο για ανάγνωση [`INotesSlideManager`](/slides/python-net/el/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/el/aspose.slides/slide/slide/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/slide/join_portions_with_same_formatting/#) | Σανενώνει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/el/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Σανενώνει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/slide/get_image/#float-float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλίμακα. |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/slide/get_image/#) | Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους). |
| [`get_image(self, image_size)`](/slides/python-net/el/aspose.slides/slide/get_image/#asposeslidessize) | Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος. |
| [`get_image(self, options)`](/slides/python-net/el/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Επιστρέφει ένα αντικείμενο εικόνας Thumbnail tiff με συγκεκριμένες παραμέτρους. |
| [`get_image(self, options)`](/slides/python-net/el/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Επιστρέφει ένα αντικείμενο Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλίμακα. |
| [`get_image(self, options, image_size)`](/slides/python-net/el/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/slide/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [`equals(self, slide)`](/slides/python-net/el/aspose.slides/slide/equals/#ibaseslide) | Καθορίζει εάν τα δύο αντικείμενα IBaseSlide είναι ίσα.<br/>            Η επιστρεφόμενη τιμή υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου.<br/>            Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, η κίνηση και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστικών, π.χ. SlideId και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στην θέση κράτησης ημερομηνίας. |
| [`create_theme_effective(self)`](/slides/python-net/el/aspose.slides/slide/create_theme_effective/#) | Επιστρέφει ένα ενεργό θέμα για αυτή τη διαφάνεια. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/el/aspose.slides/slide/find_shape_by_alt_text/#str) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [`write_as_emf(self, stream)`](/slides/python-net/el/aspose.slides/slide/write_as_emf/#iorawiobase) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [`remove(self)`](/slides/python-net/el/aspose.slides/slide/remove/#) | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [`reset(self)`](/slides/python-net/el/aspose.slides/slide/reset/#) | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στη LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/el/aspose.slides/slide/get_slide_comments/#icommentauthor) | Επιστρέφει όλα τα σχόλια της διαφάνειας που προστέθηκαν από συγκεκριμένο συντάκτη. |

### Δείτε επίσης
* κλάση [`BaseSlide`](/slides/python-net/el/aspose.slides/baseslide)
* κλάση [`Slide`](/slides/python-net/el/aspose.slides/slide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)