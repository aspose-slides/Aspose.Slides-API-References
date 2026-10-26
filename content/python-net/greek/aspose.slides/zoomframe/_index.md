---
title: ZoomFrame class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/zoomframe/
---
## ZoomFrame κλάση

Αναπαριστά ένα αντικείμενο Slide Zoom σε μια διαφάνεια.

**Κληρονομικότητα:**[`ZoomFrame`](/slides/python-net/el/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/el/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

Ο τύπος ZoomFrame εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/zoomframe/is_text_holder/) | Καθορίζει αν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/zoomframe/placeholder/) | Επιστρέφει το χώρο κράτησης για ένα σχήμα. Επιστρέφει None αν το σχήμα δεν έχει χώρο κράτησης.<br/>            Μόνο ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/zoomframe/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/zoomframe/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/zoomframe/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/zoomframe/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/zoomframe/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3δ εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3δ.<br/>            Μόνο ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/zoomframe/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/zoomframe/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/zoomframe/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/zoomframe/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/zoomframe/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσύνδεσμων.<br/>            Μόνο ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/zoomframe/hidden/) | Καθορίζει αν το σχήμα είναι κρυμμένο.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/zoomframe/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στη σειρά z.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z.<br/>            Μόνο ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/zoomframe/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/zoomframe/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από<br/>            τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/zoomframe/x/) | Λαμβάνει ή ορίζει τη συντεταγμένη x της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/zoomframe/y/) | Λαμβάνει ή ορίζει τη συντεταγμένη y της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/zoomframe/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/zoomframe/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/zoomframe/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε λειτουργία εμφάνισης ασπρόμαυρης.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/zoomframe/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/zoomframe/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στην διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή στον κώδικα interop να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/zoomframe/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/zoomframe/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/zoomframe/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/zoomframe/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/zoomframe/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/zoomframe/is_grouped/) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/zoomframe/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/zoomframe/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/zoomframe/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/el/aspose.slides/zoomframe/graphical_object_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/el/aspose.slides/zoomframe/image_type/) | Λαμβάνει ή ορίζει τον τύπο εικόνας ενός αντικειμένου zoom.<br/>            Ανάγνωση/εγγραφή [`ZoomImageType`](/slides/python-net/el/aspose.slides/zoomimagetype).<br/>            Προεπιλεγμένη τιμή: Preview |
| [`return_to_parent`](/slides/python-net/el/aspose.slides/zoomframe/return_to_parent/) | Λαμβάνει ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση.<br/>            Ανάγνωση/εγγραφή **bool**.<br/>            Προεπιλεγμένη τιμή: false |
| [`show_background`](/slides/python-net/el/aspose.slides/zoomframe/show_background/) | Λαμβάνει ή ορίζει την τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το παρασκήνιο της διαφάνειας προορισμού.<br/>            Ανάγνωση/εγγραφή **bool**.<br/>            Προεπιλεγμένη τιμή: true |
| [`zoom_image`](/slides/python-net/el/aspose.slides/zoomframe/zoom_image/) | Λαμβάνει ή ορίζει την εικόνα για το αντικείμενο zoom.<br/>            Ανάγνωση/εγγραφή [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/el/aspose.slides/zoomframe/transition_duration/) | Λαμβάνει ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας.<br/>            Ανάγνωση/εγγραφή **float**.<br/>            Προεπιλεγμένη τιμή: 1.0f |
| [`target_slide`](/slides/python-net/el/aspose.slides/zoomframe/target_slide/) | Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Slide Zoom.<br/>            Ανάγνωση/εγγραφή [`ISlide`](/slides/python-net/el/aspose.slides/islide). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/zoomframe/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            Το ShapeThumbnailBounds.Shape τύπο ορίων μικρογραφίας σχήματος χρησιμοποιείται ως προεπιλογή. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/zoomframe/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι χώρο κράτησης. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Προσθέτει νέο χώρο κράτησης αν δεν υπάρχει και ορίζει τις ιδιότητες του χώρου κράτησης σε ένα καθορισμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/zoomframe/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα χώρου κράτησης (σχήμα από τη διάταξη και/ή την κύρια διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφεται None αν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/zoomframe/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του. |

### Δείτε επίσης
* κλάση [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* κλάση [`ZoomFrame`](/slides/python-net/el/aspose.slides/zoomframe)
* κλάση [`ZoomObject`](/slides/python-net/el/aspose.slides/zoomobject)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)