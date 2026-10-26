---
title: PictureFrame class
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/pictureframe/
---
## PictureFrame κλάση

Αντιπροσωπεύει ένα πλαίσιο με μια εικόνα μέσα.

**Κληρονομικότητα:**[`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

Ο τύπος PictureFrame εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/pictureframe/is_text_holder/) | Καθορίζει εάν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/pictureframe/placeholder/) | Επιστρέφει το σύμβολο κράτησης για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει σύμβολο κράτησης.<br/>            Μόνο ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/pictureframe/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/pictureframe/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/Εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/pictureframe/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/Εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/pictureframe/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/pictureframe/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3d εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d.<br/>            Μόνο ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/pictureframe/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/pictureframe/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/pictureframe/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/Εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/pictureframe/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για hover ποντικιού.<br/>            Ανάγνωση/Εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/pictureframe/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/pictureframe/hidden/) | Καθορίζει εάν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/pictureframe/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στην σειρά z.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z.<br/>            Μόνο ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/pictureframe/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/pictureframe/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z.<br/>            Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/pictureframe/x/) | Λαμβάνει ή ορίζει τη διεύθυνση x της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/pictureframe/y/) | Λαμβάνει ή ορίζει τη διεύθυνση y της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/pictureframe/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/pictureframe/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/pictureframe/black_white_mode/) | Ιδιότητα που καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία προβολής ασπρόμαυρου.<br/>            Ανάγνωση/Εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/pictureframe/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στο παρουσίαση ταυτοποιητή προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/pictureframe/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό ταυτοποιητή περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφερθεί αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/pictureframe/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/pictureframe/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/pictureframe/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/pictureframe/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/pictureframe/shape_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο ανάγνωση [`IPictureFrameLock`](/slides/python-net/el/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/pictureframe/is_grouped/) | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/pictureframe/parent_group/) | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/pictureframe/slide/) | Επιστρέφει τη διαφάνεια γονέα ενός σχήματος.<br/>            Μόνο ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/pictureframe/presentation/) | Επιστρέφει την παρουσίαση γονέα μιας διαφάνειας.<br/>            Μόνο ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/el/aspose.slides/pictureframe/shape_style/) | Επιστρέφει το αντικείμενο στυλ του σχήματος.<br/>            Μόνο ανάγνωση [`IShapeStyle`](/slides/python-net/el/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/el/aspose.slides/pictureframe/shape_type/) | Επιστρέφει ή ορίζει τον τύπο AutoShape για ένα PictureFrame.<br/>            Επιτρέπονται όλα τα στοιχεία του συνόλου [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype), <br/>            εκτός όλων των ειδών γραμμών:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Ανάγνωση/Εγγραφή [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/el/aspose.slides/pictureframe/adjustments/) | Επιστρέφει μια συλλογή των τιμών ρύθμισης του σχήματος.<br/>            Μόνο ανάγνωση [`IAdjustValueCollection`](/slides/python-net/el/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/el/aspose.slides/pictureframe/picture_frame_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο ανάγνωση [`IPictureFrameLock`](/slides/python-net/el/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/el/aspose.slides/pictureframe/picture_format/) | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας.<br/>            Μόνο ανάγνωση [`IPictureFillFormat`](/slides/python-net/el/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/el/aspose.slides/pictureframe/relative_scale_height/) | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`relative_scale_width`](/slides/python-net/el/aspose.slides/pictureframe/relative_scale_width/) | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`is_cameo`](/slides/python-net/el/aspose.slides/pictureframe/is_cameo/) | Καθορίζει εάν το PictureFrame είναι αντικείμενο Cameo ή όχι.<br/>            Μόνο ανάγνωση **bool**. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/pictureframe/get_image/#) | Επιστρέφει μικρογραφία σχήματος.<br/>            Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια μικρογραφίας σχήματος. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει μικρογραφία σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/pictureframe/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι σύμβολο κράτησης. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο σύμβολο κράτησης εάν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολο κράτησης σε ένα καθορισμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/pictureframe/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα σύμβολο κράτησης (σχήμα από τη διάταξη και/ή τη κύρια διαφάνεια από την οποία κληρονόμησε το τρέχον σχήμα).<br/>            Επιστρέφεται None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/pictureframe/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδόσμένο περιεχόμενό του. |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/pictureframe/get_geometry_paths/#) | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με το αριστερό άνω άκρο του σχήματος. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το αριστερό<br/>             άνω άκρο του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από πίνακα [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το αριστερό<br/>             άνω άκρο του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/pictureframe/create_shape_elements/#) | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |

### Δείτε επίσης
* κλάση [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* κλάση [`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)