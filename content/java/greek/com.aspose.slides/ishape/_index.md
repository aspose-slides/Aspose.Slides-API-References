---
title: IShape
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ishape/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Καθορίζει αν το σχήμα είναι TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Επιστρέφει το placeholder για ένα σχήμα. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [removePlaceholder()](#removePlaceholder--) | Καθορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. |
| [getRawFrame()](#getRawFrame--) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου frame του σχήματος. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου frame του σχήματος. |
| [getFrame()](#getFrame--) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου frame του σχήματος. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου frame του σχήματος. |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. |
| [getThreeDFormat()](#getThreeDFormat--) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. |
| [getImage()](#getImage--) | Επιστρέφει μικρογραφία σχήματος. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Επιστρέφει μικρογραφία σχήματος. |
| [getHidden()](#getHidden--) | Καθορίζει αν το σχήμα είναι κρυφό. |
| [setHidden(boolean value)](#setHidden-boolean-) | Καθορίζει αν το σχήμα είναι κρυφό. |
| [getZOrderPosition()](#getZOrderPosition--) | Επιστρέφει τη θέση ενός σχήματος στην σειρά z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. |
| [getRotation()](#getRotation--) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. |
| [setRotation(float value)](#setRotation-float-) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. |
| [getX()](#getX--) | Λαμβάνει ή ορίζει τη συντεταγμένη x του άνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. |
| [setX(float value)](#setX-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη x του άνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. |
| [getY()](#getY--) | Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. |
| [setY(float value)](#setY-float-) | Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. |
| [getWidth()](#getWidth--) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. |
| [setWidth(float value)](#setWidth-float-) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. |
| [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. |
| [setHeight(float value)](#setHeight-float-) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. |
| [getAlternativeText()](#getAlternativeText--) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. |
| [isDecorative()](#isDecorative--) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' Read/write boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' Read/write boolean. |
| [getShapeLock()](#getShapeLock--) | Επιστρέφει τις κλειδώσεις του σχήματος. |
| [getUniqueId()](#getUniqueId--) | Επιστρέφει έναν εσωτερικό, περιορισμένο σε παρουσία, ταυτοποιητή προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή τον κώδικα interop να αναφέρεται αξιόπιστα στο σ shape από οπουδήποτε στο έγγραφο. |
| [isGrouped()](#isGrouped--) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία μαυρόασπρου εμφάνισης. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία μαυρόασπρου εμφάνισης. |
| [getParentGroup()](#getParentGroup--) | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σχήμα είναι ομαδοποιημένο. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Επιστρέφει ένα βασικό σ shape placeholder (σ shape από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σ shape). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Καθορίζει αν το σχήμα είναι TextHolder. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Επιστρέφει το placeholder για ένα σ shape. Μόνο για ανάγνωση [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Επιστρέφει:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder to copy content from. |

**Επιστρέφει:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Καθορίζει ότι αυτό το σ shape δεν είναι placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Επιστρέφει τα προσαρμοσμένα δεδομένα του σ shape. Μόνο για ανάγνωση [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου frame του σ shape. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  // ή
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  // Αυτός ο κώδικας μπορεί να οδηγήσει σε ασαφείς καταστάσεις. Έτσι έχουν προστεθεί περιορισμοί για τη χρήση ακαθόριστων τιμών στο IShape.getFrame(). Οι τιμές των x, y, width, height, flipH, flipV και rotationAngle πρέπει να είναι ορισμένες (όχι Float.NaN ή NullableBool.NotDefined). Ο παραπάνω κώδικας τώρα ρίχνει εξαίρεση ArgumentException.
>  // Αυτό εφαρμόζεται σε αυτές τις περιπτώσεις:
>  IShape shape = ...;
>  shape.setFrame(...); // δεν μπορεί να είναι ακαθόριστο
>  IShapeCollection shapes = ...;
>  // οι παράμετροι x, y, width, height δεν μπορούν να είναι Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // τώρα το shape κληρονομεί τις τιμές x, y, height, flipH, flipV από το placeholder και υπερισχύει το width=100 και rotationAngle=0.
> ```

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει τις ιδιότητες του ακατέργαστου frame του σ shape. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ή
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Τέτοιος κώδικας μπορεί να οδηγήσει σε ασαφείς καταστάσεις. Έτσι έχουν προστεθεί περιορισμοί για τη χρήση ακαθόριστων τιμών στο IShape.getFrame(). Οι τιμές των x, y, width, height, flipH, flipV και rotationAngle πρέπει να είναι ορισμένες (όχι Float.NaN ή NullableBool.NotDefined). Ο παραπάνω κώδικας τώρα ρίχνει εξαίρεση ArgumentException.
>  //Αυτό ισχύει για αυτές τις περιπτώσεις:
>  IShape shape = ...;
>  shape.setFrame(...); // δεν μπορεί να είναι ακαθόριστο
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // τώρα το shape κληρονομεί τις τιμές x, y, height, flipH, flipV από το placeholder και υπερισχύει το width=100 και rotationAngle=0.
```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Επιστρέφει ή ορίζει τις ιδιότητες του σ frame. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Η τιμή κάθε ιδιότητας του επιστρεφόμενου IShapeFrame παραδείγματος δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας του ανατεθειμένου IShapeFrame πρέπει να μην είναι undefined (πρέπει να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει τις ιδιότητες του σ frame. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Η τιμή κάθε ιδιότητας του επιστρεφόμενου IShapeFrame παραδείγματος δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας του ανατεθειμένου IShapeFrame πρέπει να μην είναι undefined (πρέπει να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σ shape. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σ shape. Μόνο για ανάγνωση [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Επιστρέφει:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σ shape. Μόνο για ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σ shape. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Επιστρέφει μικρογραφία σ shape. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Επιστρέφει μικρογραφία σ shape.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail ή null σε περίπτωση που χρησιμοποιείται ShapeThumbnailBounds.Appearance και το σ shape δεν έχει ορατά στοιχεία.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Καθορίζει αν το σ shape είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Καθορίζει αν το σ shape είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Επιστρέφει τη θέση ενός σ shape στην σειρά z. Shapes[0] επιστρέφει το σ shape στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σ shape στο μπροστινό μέρος της σειράς z. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σ shape. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το καθορισμένο σ shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη (δεν είναι Float.NaN). Η τιμή που ανατίθεται πρέπει να είναι ορισμένη (δεν είναι Float.NaN). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Επιστρέφει:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το καθορισμένο σ shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη (δεν είναι Float.NaN). Η τιμή που ανατίθεται πρέπει να είναι ορισμένη (δεν είναι Float.NaN). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Λαμβάνει ή ορίζει τη συντεταγμένη x του άνω-αριστερού γωνιακού σημείου του σ shape, μετρημένη σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Λαμβάνει ή ορίζει τη συντεταγμένη x του άνω-αριστερού γωνιακού σημείου του σ shape, μετρημένη σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω-αριστερού γωνιακού σημείου του σ shape, μετρημένη σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Λαμβάνει ή ορίζει τη συντεταγμένη y του άνω-αριστερού γωνιακού σημείου του σ shape, μετρημένη σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Λαμβάνει ή ορίζει το πλάτος του σ shape, μετρημένο σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Λαμβάνει ή ορίζει το πλάτος του σ shape, μετρημένο σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Λαμβάνει ή ορίζει το ύψος του σ shape, μετρημένο σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Λαμβάνει ή ορίζει το ύψος του σ shape, μετρημένο σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σ shape. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σ shape. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σ shape. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σ shape. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Επιστρέφει ή ορίζει το όνομα ενός σ shape. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός σ shape. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Επιστρέφει τις κλειδώσεις του σ shape. Μόνο για ανάγνωση [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Επιστρέφει:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Επιστρέφει έναν εσωτερικό, περιορισμένο σε παρουσία, ταυτοποιητή προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση long. Δείτε επίσης \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Επιστρέφει:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σ shape και επιτρέπει στο PowerPoint ή τον κώδικα interop να αναφέρεται αξιόπιστα στο σ shape από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση long. Δείτε επίσης \#getUniqueId.getUniqueId.

**Επιστρέφει:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Καθορίζει αν το σ shape είναι ομαδοποιημένο. Μόνο για ανάγνωση boolean.

--------------------

Η ιδιότητα \#getParentGroup.getParentGroup επιστρέφει το αντικείμενο GroupShape γονέα εάν το σ shape είναι ομαδοποιημένο.

**Επιστρέφει:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σ shape σε λειτουργία μαυρόασπρου εμφάνισης. Ανάγνωση/εγγραφή [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Επιστρέφει:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σ shape σε λειτουργία μαυρόασπρου εμφάνισης. Ανάγνωση/εγγραφή [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σ shape είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Η ιδιότητα \#isGrouped.isGrouped καθορίζει αν το σ shape είναι ομαδοποιημένο.

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Επιστρέφει ένα βασικό σ shape placeholder (σ shape από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σ shape).

--------------------

> ```
> // Πάρτε όλα τα (master/layout/slide) κινούμενα εφέ του placeholder shape
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Επιστρέφεται null εάν το τρέχον σ shape δεν κληρονομείται.

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)