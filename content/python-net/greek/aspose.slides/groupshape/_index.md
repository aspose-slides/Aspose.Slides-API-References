---
title: GroupShape class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/groupshape/
---
## GroupShape κλάση

Αντιπροσωπεύει μια ομάδα σχημάτων σε μια διαφάνεια.

**Inheritance:**[`GroupShape`](/slides/python-net/el/aspose.slides/groupshape) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

Ο τύπος GroupShape εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/groupshape/is_text_holder/) | Καθορίζει αν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο-ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/groupshape/placeholder/) | Επιστρέφει το σύμβολο κράτησης θέσης για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει σύμβολο κράτησης θέσης.<br/>            Μόνο-ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/groupshape/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο-ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/groupshape/raw_frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/groupshape/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/groupshape/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: Επιστρέφει None για αντικείμενα GroupShape επειδή δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο-ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/groupshape/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3δ εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν 3δ ιδιότητες.<br/>            Μόνο-ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/groupshape/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο-ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/groupshape/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο-ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/groupshape/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/groupshape/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για το πέρασμα του ποντικού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/groupshape/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο-ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/groupshape/hidden/) | Καθορίζει αν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/groupshape/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στη σειρά z.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z.<br/>            Μόνο-ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/groupshape/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο-ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/groupshape/rotation/) | Επιστρέφει ή ορίζει τον αριθμό μοιρών που το καθορισμένο σχήμα περιστρέφεται γύρω από<br/>            τον άξονα z. Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/groupshape/x/) | Λαμβάνει ή ορίζει την x-συντεταγμένη της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/groupshape/y/) | Λαμβάνει ή ορίζει την y-συντεταγμένη της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/groupshape/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/groupshape/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/groupshape/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε λειτουργία εμφάνισης ασπρόμαυρου.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/groupshape/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση, αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επανεκχωρηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο-ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/groupshape/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό κατά τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο-ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/groupshape/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/groupshape/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/groupshape/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά εφόσον χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/groupshape/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/groupshape/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο-ανάγνωση [`IGroupShapeLock`](/slides/python-net/el/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/groupshape/is_grouped/) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο-ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/groupshape/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο-ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/groupshape/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο-ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/groupshape/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο-ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/el/aspose.slides/groupshape/group_shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο-ανάγνωση [`IGroupShapeLock`](/slides/python-net/el/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/el/aspose.slides/groupshape/shapes/) | Επιστρέφει τη συλλογή των σχημάτων μέσα στην ομάδα.<br/>            Μόνο-ανάγνωση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/groupshape/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλεγμένος τύπος ορίων μικρογραφίας σχήματος. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/groupshape/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι σύμβολο κράτησης θέσης. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο σύμβολο κράτησης θέσης αν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολου σε ένα καθορισμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/groupshape/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα σύμβολου κράτησης θέσης (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφεται None αν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/groupshape/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποτυπωμένο του περιεχόμενο. |

### Δείτε επίσης
* κλάση [`GroupShape`](/slides/python-net/el/aspose.slides/groupshape)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)