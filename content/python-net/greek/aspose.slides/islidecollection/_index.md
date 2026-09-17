---
title: ISlideCollection class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/islidecollection/
---
## ISlideCollection κλάση

Αντιπροσωπεύει μια συλλογή διαφανειών.

Ο τύπος ISlideCollection εκθέτει τα ακόλουθα μέλη:

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.
            Μόνο-ανάγνωση [`ISlide`](/slides/python-net/el/aspose.slides/islide).

## Δείκτης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides/islidecollection/__getitem__/) |  |

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/el/aspose.slides/islidecollection/add_clone/#islide) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/el/aspose.slides/islidecollection/add_clone/#islide-isection) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/el/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/el/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Προσθέτει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στο τέλος της συλλογής.<br/>            Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο <br/> master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως <br/> της διάταξης της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη τότε<br/> η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (εάν allowCloneMissingLayout <br/> είναι true) ή θα εκριθεί PptxEditException (εάν allowCloneMissingLayout<br/> είναι false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/el/aspose.slides/islidecollection/insert_clone/#int-islide) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στην καθορισμένη θέση της συλλογής. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/el/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στην καθορισμένη θέση της συλλογής. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/el/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Εισάγει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στην καθορισμένη θέση της συλλογής.<br/>            Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο <br/> master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως <br/> της διάταξης της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη τότε<br/> η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (εάν allowCloneMissingLayout <br/> είναι true) ή θα εκριθεί PptxEditException (εάν allowCloneMissingLayout<br/> είναι false). |
| [`to_array(self)`](/slides/python-net/el/aspose.slides/islidecollection/to_array/#) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες. |
| [`to_array(self, start_index, count)`](/slides/python-net/el/aspose.slides/islidecollection/to_array/#int-int) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος. |
| [`reorder(self, index, slide)`](/slides/python-net/el/aspose.slides/islidecollection/reorder/#int-islide) | Μετακινεί τη διαφάνεια από τη συλλογή στην καθορισμένη θέση. |
| [`reorder(self, index, slides)`](/slides/python-net/el/aspose.slides/islidecollection/reorder/#int-listislide) | Μετακινεί τις διαφάνειες από τη συλλογή στην καθορισμένη θέση.<br/>            Οι διαφάνειες θα τοποθετηθούν ξεκινώντας από το δείκτη με τη σειρά που εμφανίζονται στη λίστα. |
| [`add_from_pdf(self, path)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_pdf/#str) | Δημιουργεί διαφάνειες από το PDF έγγραφο και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Δημιουργεί διαφάνειες από το PDF έγγραφο και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής pdf. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Δημιουργεί διαφάνειες από το PDF έγγραφο και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Δημιουργεί διαφάνειες από το PDF έγγραφο και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_text)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_html/#str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_stream)`](/slides/python-net/el/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [`add_empty_slide(self, layout)`](/slides/python-net/el/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Προσθέτει μια νέα κενή διαφάνεια στο τέλος της συλλογής. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/el/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στην καθορισμένη θέση της συλλογής. |
| [`remove(self, value)`](/slides/python-net/el/aspose.slides/islidecollection/remove/#islide) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides/islidecollection/remove_at/#int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [`index_of(self, slide)`](/slides/python-net/el/aspose.slides/islidecollection/index_of/#islide) | Επιστρέφει έναν δείκτη της καθορισμένης διαφάνειας στη συλλογή. |

### Δείτε επίσης
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)