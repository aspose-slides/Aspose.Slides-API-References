---
title: VideoFrame class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/videoframe/
---
## VideoFrame κλάση

Represents a video clip on a slide.

**Inheritance:**[`VideoFrame`](/slides/python-net/el/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

The VideoFrame type exposes the following members:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/videoframe/is_text_holder/) | Καθορίζει εάν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο για ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/videoframe/placeholder/) | Επιστρέφει τον placeholder για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει placeholder.<br/>            Μόνο για ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/videoframe/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/videoframe/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/videoframe/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σ_shape.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/videoframe/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο για ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/videoframe/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3D εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3D.<br/>            Μόνο για ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/videoframe/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο για ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/videoframe/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο για ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/videoframe/hyperlink_click/) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/videoframe/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για hover του ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/videoframe/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμου.<br/>            Μόνο για ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/videoframe/hidden/) | Καθορίζει εάν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/videoframe/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στην κλίμακα z-order.<br/>            Shapes[0] επιστρέφει το σχήμα στο βάθος του z-order,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστά τμήμα του z-order.<br/>            Μόνο για ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/videoframe/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο για ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/videoframe/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τον οποίο το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z.<br/>            Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδηλώνει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/videoframe/x/) | Λαμβάνει ή ορίζει την x-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/videoframe/y/) | Λαμβάνει ή ορίζει την y-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/videoframe/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/videoframe/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/videoframe/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης προβολής.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/videoframe/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση, ταυτοποιητή που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Δεδομένου ότι αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/videoframe/office_interop_shape_id/) | Επιστρέφει έναν μοναδικό ταυτοποιητή περιορισμένο στη διαφάνεια που παραμένει σταθερός κατά τη διάρκεια της ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα interop να κάνει αξιόπιστη αναφορά στο σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/videoframe/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/videoframe/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/videoframe/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή τιμή συμβολοσειράς εάν χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/videoframe/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/videoframe/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο για ανάγνωση [`IPictureFrameLock`](/slides/python-net/el/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/videoframe/is_grouped/) | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο για ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/videoframe/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο για ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/videoframe/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο για ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/videoframe/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο για ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/el/aspose.slides/videoframe/shape_style/) | Επιστρέφει το αντικείμενο στυλ του σχήματος.<br/>            Μόνο για ανάγνωση [`IShapeStyle`](/slides/python-net/el/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/el/aspose.slides/videoframe/shape_type/) | Επιστρέφει ή ορίζει τον τύπο AutoShape για ένα PictureFrame.<br/>            Επιτρέπονται όλα τα στοιχεία του συνόλου [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype), <br/>            εκτός όλων των τύπων γραμμών:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Ανάγνωση/εγγραφή [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/el/aspose.slides/videoframe/adjustments/) | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος.<br/>            Μόνο για ανάγνωση [`IAdjustValueCollection`](/slides/python-net/el/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/el/aspose.slides/videoframe/picture_frame_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο για ανάγνωση [`IPictureFrameLock`](/slides/python-net/el/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/el/aspose.slides/videoframe/picture_format/) | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας.<br/>            Μόνο για ανάγνωση [`IPictureFillFormat`](/slides/python-net/el/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/el/aspose.slides/videoframe/relative_scale_height/) | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σε σχέση με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί σε 100%.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`relative_scale_width`](/slides/python-net/el/aspose.slides/videoframe/relative_scale_width/) | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σε σχέση με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί σε 100%.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`is_cameo`](/slides/python-net/el/aspose.slides/videoframe/is_cameo/) | Καθορίζει εάν το PictureFrame είναι αντικείμενο Cameo ή όχι.<br/>            Μόνο για ανάγνωση **bool**. |
| [`rewind_video`](/slides/python-net/el/aspose.slides/videoframe/rewind_video/) | Καθορίζει εάν ένα βίντεο επαναλαμβάνεται αυτόματα από την αρχή<br/>            μόλις το βίντεο ολοκληρώσει την αναπαραγωγή.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`play_loop_mode`](/slides/python-net/el/aspose.slides/videoframe/play_loop_mode/) | Καθορίζει εάν ένα βίντεο είναι σε βρόχο.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`hide_at_showing`](/slides/python-net/el/aspose.slides/videoframe/hide_at_showing/) | Καθορίζει εάν το VideoFrame είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`volume`](/slides/python-net/el/aspose.slides/videoframe/volume/) | Επιστρέφει ή ορίζει την ένταση ήχου.<br/>            Ανάγνωση/εγγραφή [`AudioVolumeMode`](/slides/python-net/el/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/el/aspose.slides/videoframe/play_mode/) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο.<br/>            Ανάγνωση/εγγραφή [`VideoPlayModePreset`](/slides/python-net/el/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/el/aspose.slides/videoframe/full_screen_mode/) | Καθορίζει εάν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`link_path_long`](/slides/python-net/el/aspose.slides/videoframe/link_path_long/) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`embedded_video`](/slides/python-net/el/aspose.slides/videoframe/embedded_video/) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο.<br/>            Ανάγνωση/εγγραφή [`IVideo`](/slides/python-net/el/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/el/aspose.slides/videoframe/trim_from_start/) | Έναρξη περικοπής [ms] |
| [`trim_from_end`](/slides/python-net/el/aspose.slides/videoframe/trim_from_end/) | Τέλος περικοπής [ms] |
| [`caption_tracks`](/slides/python-net/el/aspose.slides/videoframe/caption_tracks/) | Λαμβάνει τη συλλογή των κλειστών υποτίτλων που συνδέονται με το πλαίσιο βίντεο.<br/>             Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [`ICaptionsCollection`](/slides/python-net/el/aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια υποτίτλων. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/videoframe/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια της μικρογραφίας. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/videoframe/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Προσθέτει νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/videoframe/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη μητρική διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφεται None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/videoframe/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδομένο του περιεχόμενο. |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/videoframe/get_geometry_paths/#) | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικά με την επάνω αριστερή γωνία του σχήματος. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικά με την επάνω αριστερή γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικά με την επάνω αριστερή γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/videoframe/create_shape_elements/#) | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |

### Δείτε επίσης
* κλάση [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* κλάση [`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* κλάση [`VideoFrame`](/slides/python-net/el/aspose.slides/videoframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)