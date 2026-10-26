---
title: OleObjectFrame class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/oleobjectframe/
---
## OleObjectFrame κλάση

Αντιπροσωπεύει ένα αντικείμενο OLE σε μια διαφάνεια.

**Κληρονομικότητα:**[`OleObjectFrame`](/slides/python-net/el/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

Ο τύπος OleObjectFrame εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/oleobjectframe/is_text_holder/) | Καθορίζει αν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο για ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/oleobjectframe/placeholder/) | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει placeholder.<br/>            Μόνο για ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/oleobjectframe/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο για ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/oleobjectframe/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/oleobjectframe/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/oleobjectframe/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο για ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/oleobjectframe/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3D εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3D.<br/>            Μόνο για ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/oleobjectframe/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει τα pixel εφέ που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο για ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/oleobjectframe/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο για ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/oleobjectframe/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο ορισμένο για κλικ του ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο ορισμένο για τοπική επίδειξη ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/oleobjectframe/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο για ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/oleobjectframe/hidden/) | Καθορίζει αν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/oleobjectframe/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στην τάξη z.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της τάξης z,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της τάξης z.<br/>            Μόνο για ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/oleobjectframe/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο για ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/oleobjectframe/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z.<br/>            Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/oleobjectframe/x/) | Αποκτά ή ορίζει τη συντεταγμένη x της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/oleobjectframe/y/) | Αποκτά ή ορίζει τη συντεταγμένη y της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/oleobjectframe/width/) | Αποκτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/oleobjectframe/height/) | Αποκτά ή ορίζει το ύψος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/oleobjectframe/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε λειτουργία εμφάνισης μαύρου-λευκού.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/oleobjectframe/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίατα ταυτοποιητή που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα.<br/>            Δεδομένου ότι αυτή η τιμή μπορεί να ανατεθεί εκ νέου από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/oleobjectframe/office_interop_shape_id/) | Επιστρέφει έναν μοναδικό ταυτοποιητή περιορισμένο σε διαφάνεια που παραμένει σταθερός για τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο για ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/oleobjectframe/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/oleobjectframe/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/oleobjectframe/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή τιμή string αν χρειαστεί.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/oleobjectframe/is_decorative/) | Αποκτά ή ορίζει την επιλογή 'Mark as decorative'.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/oleobjectframe/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο για ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/oleobjectframe/is_grouped/) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο για ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/oleobjectframe/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο για ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/oleobjectframe/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο για ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/oleobjectframe/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο για ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/el/aspose.slides/oleobjectframe/graphical_object_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο για ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/el/aspose.slides/oleobjectframe/substitute_picture_format/) | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject.<br/>            Μόνο για ανάγνωση [`IPictureFillFormat`](/slides/python-net/el/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/el/aspose.slides/oleobjectframe/substitute_picture_title/) | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`object_name`](/slides/python-net/el/aspose.slides/oleobjectframe/object_name/) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`object_prog_id`](/slides/python-net/el/aspose.slides/oleobjectframe/object_prog_id/) | Επιστρέφει το ProgID ενός αντικειμένου.<br/>            Μόνο για ανάγνωση **str**. |
| [`link_file_name`](/slides/python-net/el/aspose.slides/oleobjectframe/link_file_name/) | Επιστρέφει την πλήρη διαδρομή ενός συνδεδεμένου αρχείου. Θα χρησιμοποιηθεί το σύντομο όνομα αρχείου.<br/>            Μόνο για ανάγνωση **str**. |
| [`link_path_long`](/slides/python-net/el/aspose.slides/oleobjectframe/link_path_long/) | Επιστρέφει την πλήρη διαδρομή ενός συνδεδεμένου αρχείου. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`link_path_relative`](/slides/python-net/el/aspose.slides/oleobjectframe/link_path_relative/) | Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο εάν υπάρχει, διαφορετικά επιστρέφει μια κενή συμβολοσειρά.<br/>             Μόνο για ανάγνωση **str**. |
| [`embedded_file_label`](/slides/python-net/el/aspose.slides/oleobjectframe/embedded_file_label/) | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [`embedded_file_name`](/slides/python-net/el/aspose.slides/oleobjectframe/embedded_file_name/) | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| [`embedded_data`](/slides/python-net/el/aspose.slides/oleobjectframe/embedded_data/) | Αποκτά ή ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.<br/>            Ανάγνωση/εγγραφή [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/el/aspose.slides/oleobjectframe/is_object_icon/) | Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`is_object_link`](/slides/python-net/el/aspose.slides/oleobjectframe/is_object_link/) | Καθορίζει αν ένα αντικείμενο είναι συνδεδεμένο σε εξωτερικό αρχείο.<br/>            Μόνο για ανάγνωση **bool**. |
| [`update_automatic`](/slides/python-net/el/aspose.slides/oleobjectframe/update_automatic/) | Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται.<br/>            Ανάγνωση/εγγραφή **bool**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/oleobjectframe/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            Η προεπιλεγμένη χρήση είναι ο τύπος ShapeThumbnailBounds.Shape για τα όρια μικρογραφίας σχήματος. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/oleobjectframe/remove_placeholder/#) | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/oleobjectframe/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια-μάστορα από το οποίο κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφεται None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/oleobjectframe/get_visual_bounds/#) | Αποκτά τα οπτικά όρια του σχήματος, υπολογισμένα από το αποδιδόμενο περιεχόμενό του. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/el/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.<br/>            <br/>            Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντανακλούν τα νέα δεδομένα και <br/>            ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |

### Δείτε επίσης
* κλάση [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject)
* κλάση [`OleObjectFrame`](/slides/python-net/el/aspose.slides/oleobjectframe)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)