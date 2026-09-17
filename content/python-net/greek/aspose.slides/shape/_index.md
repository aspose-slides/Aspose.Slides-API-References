---
title: Shape class
second_title: Aspose.Slides για Python μέσω .NET - Αναφορά API
description: 
type: docs
url: /el/aspose.slides/shape/
---
## Shape κλάση

Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.

Ο τύπος Shape εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/shape/is_text_holder/) | Καθορίζει εάν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο για ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/shape/placeholder/) | Επιστρέφει το σύμβολο κράτησης θέσης για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει σύμβολο κράτησης θέσης.<br/>            Μόνο για ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/shape/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/shape/raw_frame/) | Επιστρέφει ή ορίζει τις πρωτόγονες ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/shape/frame/) | Επιστέψει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/shape/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο για ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/shape/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3δ εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3δ.<br/>            Μόνο για ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/shape/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο για ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/shape/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γέμισματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γέμισματος.<br/>            Μόνο για ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/shape/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/shape/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για αιωρία ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/shape/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο για ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/shape/hidden/) | Καθορίζει εάν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/shape/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στη σειρά z.<br/>            Το Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z,<br/>            και το Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στην μπροστινή θέση της σειράς z.<br/>            Μόνο για ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/shape/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο για ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/shape/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών με τους οποίους το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/shape/x/) | Λαμβάνει ή ορίζει το συντεταγμένο x της επάνω αριστερής γωνίας του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/shape/y/) | Λαμβάνει ή ορίζει το συντεταγμένο y της επάνω αριστερής γωνίας του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/shape/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/shape/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/shape/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα εμφανίζεται ένα σχήμα σε λειτουργία έντονου ασπρόμαυρου.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id/) | Επιστρέφει ένα εσωτερικό, σε παρουσία περιορισμένο αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Δεδομένου ότι αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/shape/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/shape/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/shape/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/shape/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/shape/shape_lock/) | Επιστρέφει τα κλειδώματα του σχήματος.<br/>            Μόνο για ανάγνωση [`IBaseShapeLock`](/slides/python-net/el/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/shape/is_grouped/) | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο για ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/shape/parent_group/) | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο για ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/shape/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο για ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/shape/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο για ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/shape/get_image/#) | Επιστρέφει μικρογραφία σχήματος.<br/>            Το ShapeThumbnailBounds.Shape shape thumbnail bounds type χρησιμοποιείται ως προεπιλογή. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει μικρογραφία σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/shape/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/shape/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι σύμβολο κράτησης θέσης. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/shape/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο σύμβολο κράτησης θέσης εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/shape/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφει None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/shape/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδομένο περιεχόμενό του. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)