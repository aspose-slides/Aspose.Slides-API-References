---
title: Presentation class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/presentation/
---
## κλάση Presentation

Αντιπροσωπεύει μια παρουσίαση Microsoft PowerPoint.

Ο τύπος Presentation εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides/presentation/__init__/#) | Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από το μηδέν.<br/>            Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια. |
| [`__init__(self, load_options)`](/slides/python-net/el/aspose.slides/presentation/__init__/#loadoptions) | Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από το μηδέν.<br/>            Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια. |
| [`__init__(self, stream)`](/slides/python-net/el/aspose.slides/presentation/__init__/#iorawiobase) | Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για ανάγνωση μιας υπάρχουσας Presentation. |
| [`__init__(self, stream, load_options)`](/slides/python-net/el/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για ανάγνωση μιας υπάρχουσας Presentation. |
| [`__init__(self, file)`](/slides/python-net/el/aspose.slides/presentation/__init__/#str) | Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή του αρχείου προέλευσης από την οποία<br/>             διαβάζονται τα περιεχόμενα της Presentation. |
| [`__init__(self, file, load_options)`](/slides/python-net/el/aspose.slides/presentation/__init__/#str-loadoptions) | Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή του αρχείου προέλευσης από την οποία<br/>            διαβάζονται τα περιεχόμενα της Presentation. |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/el/aspose.slides/presentation/current_date_time/) | Επιστρέφει ή ορίζει ημερομηνία και ώρα που θα αντικαταστήσουν το περιεχόμενο των πεδίων datetime.<br/>            Η ώρα δημιουργίας αυτού του αντικειμένου Presentation από προεπιλογή.<br/>            Ανάγνωση/εγγραφή **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/el/aspose.slides/presentation/header_footer_manager/) | Επιστρέφει τον τρέχοντα διαχειριστή HeaderFooter.<br/>            Μόνο για ανάγνωση [`IPresentationHeaderFooterManager`](/slides/python-net/el/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/el/aspose.slides/presentation/protection_manager/) | Λαμβάνει τον διαχειριστή των δικαιωμάτων για αυτήν την παρουσίαση.<br/>            Μόνο για ανάγνωση [`IProtectionManager`](/slides/python-net/el/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/el/aspose.slides/presentation/slides/) | Επιστρέφει μια λίστα με όλες τις διαφάνειες που ορίζονται στην παρουσίαση.<br/el/>            Μόνο για ανάγνωση [`ISlideCollection`](/slides/python-net/el/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/el/aspose.slides/presentation/sections/) | Επιστρέφει μια λίστα με όλα τα τμήματα διαφανειών που ορίζονται στην παρουσίαση.<br/>            Μόνο για ανάγνωση [`ISectionCollection`](/slides/python-net/el/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/el/aspose.slides/presentation/slide_size/) | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας.<br/>            Μόνο για ανάγνωση [`ISlideSize`](/slides/python-net/el/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/el/aspose.slides/presentation/notes_size/) | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων.<br/>            Μόνο για ανάγνωση [`INotesSize`](/slides/python-net/el/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/el/aspose.slides/presentation/layout_slides/) | Επιστρέφει μια λίστα με όλες τις διαφάνειες διάταξης που ορίζονται στην παρουσίαση.<br/>            Μόνο για ανάγνωση [`IGlobalLayoutSlideCollection`](/slides/python-net/el/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/el/aspose.slides/presentation/masters/) | Επιστρέφει μια λίστα με όλες τις κύριες διαφάνειες (master) που ορίζονται στην παρουσίαση.<br/>            Μόνο για ανάγνωση [`IMasterSlideCollection`](/slides/python-net/el/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/el/aspose.slides/presentation/master_notes_slide_manager/) | Επιστρέφει τον διαχειριστή κύριων σημειώσεων.<br/>            Μόνο για ανάγνωση [`IMasterNotesSlideManager`](/slides/python-net/el/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/el/aspose.slides/presentation/master_handout_slide_manager/) | Επιστρέφει τον διαχειριστή κύριου φυλλαδίου.<br/>            Μόνο για ανάγνωση [`IMasterHandoutSlideManager`](/slides/python-net/el/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/el/aspose.slides/presentation/fonts_manager/) | Επιστρέφει το διαχειριστή γραμματοσειρών.<br/>            Μόνο για ανάγνωση [`IFontsManager`](/slides/python-net/el/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/el/aspose.slides/presentation/default_text_style/) | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα.<br/>            Μόνο για ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/el/aspose.slides/presentation/comment_authors/) | Επιστρέφει τη συλλογή των συγγραφέων σχολίων.<br/>            Μόνο για ανάγνωση [`ICommentAuthorCollection`](/slides/python-net/el/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/el/aspose.slides/presentation/document_properties/) | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου.<br/>            Μόνο για ανάγνωση [`IDocumentProperties`](/slides/python-net/el/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/el/aspose.slides/presentation/images/) | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση.<br/>            Μόνο για ανάγνωση [`IImageCollection`](/slides/python-net/el/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/el/aspose.slides/presentation/audios/) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση.<br/>            Μόνο για ανάγνωση [`IAudioCollection`](/slides/python-net/el/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/el/aspose.slides/presentation/videos/) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση.<br/>            Μόνο για ανάγνωση [`IVideoCollection`](/slides/python-net/el/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/el/aspose.slides/presentation/slide_show_settings/) | Επιστρέφει τις ρυθμίσεις παρουσίασης διαφανειών για την παρουσίαση. |
| [`digital_signatures`](/slides/python-net/el/aspose.slides/presentation/digital_signatures/) | Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιούνται για την υπογραφή της παρουσίασης.<br/>            Μόνο για ανάγνωση [`IDigitalSignatureCollection`](/slides/python-net/el/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/el/aspose.slides/presentation/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/el/aspose.slides/presentation/all_custom_xml_parts/) | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση.<br/>            Μόνο για ανάγνωση [`ICustomXmlPart`](/slides/python-net/el/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/el/aspose.slides/presentation/vba_project/) | Λαμβάνει ή ορίζει το έργο VBA με μακροεντολές παρουσίασης.<br/>            Ανάγνωση/εγγραφή [`IVbaProject`](/slides/python-net/el/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/presentation/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (εκτός από master, layout, notes).<br/>            Μόνο για ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/el/aspose.slides/presentation/view_properties/) | Λαμβάνει τις ιδιότητες προβολής για ολόκληρη την παρουσίαση.<br/>            Μόνο για ανάγνωση [`IViewProperties`](/slides/python-net/el/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/el/aspose.slides/presentation/first_slide_number/) | Αντιπροσωπεύει τον αριθμό της πρώτης διαφάνειας στην παρουσίαση |
| [`sensitivity_labels`](/slides/python-net/el/aspose.slides/presentation/sensitivity_labels/) | Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης.<br/>            Μόνο για ανάγνωση [`ISensitivityLabelCollection`](/slides/python-net/el/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/el/aspose.slides/presentation/source_format/) | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση.<br/>            Μόνο για ανάγνωση [`SourceFormat`](/slides/python-net/el/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/el/aspose.slides/presentation/master_theme/) | Επιστρέφει το κύριο θέμα.<br/>            Μόνο για ανάγνωση [`IMasterTheme`](/slides/python-net/el/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/el/aspose.slides/presentation/presentation/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/el/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή. |
| [`save(self, stream, format)`](/slides/python-net/el/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή. |
| [`save(self, fname, format, options)`](/slides/python-net/el/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/el/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [`save(self, options)`](/slides/python-net/el/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αναπαριστούν σήμανση XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/el/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/el/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας. |
| [`save(self, stream, slides, format)`](/slides/python-net/el/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/el/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας. |
| [`get_images(self, options)`](/slides/python-net/el/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Επιστρέφει αντικείμενα Image για όλες τις διαφάνειες μιας παρουσίασης. |
| [`get_images(self, options, slides)`](/slides/python-net/el/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |
| [`get_images(self, options, image_size)`](/slides/python-net/el/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/el/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/el/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/el/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`get_slide_by_id(self, id)`](/slides/python-net/el/aspose.slides/presentation/get_slide_by_id/#int) | Επιστρέφει ένα Slide, MasterSlide ή LayoutSlide βάσει Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/presentation/join_portions_with_same_formatting/#) | Ενώνει τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/el/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/el/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/el/aspose.slides/presentation/replace_regex/#str-str) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο κείμενο. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)