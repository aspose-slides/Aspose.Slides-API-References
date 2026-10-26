---
title: AudioFrame class
second_title: Aspose.Slides για Python μέσω .NET API αναφορά
description: 
type: docs
url: /el/aspose.slides/audioframe/
---
## AudioFrame κατηγορία

Αντιπροσωπεύει ένα ηχητικό απόσπασμα σε μια διαφάνεια.

**Κληρονομιά:**[`AudioFrame`](/slides/python-net/el/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

Ο τύπος AudioFrame εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/audioframe/is_text_holder/) | Καθορίζει εάν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο για ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/audioframe/placeholder/) | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει placeholder.<br/>            Μόνο για ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/audioframe/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/audioframe/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/audioframe/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/audioframe/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο για ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/audioframe/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3δ εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν 3δ ιδιότητες.<br/>            Μόνο για ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/audioframe/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat το οποίο περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο για ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/audioframe/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο για ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/audioframe/hyperlink_click/) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/audioframe/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για αιώρηση ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/audioframe/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο για ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/audioframe/hidden/) | Καθορίζει εάν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/audioframe/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στο z-order.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος του z-order,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος του z-order.<br/>            Μόνο για ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/audioframe/connection_site_count/) | Επιστρέφει τον αριθμό σημείων σύνδεσης στο σχήμα.<br/>            Μόνο για ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/audioframe/rotation/) | Επιστρέφει ή ορίζει τον αριθμό μοιρών κατά τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/audioframe/x/) | Λαμβάνει ή ορίζει τη συντεταγμένη x της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/audioframe/y/) | Λαμβάνει ή ορίζει τη συντεταγμένη y της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/audioframe/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/audioframe/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/audioframe/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε λειτουργία ασπρόμαυρης προβολής.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/audioframe/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσία αναγνωριστικό που προορίζεται για χρήση από προσθετά ή άλλο κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/audioframe/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για όλη τη ζωή του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφερθεί αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/audioframe/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/audioframe/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/audioframe/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/audioframe/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή «Σημείωση ως διακοσμητικό»<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/audioframe/shape_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο για ανάγνωση [`IPictureFrameLock`](/slides/python-net/el/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/audioframe/is_grouped/) | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο για ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/audioframe/parent_group/) | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο για ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/audioframe/slide/) | Επιστρέφει τη διαφάνεια γονέα ενός σχήματος.<br/>            Μόνο για ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/audioframe/presentation/) | Επιστρέφει την παρουσία γονέα μιας διαφάνειας.<br/>            Μόνο για ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/el/aspose.slides/audioframe/shape_style/) | Επιστρέφει το αντικείμενο στυλ του σχήματος.<br/>            Μόνο για ανάγνωση [`IShapeStyle`](/slides/python-net/el/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/el/aspose.slides/audioframe/shape_type/) | Επιστρέφει ή ορίζει τον τύπο AutoShape για ένα PictureFrame.<br/>            Επιτρέπονται όλα τα στοιχεία του συνόλου [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype), εκτός από όλες τις μορφές γραμμών:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Ανάγνωση/εγγραφή [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/el/aspose.slides/audioframe/adjustments/) | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος.<br/>            Μόνο για ανάγνωση [`IAdjustValueCollection`](/slides/python-net/el/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/el/aspose.slides/audioframe/picture_frame_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο για ανάγνωση [`IPictureFrameLock`](/slides/python-net/el/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/el/aspose.slides/audioframe/picture_format/) | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας.<br/>            Μόνο για ανάγνωση [`IPictureFillFormat`](/slides/python-net/el/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/el/aspose.slides/audioframe/relative_scale_height/) | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί σε 100%.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`relative_scale_width`](/slides/python-net/el/aspose.slides/audioframe/relative_scale_width/) | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί σε 100%.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`is_cameo`](/slides/python-net/el/aspose.slides/audioframe/is_cameo/) | Καθορίζει εάν το PictureFrame είναι αντικείμενο Cameo ή όχι.<br/>            Μόνο για ανάγνωση **bool**. |
| [`audio_cd_start_track`](/slides/python-net/el/aspose.slides/audioframe/audio_cd_start_track/) | Επιστρέφει ή ορίζει έναν δείκτη έναρξης κομματιού.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/el/aspose.slides/audioframe/audio_cd_start_track_time/) | Επιστρέφει ή ορίζει τον χρόνο έναρξης κομματιού.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`audio_cd_end_track`](/slides/python-net/el/aspose.slides/audioframe/audio_cd_end_track/) | Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/el/aspose.slides/audioframe/audio_cd_end_track_time/) | Επιστρέφει ή ορίζει τον χρόνο τελευταίου κομματιού.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`volume`](/slides/python-net/el/aspose.slides/audioframe/volume/) | Επιστρέφει ή ορίζει την ένταση ήχου.<br/>            Ανάγνωση/εγγραφή [`AudioVolumeMode`](/slides/python-net/el/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/el/aspose.slides/audioframe/play_mode/) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου.<br/>            Ανάγνωση/εγγραφή [`AudioPlayModePreset`](/slides/python-net/el/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/el/aspose.slides/audioframe/hide_at_showing/) | Καθορίζει εάν ένα AudioFrame είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`play_loop_mode`](/slides/python-net/el/aspose.slides/audioframe/play_loop_mode/) | Καθορίζει εάν ένας ήχος είναι επαναλαμβανόμενος.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`play_across_slides`](/slides/python-net/el/aspose.slides/audioframe/play_across_slides/) | Καθορίζει εάν ο ήχος αναπαράγεται σε όλες τις διαφάνειες.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`rewind_audio`](/slides/python-net/el/aspose.slides/audioframe/rewind_audio/) | Καθορίζει εάν ο ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`embedded`](/slides/python-net/el/aspose.slides/audioframe/embedded/) | Καθορίζει εάν ένας ήχος είναι ενσωματωμένος σε μια παρουσία.<br/>            Μόνο για ανάγνωση **bool**. |
| [`link_path_long`](/slides/python-net/el/aspose.slides/audioframe/link_path_long/) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που συνδέεται με ένα AudioFrame.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`embedded_audio`](/slides/python-net/el/aspose.slides/audioframe/embedded_audio/) | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου.<br/>            Ανάγνωση/εγγραφή [`IAudio`](/slides/python-net/el/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/el/aspose.slides/audioframe/fade_in_duration/) | Καθορίζει τη διάρκεια σε χιλιοστά του δευτερολέπτου για το αρχικό fade-in των μέσων.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`fade_out_duration`](/slides/python-net/el/aspose.slides/audioframe/fade_out_duration/) | Καθορίζει τη διάρκεια σε χιλιοστά του δευτερολέπτου για το τελικό fade-out των μέσων.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`volume_value`](/slides/python-net/el/aspose.slides/audioframe/volume_value/) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`trim_from_start`](/slides/python-net/el/aspose.slides/audioframe/trim_from_start/) | Καθορίζει τη διάρκεια σε χιλιοστά του δευτερολέπτου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`trim_from_end`](/slides/python-net/el/aspose.slides/audioframe/trim_from_end/) | Καθορίζει τη διάρκεια σε χιλιοστά του δευτερολέπτου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`caption_tracks`](/slides/python-net/el/aspose.slides/audioframe/caption_tracks/) | Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο ήχου.<br/>            Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [`ICaptionsCollection`](/slides/python-net/el/aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια υποτίτλων. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/audioframe/get_image/#) | Επιστρέφει μικρογραφία σχήματος.<br/>            Χρησιμοποιείται προεπιλεγμένα ο τύπος ShapeThumbnailBounds.Shape για τα όρια μικρογραφίας. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει μικρογραφία σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/audioframe/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/audioframe/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια-μαστέρα από την οποία κληρονομεί το τρέχον σχήμα).<br/>            Επιστρέφει None εάν το τρέχον σχήμα δεν κληρονομεί. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/audioframe/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του. |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/audioframe/get_geometry_paths/#) | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την πάνω αριστερή γωνία του σχήματος. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την πάνω αριστερή γωνία του σχήματος.<br/>            Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από σειρά [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την πάνω αριστερή γωνία του σχήματος.<br/>            Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/audioframe/create_shape_elements/#) | Δημιουργεί και επιστρέφει σειρά των στοιχείων του σχήματος. |

### Δείτε επίσης
* κατηγορία [`AudioFrame`](/slides/python-net/el/aspose.slides/audioframe)
* κατηγορία [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* κατηγορία [`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe)
* κατηγορία [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)