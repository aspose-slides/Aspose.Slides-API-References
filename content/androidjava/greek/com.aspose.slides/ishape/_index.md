---
title: IShape
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ishape/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
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
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [removePlaceholder()](#removePlaceholder--) | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. |
| [getRawFrame()](#getRawFrame--) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. |
| [getFrame()](#getFrame--) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος. |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. |
| [getThreeDFormat()](#getThreeDFormat--) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες μορφοποίησης τρισδιάστατου για ένα σχήμα. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. |
| [getImage()](#getImage--) | Επιστρέφει μικρογραφία σχήματος. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Επιστρέφει μικρογραφία σχήματος. |
| [getHidden()](#getHidden--) | Καθορίζει αν το σχήμα είναι κρυφό. |
| [setHidden(boolean value)](#setHidden-boolean-) | Καθορίζει αν το σχήμα είναι κρυφό. |
| [getZOrderPosition()](#getZOrderPosition--) | Επιστρέφει τη θέση ενός σχήματος στην κατάταξη z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. |
| [getRotation()](#getRotation--) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. |
| [setRotation(float value)](#setRotation-float-) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σ shape περιστρέφεται γύρω από τον άξονα z. |
| [getX()](#getX--) | Λαμβάνει ή ορίζει την x-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points. |
| [setX(float value)](#setX-float-) | Λαμβάνει ή ορίζει την x-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points. |
| [getY()](#getY--) | Λαμβάνει ή ορίζει την y-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points. |
| [setY(float value)](#setY-float-) | Λαμβάνει ή ορίζει την y-συντεταγμένη της επάνω-αριστερής γωνίας του σ shape, μετρημένη σε points. |
| [getWidth()](#getWidth--) | Λαμβάνει ή ορίζει το πλάτος του σ shape, μετρημένο σε points. |
| [setWidth(float value)](#setWidth-float-) | Λαμβάνει ή ορίζει το πλάτος του σ shape, μετρημένο σε points. |
| [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος του σ shape, μετρημένο σε points. |
| [setHeight(float value)](#setHeight-float-) | Λαμβάνει ή ορίζει το ύψος του σ shape, μετρημένο σε points. |
| [getAlternativeText()](#getAlternativeText--) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σ shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σ shape. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σ shape. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σ shape. |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα ενός σ shape. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός σ shape. |
| [isDecorative()](#isDecorative--) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' ανάγνωση/εγγραφή boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' ανάγνωση/εγγραφή boolean. |
| [getShapeLock()](#getShapeLock--) | Επιστρέφει τις κλειδώσεις του σ shape. |
| [getUniqueId()](#getUniqueId--) | Επιστρέφει έναν εσωτερικό, σε επίπεδο παρουσίασης, ταυτοποιητή προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Επιστρέφει έναν μοναδικό ταυτοποιητή σε επίπεδο διαφάνειας που παραμένει σταθερός για όλη τη διάρκεια ζωής του σ shape και επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρει αξιόπιστα το σ shape από οπουδήποτε στο έγγραφο. |
| [isGrouped()](#isGrouped--) | Καθορίζει αν το σ shape είναι ομαδοποιημένο. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σ shape σε λειτουργία ασπρόμαυρης προβολής. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σ shape σε λειτουργία ασπρόμαυρης προβολής. |
| [getParentGroup()](#getParentGroup--) | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σ shape είναι ομαδοποιημένο. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Επιστρέφει ένα βασικό σ shape placeholder (σ shape από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σ shape). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Καθορίζει αν το σ shape είναι TextHolder. Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Επιστρέφει το placeholder για ένα σ shape. Μόνο-ανάγνωση [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Επιστρέφει:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder to copy content from. |

**Επιστρέφει:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Ορίζει ότι αυτό το σ shape δεν είναι placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Επιστρέφει τα προσαρμοσμένα δεδομένα του σ shape. Μόνο-ανάγνωση [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σ shape. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ή
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Τέτοιος κώδικας μπορεί να οδηγήσει σε ασαφείς καταστάσεις. Έτσι προστέθηκαν περιορισμοί για τη χρήση ακαθορισμένων τιμών για το IShape.getFrame(). Οι τιμές των x, y, width, height, flipH, flipV και rotationAngle πρέπει να είναι ορισμένες (όχι Float.NaN ή NullableBool.NotDefined). Ο παραπάνω κώδικας τώρα ρίχνει εξαίρεση ArgumentException.
>  //Αυτό ισχύει για τις ακόλουθες χρήσεις:
>  IShape shape = ...;
>  shape.setFrame(...); // δεν μπορεί να είναι ακαθόριστο
>  IShapeCollection shapes = ...;
>  //παράμετροι x, y, width, height δεν μπορούν να είναι Float.NaN:
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
>  IShape shape = ...; // το σ shape είναι συνδεδεμένο με placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // τώρα το σ shape κληρονομεί τις τιμές x, y, height, flipH, flipV από το placeholder και παρακάμπτει το width=100 και rotationAngle=0.
```

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σ shape. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ή
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Τέτοιος κώδικας μπορεί να οδηγήσει σε ασαφείς καταστάσεις. Έτσι προστέθηκαν περιορισμοί για τη χρήση ακαθόριστων τιμών για IShape.getFrame(). Οι τιμές των x, y, width, height, flipH, flipV και rotationAngle πρέπει να είναι ορισμένες (όχι Float.NaN ή NullableBool.NotDefined). Ο παραπάνω κώδικας τώρα ρίχνει εξαίρεση ArgumentException.
>  //Αυτό ισχύει για τις ακόλουθες περιπτώσεις:
>  IShape shape = ...;
>  shape.setFrame(...); // δεν μπορεί να είναι ακαθόριστο
>  IShapeCollection shapes = ...;
>  //παράμετροι x, y, width, height δεν μπορούν να είναι Float.NaN:
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
>  IShape shape = ...; // το σ shape είναι συνδεδεμένο με placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // τώρα το σ shape κληρονομεί τις τιμές x, y, height, flipH, flipV από το placeholder και παρακάμπτει το width=100 και rotationAngle=0.
```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σ shape. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Η τιμή κάθε ιδιότητας του επιστρεφόμενου παραδείγματος IShapeFrame δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας του ανατεθειμένου παραδείγματος IShapeFrame πρέπει να μην είναι undefined (πρέπει να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σ shape. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Η τιμή κάθε ιδιότητας του επιστρεφόμενου παραδείγματος IShapeFrame δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας του ανατεθειμένου παραδείγματος IShapeFrame πρέπει να μην είναι undefined (πρέπει να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σ shape. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες μορφοποίησης τρισδιάστατου για ένα σ shape. Μόνο-ανάγνωση [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Επιστρέφει:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σ shape. Μόνο-ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σ shape. Μόνο-ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Επιστρέφει τη θέση ενός σ shape στην κατάταξη z. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σ shape. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σ shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόμετρη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόμετρη περιστροφή. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη (δεν είναι Float.NaN). Η ανατεθειμένη τιμή πρέπει να είναι ορισμένη (δεν είναι Float.NaN). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Επιστρέφει:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σ shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόμετρη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόμετρη περιστροφή. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα ορισμένη (δεν είναι Float.NaN). Η ανατεθειμένη τιμή πρέπει να είναι ορισμένη (δεν είναι Float.NaN). Μπορείτε να ορίσετε undefined τιμές για τις ιδιότητες του RawFrame.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Λαμβάνει ή ορίζει την x-συντεταγμένη της επάνω-αριστερής γωνίας του σ shape, μετρημένη σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Λαμβάνει ή ορίζει την x-συντεταγμένη της επάνω-αριστερής γωνίας του σ shape, μετρημένη σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Λαμβάνει ή ορίζει την y-συντεταγμένη της επάνω-αριστερής γωνίας του σ shape, μετρημένη σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Λαμβάνει ή ορίζει την y-συντεταγμένη της επάνω-αριστερής γωνίας του σ shape, μετρημένη σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Λαμβάνει ή ορίζει το πλάτος του σ shape, μετρημένο σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Λαμβάνει ή ορίζει το πλάτος του σ shape, μετρημένο σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Λαμβάνει ή ορίζει το ύψος του σ shape, μετρημένο σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Επιστρέφει:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Λαμβάνει ή ορίζει το ύψος του σ shape, μετρημένο σε points. Ανάγνωση/εγγραφή float.

--------------------

Η τιμή που επιστρέφεται είναι πάντα ορισμένη και ποτέ Float.NaN. Η τιμή που ανατίθεται πρέπει επίσης να είναι ορισμένη· αναθέστε Float.NaN μόνο σε ιδιότητες ενός RawFrame.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' ανάγνωση/εγγραφή boolean.

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

Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative' ανάγνωση/εγγραφή boolean.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Επιστρέφει τις κλειδώσεις του σ shape. Μόνο-ανάγνωση [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Επιστρέφει:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Επιστρέφει έναν εσωτερικό, σε επίπεδο παρουσίασης, ταυτοποιητή προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση long. Δείτε επίσης \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Επιστρέφει:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public



```

Επιστρέφει έναν μοναδικό ταυτοποιητή σε επίπεδο διαφάνειας που παραμένει σταθερός για όλη τη διάρκεια ζωής του σ shape και επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρει αξιόπιστα το σ shape από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση long. Δείτε επίσης \#getUniqueId.getUniqueId.

**Επιστρέφει:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Καθορίζει αν το σ shape είναι ομαδοποιημένο. Μόνο-ανάγνωση boolean.

--------------------

Η ιδιότητα \#getParentGroup.getParentGroup επιστρέφει το αντικείμενο GroupShape γονέα εάν το σ shape είναι ομαδοποιημένο.

**Επιστρέφει:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σ shape σε λειτουργία ασπρόμαυρης προβολής. Ανάγνωση/εγγραφή [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Επιστρέφει:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σ shape σε λειτουργία ασπρόμαυρης προβολής. Ανάγνωση/εγγραφή [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σ shape είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [IGroupShape](../../com.aspose.slides/igroupshape).

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
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
> // λάβετε όλα τα (master/layout/slide) κινούμενα εφέ του placeholder shape
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

Μια τιμή null επιστρέφεται εάν το τρέχον σ shape δεν κληρονομείται.

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)