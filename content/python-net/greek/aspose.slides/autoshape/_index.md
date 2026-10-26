---
title: AutoShape class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/autoshape/
---
## AutoShape κλάση

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/el/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

The AutoShape type exposes the following members:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/autoshape/is_text_holder/) | Καθορίζει αν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο-ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/autoshape/placeholder/) | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει placeholder.<br/>            Μόνο-ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/autoshape/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο-ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/autoshape/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/autoshape/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/autoshape/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο-ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/autoshape/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3d εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d.<br/>            Μόνο-ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/autoshape/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο-ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/autoshape/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο-ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/autoshape/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/autoshape/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για τοπική τοποθέτηση του ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/autoshape/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο-ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/autoshape/hidden/) | Καθορίζει αν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/autoshape/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στην σειρά z.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z.<br/>            Μόνο-ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/autoshape/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο-ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/autoshape/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών με τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z.<br/>            Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μία αρνητική τιμή<br/>            υποδηλώνει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/autoshape/x/) | Αποκτά ή ορίζει την τιμή x του άνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/autoshape/y/) | Αποκτά ή ορίζει την τιμή y του άνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/autoshape/width/) | Αποκτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/autoshape/height/) | Αποκτά ή ορίζει το ύψος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/autoshape/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε μορφή ασπρόμαυρης προβολής..<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/autoshape/unique_id/) | Επιστρέφει έναν εσωτερικό αναγνωριστικό, περιορισμένο στην παρουσίαση, που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο-ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/autoshape/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο-ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/autoshape/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/autoshape/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/autoshape/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/autoshape/is_decorative/) | Αποκτά ή ορίζει την επιλογή 'Mark as decorative'<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/autoshape/shape_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο-ανάγνωση [`IAutoShapeLock`](/slides/python-net/el/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/autoshape/is_grouped/) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο-ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/autoshape/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο-ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/autoshape/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο-ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/autoshape/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο-ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/el/aspose.slides/autoshape/shape_style/) | Επιστρέφει το αντικείμενο στυλ του σχήματος.<br/>            Μόνο-ανάγνωση [`IShapeStyle`](/slides/python-net/el/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/el/aspose.slides/autoshape/shape_type/) | Επιστρέφει ή ορίζει τον τύπο προρυθμισμένης γεωμετρίας.<br/>            Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές προσαρμογών θα επαναφερθούν στις προεπιλεγμένες τιμές.<br/>            Ανάγνωση/εγγραφή [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/el/aspose.slides/autoshape/adjustments/) | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος.<br/>            Μόνο-ανάγνωση [`IAdjustValueCollection`](/slides/python-net/el/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/el/aspose.slides/autoshape/auto_shape_lock/) | Επιστρέφει τα κλειδώματα του autoshape.<br/>            Μόνο-ανάγνωση [`IAutoShapeLock`](/slides/python-net/el/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/el/aspose.slides/autoshape/text_frame/) | Επιστρέφει το αντικείμενο TextFrame για το AutoShape.<br/>            Μόνο-ανάγνωση [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/el/aspose.slides/autoshape/use_background_fill/) | Καθορίζει αν αυτό το autoshape πρέπει να γεμιστεί με το φόντο της διαφάνειας αντί να καθορίζεται από το στυλ ή το format γεμίσματος.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`is_text_box`](/slides/python-net/el/aspose.slides/autoshape/is_text_box/) | Καθορίζει αν το σχήμα είναι πλαίσιο κειμένου. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/autoshape/get_image/#) | Επιστρέφει μικρογραφία σχήματος.<br/>            Χρησιμοποιείται προεπιλεγμένα ο τύπος ShapeThumbnailBounds.Shape για τα όρια της μικρογραφίας. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει μικρογραφία σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/autoshape/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/autoshape/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφει None εάν το τρέχον σχήμα δεν κληρονομεί. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/autoshape/get_visual_bounds/#) | Αποκτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/autoshape/get_geometry_paths/#) | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με το πάνω αριστερό γωνιακό σημείο του σχήματος. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το πάνω αριστερό γωνιακό σημείο του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από πίνακα [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το πάνω αριστερό γωνιακό σημείο του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/autoshape/create_shape_elements/#) | Δημιουργεί και επιστρέφει πίνακα των στοιχείων του σχήματος. |
| [`add_text_frame(self, text)`](/slides/python-net/el/aspose.slides/autoshape/add_text_frame/#str) | Προσθέτει ένα νέο TextFrame σε σχήμα.<br/>            Εάν το σχήμα διαθέτει ήδη TextFrame, τότε απλώς αλλάζει το κείμενό του. |

### Δείτε επίσης
* κλάση [`AutoShape`](/slides/python-net/el/aspose.slides/autoshape)
* κλάση [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)