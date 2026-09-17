---
title: Connector class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/connector/
---
## Κλάση Connector

Αντιπροσωπεύει έναν σύνδεσμο.

**Κληρονομικότητα:**[`Connector`](/slides/python-net/el/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

Ο τύπος Connector εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/connector/is_text_holder/) | Καθορίζει εάν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/connector/placeholder/) | Επιστρέφει το χώρο κράτησης για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει χώρο κράτησης.<br/>            Μόνο ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/connector/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/connector/raw_frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/connector/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/connector/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες διαμόρφωσης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/connector/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3δ εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3δ.<br/>            Μόνο ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/connector/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/connector/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/connector/hyperlink_click/) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/connector/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/connector/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσύνδεσμου.<br/>            Μόνο ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/connector/hidden/) | Καθορίζει εάν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/connector/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στην σειρά z.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z.<br/>            Μόνο ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/connector/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/connector/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z.<br/>            Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδηλώνει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/connector/x/) | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/connector/y/) | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/connector/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/connector/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/connector/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε λειτουργία εμφάνισης ασπρόμαυρου.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/connector/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/connector/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή στον κώδικα διαλειτουργικότητας να αναφερθεί αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/connector/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/connector/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/connector/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή τιμή συμβολοσειράς εάν χρειαστεί.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/connector/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/connector/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο ανάγνωση [`IConnectorLock`](/slides/python-net/el/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/connector/is_grouped/) | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/connector/parent_group/) | Επιστρέφει το αντικείμενο γονέα GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/connector/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/connector/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/el/aspose.slides/connector/shape_style/) | Επιστρέφει το αντικείμενο στυλ του σχήματος.<br/>            Μόνο ανάγνωση [`IShapeStyle`](/slides/python-net/el/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/el/aspose.slides/connector/shape_type/) | Επιστρέφει ή ορίζει τον τύπο AutoShape.<br/>            Ανάγνωση/εγγραφή [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/el/aspose.slides/connector/adjustments/) | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος.<br/>            Μόνο ανάγνωση [`IAdjustValueCollection`](/slides/python-net/el/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/el/aspose.slides/connector/connector_lock/) | Επιστρέφει τις κλειδώσεις του συνδέσμου.<br/>            Μόνο ανάγνωση [`IConnectorLock`](/slides/python-net/el/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/el/aspose.slides/connector/start_shape_connected_to/) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του συνδέσμου.<br/>            Ανάγνωση/εγγραφή [`IShape`](/slides/python-net/el/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/el/aspose.slides/connector/end_shape_connected_to/) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το άκρο του συνδέσμου.<br/>            Ανάγνωση/εγγραφή [`IShape`](/slides/python-net/el/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/el/aspose.slides/connector/start_shape_connection_site_index/) | Επιστρέφει ή ορίζει τον δείκτη σημείου σύνδεσης για το αρχικό σχήμα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/el/aspose.slides/connector/end_shape_connection_site_index/) | Επιστρέφει ή ορίζει τον δείκτη σημείου σύνδεσης για το τελικό σχήμα.<br/>            Ανάγνωση/εγγραφή **int**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/connector/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια της μικρογραφίας. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/connector/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/connector/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/connector/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/connector/get_base_placeholder/#) | Επιστρέφει ένα βασικό shape placeholder (shape από τη διάταξη και/ή τη διαφάνεια-μαστέχα από την οποία κληρονομεί το τρέχον σχήμα).<br/>            Επιστρέφει None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/connector/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδιδόμενο περιεχόμενό του. |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/connector/get_geometry_paths/#) | Επιστρέφει ένα αντίγραφο του μονοπατιού του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή άνω γωνία του σχήματος. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/connector/set_geometry_path/#igeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή<br/>             άνω γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα του [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή<br/>             άνω γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/connector/create_shape_elements/#) | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| [`reroute(self)`](/slides/python-net/el/aspose.slides/connector/reroute/#) | Αναδρομολογεί τον σύνδεσμο ώστε να ακολουθεί τη συντομότερη δυνατή διαδρομή μεταξύ των σχημάτων που συνδέει. |

### Δείτε επίσης
* κλάση [`Connector`](/slides/python-net/el/aspose.slides/connector)
* κλάση [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)