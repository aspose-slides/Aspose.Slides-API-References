---
title: GraphicalObject class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/graphicalobject/
---
## GraphicalObject κλάση

Represents abstract graphical object.

**Inheritance:**[`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

The GraphicalObject type exposes the following members:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/graphicalobject/is_text_holder/) | Καθορίζει εάν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/graphicalobject/placeholder/) | Επιστρέφει το σύμβολο κράτησης για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει σύμβολο κράτησης.<br/>            Μόνο ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/graphicalobject/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/graphicalobject/raw_frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/graphicalobject/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/graphicalobject/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/graphicalobject/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3d εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d.<br/>            Μόνο ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/graphicalobject/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/graphicalobject/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/graphicalobject/hyperlink_click/) | Επιστρέφει ή ορίζει τον υποσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υποσύνδεσμο που ορίζεται για πέρασμα ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/graphicalobject/hyperlink_manager/) | Επιστρέφει το διαχειριστή υποσυνδέσμων.<br/>            Μόνο ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/graphicalobject/hidden/) | Καθορίζει εάν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/graphicalobject/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στην τάξη z-order.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος του z-order,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος του z-order.<br/>            Μόνο ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/graphicalobject/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/graphicalobject/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z.<br/>            Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/graphicalobject/x/) | Ανακτά ή ορίζει τη συντεταγμένη x της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/graphicalobject/y/) | Ανακτά ή ορίζει τη συντεταγμένη y της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/graphicalobject/width/) | Ανακτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/graphicalobject/height/) | Ανακτά ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/graphicalobject/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποτυπωθεί ένα σχήμα σε λειτουργία μαυρόασπρου εμφάνισης.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/graphicalobject/unique_id/) | Επιστρέφει έναν εσωτερικό, σε επίπεδο παρουσίασης, αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλον κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επαναχωριστεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/graphicalobject/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό σε επίπεδο διαφάνειας που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρει αξιόπιστα το σχήμα από οποιοδήποτε σημείο του εγγράφου.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/graphicalobject/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/graphicalobject/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/graphicalobject/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/graphicalobject/is_decorative/) | Ανακτά ή ορίζει την επιλογή 'Σημειώστε ως διακοσμητικό'<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/graphicalobject/shape_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/graphicalobject/is_grouped/) | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/graphicalobject/parent_group/) | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/graphicalobject/slide/) | Επιστρέφει τη διαφάνεια γονέα ενός σχήματος.<br/>            Μόνο ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/graphicalobject/presentation/) | Επιστρέφει την παρουσίαση γονέα μιας διαφάνειας.<br/>            Μόνο ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/el/aspose.slides/graphicalobject/graphical_object_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/graphicalobject/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            Χρησιμοποιείται προεπιλογή τύπου ShapeThumbnailBounds.Shape για τα όρια μικρογραφίας. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/graphicalobject/remove_placeholder/#) | Καθορίζει ότι αυτό το σχήμα δεν είναι σύμβολο κράτησης. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο σύμβολο κράτησης εάν δεν υπάρχει και ορίζει τις ιδιότητες του συμβόλου σε ένα καθορισμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/graphicalobject/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα σύμβολου κράτησης (σχήμα από τη διάταξη και/ή τη διαφάνεια πρότυπο από την οποία κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφεται None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/graphicalobject/get_visual_bounds/#) | Ανακτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του. |

### Δείτε επίσης
* κλάση [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)