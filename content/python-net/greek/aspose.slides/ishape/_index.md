---
title: IShape class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/ishape/
---
## IShape κλάση

Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.

Ο τύπος IShape εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/ishape/is_text_holder/) | Καθορίζει εάν το σχήμα είναι TextHolder.<br/>            Μόνο για ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/ishape/placeholder/) | Επιστρέφει το placeholder για ένα σχήμα.<br/>            Μόνο για ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/ishape/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/ishape/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/ishape/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σ_shape_.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/ishape/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Μόνο για ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/ishape/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Μόνο για ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/ishape/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα.<br/>            Μόνο για ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/ishape/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Μόνο για ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/el/aspose.slides/ishape/hidden/) | Καθορίζει εάν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/ishape/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στη σειρά z-order.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z-order,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο εμπρός μέρος της σειράς z-order.<br/>            Μόνο για ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/ishape/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο για ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/ishape/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/ishape/x/) | Αποκτά ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/ishape/y/) | Αποκτά ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας του σ Shape_.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/ishape/width/) | Αποκτά ή ορίζει το πλάτος του σ Shape_, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/ishape/height/) | Αποκτά ή ορίζει το ύψος του σ Shape_, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`alternative_text`](/slides/python-net/el/aspose.slides/ishape/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σ Shape_.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/ishape/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σ Shape_.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/ishape/name/) | Επιστρέφει ή ορίζει το όνομα ενός σ Shape_.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/ishape/is_decorative/) | Αποκτά ή ορίζει την επιλογή 'Mark as decorative'<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/ishape/shape_lock/) | Επιστρέφει τα κλειδώματα του σ Shape_.<br/>            Μόνο για ανάγνωση [`IBaseShapeLock`](/slides/python-net/el/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/el/aspose.slides/ishape/unique_id/) | Επιστρέφει έναν εσωτερικό, σε παρουσία περιορισμένο, αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`IShape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/ishape/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια, το οποίο παραμένει σταθερό για τη διάρκεια ζωής του σ Shape_ και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα διαλειτουργικότητας να αναφέρεται αξιόπιστα στο σ Shape_ από οπουδήποτε στο έγγραφο.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`IShape.unique_id`](/slides/python-net/el/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/ishape/is_grouped/) | Καθορίζει εάν το σ Shape_ είναι ομαδοποιημένο.<br/>            Μόνο για ανάγνωση **bool**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/ishape/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σ Shape_ σε λειτουργία εμφάνισης ασπρόμαυρης.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/el/aspose.slides/ishape/parent_group/) | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σ Shape_ είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο για ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/ishape/hyperlink_manager/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/ishape/get_image/#) | Επιστρέφει τη μικρογραφία του σ Shape_.<br/>            Χρησιμοποιείται εξ ορισμού ο τύπος ShapeThumbnailBounds.Shape για τα όρια της μικρογραφίας σ Shape_. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σ Shape_. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/ishape/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/ishape/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/ishape/remove_placeholder/#) | Ορίζει ότι αυτό το σ Shape_ δεν είναι placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/ishape/get_base_placeholder/#) | Επιστρέφει ένα βασικό σ Shape_ placeholder (σ Shape_ από τη διάταξη και/ή τη κύρια διαφάνεια από την οποία κληρονομεί το τρέχον σ Shape_).<br/>            Επιστρέφεται None εάν το τρέχον σ Shape_ δεν κληρονομείται. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)