---
title: GeometryShape class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/geometryshape/
---
## GeometryShape κλάση

Represents the parent class for all geometric shapes.

**Inheritance:**[`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

The GeometryShape type exposes the following members:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/geometryshape/is_text_holder/) | Καθορίζει αν το σχήμα είναι TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/geometryshape/placeholder/) | Επιστρέφει το σύμβολο θέση για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει σύμβολο θέση.<br/>            Read-only [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/geometryshape/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Read-only [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/geometryshape/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος.<br/>            Read/write [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/geometryshape/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος.<br/>            Read/write [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/geometryshape/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμών για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Read-only [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/geometryshape/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3d εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/geometryshape/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Read-only [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/geometryshape/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Read-only [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/geometryshape/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού.<br/>            Read/write [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/geometryshape/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα του ποντικιού.<br/>            Read/write [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/geometryshape/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/geometryshape/hidden/) | Καθορίζει αν το σχήμα είναι κρυφό.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/geometryshape/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στην z-σειρά.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της z-σειράς,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της z-σειράς.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/geometryshape/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/geometryshape/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/el/aspose.slides/geometryshape/x/) | Ανακτά ή ορίζει την x-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε πόντους.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/el/aspose.slides/geometryshape/y/) | Ανακτά ή ορίζει την y-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε πόντους.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/el/aspose.slides/geometryshape/width/) | Ανακτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε πόντους.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/el/aspose.slides/geometryshape/height/) | Ανακτά ή ορίζει το ύψος του σχήματος, μετρημένο σε πόντους.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/geometryshape/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα εμφανίζεται ένα σχήμα σε λειτουργία ασπρόμαυρης απεικόνισης.<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/geometryshape/unique_id/) | Επιστρέφει έναν εσωτερικό, στο πλαίσιο της παρουσίασης, ταυτότητα που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Δεδομένου ότι αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Read-only **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/geometryshape/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στο διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο.<br/>            Read-only **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/geometryshape/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/geometryshape/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/el/aspose.slides/geometryshape/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/geometryshape/is_decorative/) | Ανακτά ή ορίζει την επιλογή 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/geometryshape/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Read-only [`IBaseShapeLock`](/slides/python-net/el/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/geometryshape/is_grouped/) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/geometryshape/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Read-only [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/geometryshape/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Read-only [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/geometryshape/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Read-only [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/el/aspose.slides/geometryshape/shape_style/) | Επιστρέφει το αντικείμενο στυλ του σχήματος.<br/>            Read-only [`IShapeStyle`](/slides/python-net/el/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type/) | Επιστρέφει ή ορίζει τον τύπο προεπιλογής γεωμετρίας.<br/>            Σημείωση: με την αλλαγή της τιμής όλες οι τιμές προσαρμογής θα επαναρυθμιστούν στις προεπιλεγμένες τιμές.<br/>            Read/write [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/el/aspose.slides/geometryshape/adjustments/) | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/el/aspose.slides/iadjustvaluecollection). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/geometryshape/get_image/#) | Επιστρέφει μικρογραφία σχήματος.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει μικρογραφία σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/geometryshape/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι σύμβολο θέση. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο σύμβολο θέση εάν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολο θέση σε ένα καθορισμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/geometryshape/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα σύμβολο θέση (σχήμα από τη διάταξη και/ή την κύρια διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφει None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/geometryshape/get_visual_bounds/#) | Ανακτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/geometryshape/get_geometry_paths/#) | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή άνω γωνία του σχήματος. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή<br/>             άνω γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από πίνακα [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή<br/>             άνω γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/geometryshape/create_shape_elements/#) | Δημιουργεί και επιστρέφει πίνακα των στοιχείων του σχήματος. |

### Δείτε επίσης
* κλάση [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)