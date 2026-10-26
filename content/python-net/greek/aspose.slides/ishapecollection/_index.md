---
title: IShapeCollection class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/ishapecollection/
---
## IShapeCollection κλάση

Αναπαριστά μια συλλογή σχημάτων.

Ο τύπος IShapeCollection εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`parent_group`](/slides/python-net/el/aspose.slides/ishapecollection/parent_group/) | Αποκτά το αντικείμενο σχήματος γονικής ομάδας για τη συλλογή σχημάτων.<br/>            Μόνο για ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |

Αποκτά το στοιχείο στον καθορισμένο δείκτη.
            Μόνο για ανάγνωση [`IShape`](/slides/python-net/el/aspose.slides/ishape).

## Δείκτης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides/ishapecollection/__getitem__/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Δημιουργεί νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει<br/>            στο τέλος της συλλογής σχημάτων. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/el/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Δημιουργεί νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει<br/>            στο τέλος της συλλογής σχημάτων. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Δημιουργεί νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις,<br/>            και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Δημιουργεί νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις,<br/>            και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/el/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/el/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/el/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/el/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Δημιουργεί ένα νέο πλαίσιο Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων<br/>            στον καθορισμένο δείκτη. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/el/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/el/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το προσθέτει στο τέλος της<br/>            συλλογής σχημάτων. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στον<br/>            καθορισμένο δείκτη. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων<br/>            στον καθορισμένο δείκτη. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/el/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/el/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/el/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της<br/>            συλλογής σχημάτων. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/el/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας<br/>            υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων<br/>            στον καθορισμένο δείκτη. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη<br/>            χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/el/aspose.slides/ishapecollection/to_array/#) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |
| [`to_array(self, start_index, count)`](/slides/python-net/el/aspose.slides/ishapecollection/to_array/#int-int) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στην καθορισμένη περιοχή. |
| [`reorder(self, index, shape)`](/slides/python-net/el/aspose.slides/ishapecollection/reorder/#int-ishape) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |
| [`reorder(self, index, shapes)`](/slides/python-net/el/aspose.slides/ishapecollection/reorder/#int-listishape) | Μετακινεί τα καθορισμένα σχήματα εντός της συλλογής σχημάτων, τοποθετώντας τα ξεκινώντας από το δοσμένο δείκτη. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Δημιουργεί ένα νέο αυτοσχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της<br/>            συλλογής σχημάτων. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/el/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Δημιουργεί ένα νέο αυτοσχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά<br/>            αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Δημιουργεί ένα νέο αυτοσχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη,<br/>            εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Δημιουργεί ένα νέο αυτοσχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη,<br/>            προαιρετικά αρχικοποιώντας το με προεπιλεγμένο στυλ προτύπου. |
| [`add_group_shape(self)`](/slides/python-net/el/aspose.slides/ishapecollection/add_group_shape/#) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων.<br/>            Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωράει τυχόν σχήματα που προστίθενται. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε επιμέρους σχήματα,<br/>            και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της<br/>            συλλογής σχημάτων. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/el/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων,<br/>            προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη,<br/>            εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη,<br/>            προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/el/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων.<br/>            Το νέο σχήμα διατηρεί το πλάτος και το ύψος του `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/el/aspose.slides/ishapecollection/add_clone/#ishape) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων.<br/>            Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.<br/>            Το νέο σχήμα διατηρεί το πλάτος και το ύψος του `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.<br/>            Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/el/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το εισάγει στη συλλογή σχημάτων<br/>            στον καθορισμένο δείκτη. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/el/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της<br/>            συλλογής σχημάτων. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων<br/>            στον καθορισμένο δείκτη. |
| [`index_of(self, shape)`](/slides/python-net/el/aspose.slides/ishapecollection/index_of/#ishape) | Επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/el/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Δημιουργεί ένα νέο αυτόματο σχήμα ορθογώνιο για φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο<br/>            τέλος της συλλογής σχημάτων. |
| [`insert_group_shape(self, index)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_group_shape/#int) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.<br/>            Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωράει τυχόν σχήματα που προστίθενται. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/el/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της<br/>            συλλογής σχημάτων. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή<br/>            σχημάτων στον καθορισμένο δείκτη. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/el/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Δημιουργεί ένα νέο πίνακα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/el/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Δημιουργεί ένα νέο πίνακα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides/ishapecollection/remove_at/#int) | Αφαιρεί το σχήμα στον καθορισμένο δείκτη από τη συλλογή σχημάτων. |
| [`remove(self, shape)`](/slides/python-net/el/aspose.slides/ishapecollection/remove/#ishape) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |
| [`clear(self)`](/slides/python-net/el/aspose.slides/ishapecollection/clear/#) | Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων. |

### Δείτε επίσης
* κλάση [`IShape`](/slides/python-net/el/aspose.slides/ishape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)