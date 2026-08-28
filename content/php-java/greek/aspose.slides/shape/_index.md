---
title: Shape
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/shape/
---
## Shape κλάση

  Represents a shape on a slide.
 
### addPlaceholder {#addPlaceholder}

| Όνομα | Περιγραφή |
| --- | --- |
| addPlaceholder ([Placeholder](../placeholder)) | Προσθέτει έναν νέο σύμβολο κράτησης αν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολου κράτησης σε ένα καθορισμένο. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| placeholderToCopyFrom | [Placeholder](../placeholder) | Σύμβολο κράτησης από το οποίο θα αντιγραφεί το περιεχόμενο. |

 **Επιστρέφει:**
[Placeholder](../placeholder)


---


### getAlternativeText {#getAlternativeText}

| Όνομα | Περιγραφή |
| --- | --- |
| getAlternativeText () | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
String


---


### getAlternativeTextTitle {#getAlternativeTextTitle}

| Όνομα | Περιγραφή |
| --- | --- |
| getAlternativeTextTitle () | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
String


---


### getBasePlaceholder {#getBasePlaceholder}

| Όνομα | Περιγραφή |
| --- | --- |
| getBasePlaceholder () | Επιστρέφει ένα βασικό σχήμα σύμβολου κράτησης (σχήμα από τη διάταξη και/ή την κύρια διαφάνεια από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### getBlackWhiteMode {#getBlackWhiteMode}

| Όνομα | Περιγραφή |
| --- | --- |
| getBlackWhiteMode () | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε κατάσταση ασπρόμαυρης εμφάνισης. Ανάγνωση/Εγγραφή BlackWhiteMode. |

 **Επιστρέφει:**
byte


---


### getConnectionSiteCount {#getConnectionSiteCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getConnectionSiteCount () | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση int. |

 **Επιστρέφει:**
int


---


### getCustomData {#getCustomData}

| Όνομα | Περιγραφή |
| --- | --- |
| getCustomData () | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση ICustomData. |

 **Επιστρέφει:**
[CustomData](../customdata)


---


### getEffectFormat {#getEffectFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getEffectFormat () | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο ανάγνωση IEffectFormat. |

 **Επιστρέφει:**
[EffectFormat](../effectformat)


---


### getFillFormat {#getFillFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getFillFormat () | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες διαμόρφωσης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο ανάγνωση IFillFormat. |

 **Επιστρέφει:**
[FillFormat](../fillformat)


---


### getFrame {#getFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| getFrame () | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή IShapeFrame. Η τιμή κάθε ιδιότητας της επιστρεφόμενης παρουσίας IShapeFrame δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας της εκχωρημένης παρουσίας IShapeFrame πρέπει να μην είναι undefined (πρέπει να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε undefined τιμές για ιδιότητες παρουσίας RawFrame. |

 **Επιστρέφει:**
[ShapeFrame](../shapeframe)


---


### getHeight {#getHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeight () | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες παρουσίας RawFrame. |

 **Επιστρέφει:**
float


---


### getHidden {#getHidden}

| Όνομα | Περιγραφή |
| --- | --- |
| getHidden () | Καθορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### getHyperlinkClick {#getHyperlinkClick}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkClick () | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/Εγγραφή IHyperlink. |

 **Επιστρέφει:**
[Hyperlink](../hyperlink)


---


### getHyperlinkManager {#getHyperlinkManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkManager () | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο ανάγνωση IHyperlinkManager. |

 **Επιστρέφει:**
[HyperlinkManager](../hyperlinkmanager)


---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkMouseOver () | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για mouse over. Ανάγνωση/Εγγραφή IHyperlink. |

 **Επιστρέφει:**
[Hyperlink](../hyperlink)


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage () | Επιστρέφει μικρογραφία σχήματος. Το τύπο όριο ShapeThumbnailBounds.Shape χρησιμοποιείται εξ' ορισμού. |

 **Επιστρέφει:**
IImage


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage (int, float, float) | Επιστρέφει μικρογραφία σχήματος. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| bounds | int | Τύπος ορίων μικρογραφίας σχήματος. |
| scaleX | float | Κλίμακα X |
| scaleY | float | Κλίμακα Y |

 **Επιστρέφει:**
IImage


---


### getLineFormat {#getLineFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getLineFormat () | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο ανάγνωση ILineFormat. |

 **Επιστρέφει:**
[LineFormat](../lineformat)


---


### getName {#getName}

| Όνομα | Περιγραφή |
| --- | --- |
| getName () | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή τιμή string αν χρειάζεται. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
String


---


### getOfficeInteropShapeId {#getOfficeInteropShapeId}

| Όνομα | Περιγραφή |
| --- | --- |
| getOfficeInteropShapeId () | Επιστρέφει ένα μοναδικό αναγνωριστικό εντός διαφάνειας που παραμένει σταθερό κατά τη διάρκεια ζωής του σχήματος και επιτρέπει στον PowerPoint ή σε κώδικα interop να αναφερθεί αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση long. Δείτε επίσης #getUniqueId. |

 **Επιστρέφει:**
long


---


### getParentGroup {#getParentGroup}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentGroup () | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση IGroupShape. Η ιδιότητα #isGrouped καθορίζει εάν το σχήμα είναι ομαδοποιημένο. |

 **Επιστρέφει:**
[GroupShape](../groupshape)


---


### getPlaceholder {#getPlaceholder}

| Όνομα | Περιγραφή |
| --- | --- |
| getPlaceholder () | Επιστρέφει το σύμβολο κράτησης για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει σύμβολο κράτησης. Μόνο ανάγνωση IPlaceholder. |

 **Επιστρέφει:**
[Placeholder](../placeholder)


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση της διαφάνειας. Μόνο ανάγνωση IPresentation. |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### getRawFrame {#getRawFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| getRawFrame () | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος. Ανάγνωση/Εγγραφή IShapeFrame. |

 **Επιστρέφει:**
[ShapeFrame](../shapeframe)


---


### getRotation {#getRotation}

| Όνομα | Περιγραφή |
| --- | --- |
| getRotation () | Επιστρέφει ή ορίζει τον αριθμό των μοιρών με τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· αρνητική τιμή αριστερόστροφη. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη (δεν είναι Float.NaN). Η εκχωρημένη τιμή πρέπει να είναι ορισμένη (δεν είναι Float.NaN). Μπορείτε να ορίσετε undefined τιμές για ιδιότητες RawFrame. |

 **Επιστρέφει:**
float


---


### getShapeLock {#getShapeLock}

| Όνομα | Περιγραφή |
| --- | --- |
| getShapeLock () | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση IBaseShapeLock. |

 **Επιστρέφει:**
[GraphicalObjectLock](../graphicalobjectlock), [ConnectorLock](../connectorlock), [AutoShapeLock](../autoshapelock), [PictureFrameLock](../pictureframelock), [BaseShapeLock](../baseshapelock), [GroupShapeLock](../groupshapelock)


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση IBaseSlide. |

 **Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getThreeDFormat {#getThreeDFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getThreeDFormat () | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3δ εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3δ. Μόνο ανάγνωση IThreeDFormat. |

 **Επιστρέφει:**
[ThreeDFormat](../threedformat)


---


### getUniqueId {#getUniqueId}

| Όνομα | Περιγραφή |
| --- | --- |
| getUniqueId () | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση, αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα. Επειδή αυτή η τιμή μπορεί να επανεκχωρηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση long. Δείτε επίσης #getOfficeInteropShapeId. |

 **Επιστρέφει:**
long


---


### getVisualBounds {#getVisualBounds}

| Όνομα | Περιγραφή |
| --- | --- |
| getVisualBounds () | Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδιδόμενο περιεχόμενο. |

 **Επιστρέφει:**
Rectangle2D.Float


---


### getWidth {#getWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getWidth () | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες RawFrame. |

 **Επιστρέφει:**
float


---


### getX {#getX}

| Όνομα | Περιγραφή |
| --- | --- |
| getX () | Λαμβάνει ή ορίζει τη συντεταγμένη x της άνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες RawFrame. |

 **Επιστρέφει:**
float


---


### getY {#getY}

| Όνομα | Περιγραφή |
| --- | --- |
| getY () | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες RawFrame. |

 **Επιστρέφει:**
float


---


### getZOrderPosition {#getZOrderPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| getZOrderPosition () | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο βάθος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στην κορυφή της σειράς z. Μόνο ανάγνωση int. |

 **Επιστρέφει:**
int


---


### isDecorative {#isDecorative}

| Όνομα | Περιγραφή |
| --- | --- |
| isDecorative () | Λαμβάνει ή ορίζει την επιλογή «Σημείωση ως διακοσμητικό». Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isGrouped {#isGrouped}

| Όνομα | Περιγραφή |
| --- | --- |
| isGrouped () | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση boolean. Η ιδιότητα #getParentGroup επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. |

 **Επιστρέφει:**
boolean


---


### isTextHolder {#isTextHolder}

| Όνομα | Περιγραφή |
| --- | --- |
| isTextHolder () | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### removePlaceholder {#removePlaceholder}

| Όνομα | Περιγραφή |
| --- | --- |
| removePlaceholder () | Ορίζει ότι αυτό το σχήμα δεν είναι σύμβολο κράτησης. |

 **Επιστρέφει:**
void


---


### setAlternativeText {#setAlternativeText}

| Όνομα | Περιγραφή |
| --- | --- |
| setAlternativeText (String) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
void


---


### setAlternativeTextTitle {#setAlternativeTextTitle}

| Όνομα | Περιγραφή |
| --- | --- |
| setAlternativeTextTitle (String) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
void


---


### setBlackWhiteMode {#setBlackWhiteMode}

| Όνομα | Περιγραφή |
| --- | --- |
| setBlackWhiteMode (byte) | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε κατάσταση ασπρόμαυρης εμφάνισης. Ανάγνωση/Εγγραφή BlackWhiteMode. |

 **Επιστρέφει:**
void


---


### setDecorative {#setDecorative}

| Όνομα | Περιγραφή |
| --- | --- |
| setDecorative (boolean) | Λαμβάνει ή ορίζει την επιλογή «Σημείωση ως διακοσμητικό». Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setFrame {#setFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή IShapeFrame. Η τιμή κάθε ιδιότητας της επιστρεφόμενης IShapeFrame δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας της εκχωρημένης IShapeFrame πρέπει να μην είναι undefined (πρέπει να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε undefined τιμές για ιδιότητες RawFrame. |

 **Επιστρέφει:**
void


---


### setHeight {#setHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setHeight (float) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες RawFrame. |

 **Επιστρέφει:**
void


---


### setHidden {#setHidden}

| Όνομα | Περιγραφή |
| --- | --- |
| setHidden (boolean) | Καθορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setHyperlinkClick {#setHyperlinkClick}

| Όνομα | Περιγραφή |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/Εγγραφή IHyperlink. |

 **Επιστρέφει:**
void


---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| Όνομα | Περιγραφή |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για mouse over. Ανάγνωση/Εγγραφή IHyperlink. |

 **Επιστρέφει:**
void


---


### setName {#setName}

| Όνομα | Περιγραφή |
| --- | --- |
| setName (String) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή τιμή string αν χρειάζεται. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
void


---


### setRawFrame {#setRawFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| setRawFrame ([ShapeFrame](../shapeframe)) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος. Ανάγνωση/Εγγραφή IShapeFrame. |

 **Επιστρέφει:**
void


---


### setRotation {#setRotation}

| Όνομα | Περιγραφή |
| --- | --- |
| setRotation (float) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών με τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· αρνητική τιμή αριστερόστροφη. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη (δεν είναι Float.NaN). Η εκχωρημένη τιμή πρέπει να είναι ορισμένη (δεν είναι Float.NaN). Μπορείτε να ορίσετε undefined τιμές για ιδιότητες RawFrame. }

 **Επιστρέφει:**
void


---


### setWidth {#setWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| setWidth (float) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες RawFrame. |

 **Επιστρέφει:**
void


---


### setX {#setX}

| Όνομα | Περιγραφή |
| --- | --- |
| setX (float) | Λαμβάνει ή ορίζει τη συντεταγμένη x της άνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες RawFrame. }

 **Επιστρέφει:**
void


---


### setY {#setY}

| Όνομα | Περιγραφή |
| --- | --- |
| setY (float) | Λαμβάνει ή ορίζει τη συντεταγμένη y της άνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή float. Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η εκχωρημένη τιμή πρέπει επίσης να είναι ορισμένη· εκχωρήστε Float.NaN μόνο σε ιδιότητες RawFrame. }

 **Επιστρέφει:**
void


---


### writeAsSvg {#writeAsSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| writeAsSvg (OutputStream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή προορισμού |

 **Επιστρέφει:**
void


---


### writeAsSvg {#writeAsSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| writeAsSvg (OutputStream, [SVGOptions](../svgoptions)) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή προορισμού |
| svgOptions | [SVGOptions](../svgoptions) | Επιλογές δημιουργίας SVG |

 **Επιστρέφει:**
void


---