---
title: SlideCollection class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/slidecollection/
---
## SlideCollection κλάση

Αντιπροσωπεύει μια συλλογή διαφανειών.

Ο τύπος SlideCollection εκθέτει τα παρακάτω μέλη:

Gets the element at the specified index.
            Μόνο-ανάγνωση [`Slide`](/slides/python-net/el/aspose.slides/slide).

## Indexer

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides/slidecollection/__getitem__/) |  |

## Methods

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/el/aspose.slides/slidecollection/add_clone/#islide) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/el/aspose.slides/slidecollection/add_clone/#islide-isection) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της καθορισμένης ενότητας. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/el/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/el/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης πηγαίας διαφάνειας στο τέλος της συλλογής.<br/>            Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο <br/>            master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως <br/>            της διάταξης της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη τότε<br/>            η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout <br/>            είναι true) ή θα εκτοξεύσει PptxEditException (αν allowCloneMissingLayout<br/>            είναι false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/el/aspose.slides/slidecollection/insert_clone/#int-islide) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/el/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/el/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης πηγαίας διαφάνειας στη καθορισμένη θέση της συλλογής.<br/>            Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο <br/>            master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως <br/>            της διάταξης της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη τότε<br/>            η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout <br/>            είναι true) ή θα εκτοξεύσει PptxEditException (αν allowCloneMissingLayout<br/>            είναι false). |
| [`to_array(self)`](/slides/python-net/el/aspose.slides/slidecollection/to_array/#) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες. |
| [`to_array(self, start_index, count)`](/slides/python-net/el/aspose.slides/slidecollection/to_array/#int-int) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος.<br/>            Δείκτης της πρώτης διαφάνειας προς προσθήκη. Αριθμός διαφανειών προς προσθήκη. |
| [`reorder(self, index, slide)`](/slides/python-net/el/aspose.slides/slidecollection/reorder/#int-islide) | Μετακινεί τη διαφάνεια από τη συλλογή στη καθορισμένη θέση. |
| [`reorder(self, index, slides)`](/slides/python-net/el/aspose.slides/slidecollection/reorder/#int-listislide) | Μετακινεί διαφάνειες από τη συλλογή στη καθορισμένη θέση.<br/>            Οι διαφάνειες θα τοποθετηθούν ξεκινώντας από τον δείκτη με τη σειρά που εμφανίζονται στη λίστα. |
| [`add_from_pdf(self, path)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_pdf/#str) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής pdf. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_text)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_html/#str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`add_from_html(self, html_stream)`](/slides/python-net/el/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/el/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [`add_empty_slide(self, layout)`](/slides/python-net/el/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Προσθέτει μια νέα κενή διαφάνεια στο τέλος της συλλογής. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/el/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |
| [`remove(self, value)`](/slides/python-net/el/aspose.slides/slidecollection/remove/#islide) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides/slidecollection/remove_at/#int) | Αφαιρεί το στοιχείο στη συγκεκριμένη θέση από τη συλλογή. |
| [`index_of(self, slide)`](/slides/python-net/el/aspose.slides/slidecollection/index_of/#islide) | Επιστρέφει το δείκτη της συγκεκριμένης διαφάνειας στη συλλογή. |

### Δείτε επίσης
* κλάση [`Slide`](/slides/python-net/el/aspose.slides/slide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)