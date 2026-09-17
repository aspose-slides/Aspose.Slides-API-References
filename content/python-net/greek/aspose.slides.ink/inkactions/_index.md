---
title: InkActions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ink/inkactions/
---
## InkActions κλάση

Represents the root of ink actions.

**Inheritance:**[`InkActions`](/slides/python-net/el/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

The InkActions type exposes the following members:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides.ink/inkactions/is_text_holder/) | Καθορίζει αν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο-ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides.ink/inkactions/placeholder/) | Επιστρέφει το δεσμευτικό στοιχείο για ένα σχήμα. Επιστρέφει None εάν το σχήμα δεν έχει δεσμευτικό στοιχείο.<br/>            Μόνο-ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides.ink/inkactions/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο-ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides.ink/inkactions/raw_frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides.ink/inkactions/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος.<br/>            Ανάγνωση/εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides.ink/inkactions/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες διαμόρφωσης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο-ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides.ink/inkactions/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιλαμβάνει τις ιδιότητες 3d εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d.<br/>            Μόνο-ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides.ink/inkactions/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat το οποίο περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο-ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides.ink/inkactions/fill_format/) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες διαμόρφωσης γεμίσματος για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος.<br/>            Μόνο-ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides.ink/inkactions/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για hover ποντικιού.<br/>            Ανάγνωση/εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides.ink/inkactions/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο-ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides.ink/inkactions/hidden/) | Καθορίζει αν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides.ink/inkactions/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στη σειρά z-order.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος του z-order,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος του z-order.<br/>            Μόνο-ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides.ink/inkactions/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο-ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides.ink/inkactions/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z.<br/>            Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή<br/>            υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides.ink/inkactions/x/) | Λαμβάνει ή ορίζει τη συντεταγμένη x της άνω-αριστερής γωνίας του σχήματος, μετρημένη σε μονάδες σημείου.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides.ink/inkactions/y/) | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω-αριστερής γωνίας του σχήματος, μετρημένη σε μονάδες σημείου.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides.ink/inkactions/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε μονάδες σημείου.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides.ink/inkactions/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε μονάδες σημείου.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides.ink/inkactions/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία εμφάνισης ασπρόμαυρης.<br/>            Ανάγνωση/εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides.ink/inkactions/unique_id/) | Επιστρέφει ένα εσωτερικό, εντός παρουσίασης αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα.<br/>            Δεδομένου ότι αυτή η τιμή μπορεί να επαναταταχθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται<br/>            ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο-ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides.ink/inkactions/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό εντός διαφάνειας που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και<br/>            επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφορά το σχήμα αξιόπιστα από οπουδήποτε στο έγγραφο.<br/>            Μόνο-ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides.ink/inkactions/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides.ink/inkactions/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides.ink/inkactions/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides.ink/inkactions/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'.<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides.ink/inkactions/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο-ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides.ink/inkactions/is_grouped/) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο-ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides.ink/inkactions/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει None.<br/>            Μόνο-ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides.ink/inkactions/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο-ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides.ink/inkactions/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο-ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/el/aspose.slides.ink/inkactions/graphical_object_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο-ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides.ink/inkactions/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            Χρησιμοποιείται προεπιλογή ο τύπος ShapeThumbnailBounds.Shape για τα όρια μικρογραφίας. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides.ink/inkactions/remove_placeholder/#) | Καθορίζει ότι αυτό το σχήμα δεν είναι δεσμευτικό στοιχείο. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο δεσμευτικό στοιχείο εάν δεν υπάρχει και ορίζει τις ιδιότητες του δεσμευτικού στοιχείου σε ένα καθορισμένο. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides.ink/inkactions/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα δεσμευτικού στοιχείου (σχήμα από τη διάταξη και/ή τη διαφάνεια master από την οποία κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφεται None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides.ink/inkactions/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενό του. |

### Δείτε επίσης
* κλάση [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject)
* κλάση [`InkActions`](/slides/python-net/el/aspose.slides.ink/inkactions)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* μονάδα [`aspose.slides.ink`](/slides/python-net/el/aspose.slides.ink)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)