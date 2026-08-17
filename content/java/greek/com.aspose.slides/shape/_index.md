---
title: Shape
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/shape/
---
**Κληρονομία:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Καθορίζει αν το σχήμα είναι TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Επιστρέφει το placeholder για ένα σχήμα. |
| [removePlaceholder()](#removePlaceholder--) | Καθορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σχήμα). |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. |
| [getRawFrame()](#getRawFrame--) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. |
| [getFrame()](#getFrame--) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. |
| [getThreeDFormat()](#getThreeDFormat--) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες τρισδιάστατου εφέ για ένα σχήμα. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. |
| [getImage()](#getImage--) | Επιστρέφει μικρογραφία σχήματος. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Επιστρέφει μικρογραφία σχήματος. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. |
| [getHidden()](#getHidden--) | Καθορίζει αν το σχήμα είναι κρυμμένο. |
| [setHidden(boolean value)](#setHidden-boolean-) | Καθορίζει αν το σχήμα είναι κρυμμένο. |
| [getZOrderPosition()](#getZOrderPosition--) | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. |
| [getRotation()](#getRotation--) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. |
| [setRotation(float value)](#setRotation-float-) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. |
| [getX()](#getX--) | Παίρνει ή ορίζει την x-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. |
| [setX(float value)](#setX-float-) | Παίρνει ή ορίζει την x-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. |
| [getY()](#getY--) | Παίρνει ή ορίζει την y-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. |
| [setY(float value)](#setY-float-) | Παίρνει ή ορίζει την y-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. |
| [getWidth()](#getWidth--) | Παίρνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. |
| [setWidth(float value)](#setWidth-float-) | Παίρνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. |
| [getHeight()](#getHeight--) | Παίρνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. |
| [setHeight(float value)](#setHeight-float-) | Παίρνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Η ιδιότητα καθορίζει πώς θα αποδιδόταν ένα σχήμα σε λειτουργία μονόχρωμης εμφάνισης. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Η ιδιότητα καθορίζει πώς θα αποδιδόταν ένα σχήμα σε λειτουργία μονόχρωμης εμφάνισης. |
| [getUniqueId()](#getUniqueId--) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίατα ταυτοποιητή που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Επιστρέφει έναν μοναδικό ταυτοποιητή περιορισμένο στη διαφάνεια που παραμένει σταθερός για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα διαλειτουργικότητας να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο. |
| [getAlternativeText()](#getAlternativeText--) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. |
| [isDecorative()](#isDecorative--) | Παίρνει ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό' (Ανάγνωση/εγγραφή) boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Παίρνει ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό' (Ανάγνωση/εγγραφή) boolean. |
| [getShapeLock()](#getShapeLock--) | Επιστρέφει τις κλειδώσεις του σχήματος. |
| [isGrouped()](#isGrouped--) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. |
| [getParentGroup()](#getParentGroup--) | Επιστρέφει το αντικείμενο γονέα GroupShape εάν το σχήμα είναι ομαδοποιημένο. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Παίρνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενό του. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Καθορίζει αν το σχήμα είναι TextHolder_PPT. Μόνο-ανάγνωση  boolean .

**Επιστρέφει:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο-ανάγνωση [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instantiates a Presentation class
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accesses the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Iterates through shapes to find the placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Changes the text in each placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Saves the presentation to disk
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Iterates through the slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint displays "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Adds subtitle
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Καθορίζει ότι αυτό το σχήμα δεν είναι placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder από το οποίο αντιγράφονται τα περιεχόμενα. |

**Επιστρέφει:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Νέα #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σχήμα).

--------------------

> ```
> // Λάβετε όλα τα (master/layout/slide) κινούμενα εφέ του σχήματος placeholder
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

Επιστρέφεται null εάν το τρέχον σχήμα δεν είναι κληρονομημένο.

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
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
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
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
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Η τιμή κάθε ιδιότητας της επιστρεφόμενης παρουσίας IShapeFrame δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας της ανατεθειμένης παρουσίας IShapeFrame πρέπει να μην είναι undefined (να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε τιμές undefined για τις ιδιότητες της παρουσίας RawFrame.

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Η τιμή κάθε ιδιότητας της επιστρεφόμενης παρουσίας IShapeFrame δεν είναι undefined (δεν είναι NaN ή NotDefined). Η τιμή κάθε ιδιότητας της ανατεθειμένης παρουσίας IShapeFrame πρέπει να μην είναι undefined (να μην είναι NaN ή NotDefined). Μπορείτε να ορίσετε τιμές undefined για τις ιδιότητες της παρουσίας RawFrame.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες τρισδιάστατου εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες τρισδιάστατου. Μόνο-ανάγνωση [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Επιστρέφει:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο-ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο-ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Επιστρέφει μικρογραφία σχήματος. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Μικρογραφία σχήματος.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Επιστρέφει μικρογραφία σχήματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bounds | int | Τύπος ορίων μικρογραφίας σχήματος. |
| scaleX | float | Κλίμακα X |
| scaleY | float | Κλίμακα Y |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Μικρογραφία σχήματος ή null σε περίπτωση που χρησιμοποιείται ShapeThumbnailBounds.Appearance και το σχήμα δεν έχει ορατά στοιχεία.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Επιλογές δημιουργίας SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Επιστρέφει ή ορίζει το υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο-ανάγνωση [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Επιστρέφει:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Καθορίζει αν το σχήμα είναι κρυμμένο. Ανάγνωση/εγγραφή  boolean .

**Επιστρέφει:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Καθορίζει αν το σχήμα είναι κρυμμένο. Ανάγνωση/εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο παρασκήνιο της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στην κορυφή της σειράς z. Μόνο-ανάγνωση  int .

**Επιστρέφει:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση  int .

**Επιστρέφει:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή float.

--------------------

Η επιστρεφόμενη τιμή είναι πάντα καθορισμένη (δεν είναι Float.NaN). Η τιμή που ανατίθεται πρέπει να είναι καθορισμένη (να μην είναι Float.NaN). Μπορείτε να ορίσετε τιμές undefined για τις ιδιότητες της παρουσίας RawFrame.

**Επιστρέφει:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Ανακτά ή ορίζει το x-συντεταγμένο της άνω-αριστερής γωνίας του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Επιστρέφει:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Ανακτά ή ορίζει το x-συντεταγμένο της άνω-αριστερής γωνίας του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Ανακτά ή ορίζει το y-συντεταγμένο της άνω-αριστερής γωνίας του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Επιστρέφει:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Ανακτά ή ορίζει το y-συντεταγμένο της άνω-αριστερής γωνίας του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Ανακτά ή ορίζει το πλάτος του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Επιστρέφει:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Ανακτά ή ορίζει το πλάτος του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Ανακτά ή ορίζει το ύψος του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Επιστρέφει:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Ανακτά ή ορίζει το ύψος του σχήματος, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Επιστρέφει:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Επιστρέφει:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only long. See also \#getUniqueId.getUniqueId.

**Επιστρέφει:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Returns or sets the alternative text associated with a shape. Read/write String.

**Επιστρέφει:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Returns or sets the alternative text associated with a shape. Read/write String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Returns or sets the title of alternative text associated with a shape. Read/write String.

**Επιστρέφει:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Returns or sets the title of alternative text associated with a shape. Read/write String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Gets or sets 'Mark as decorative' option Read/write boolean.

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
public final void setDecorative(boolean value)
```

Gets or sets 'Mark as decorative' option Read/write boolean.

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
public IBaseShapeLock getShapeLock()
```

Returns shape's locks. Read-only [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Επιστρέφει:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determines whether the shape is grouped. Read-only boolean.

--------------------

Property #getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Επιστρέφει:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property #isGrouped.isGrouped determines whether the shape is grouped.

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent_Immediate object. Read-only IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Gets the visual bounds of the shape calculated from its rendered content.

**Επιστρέφει:**
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float that represents the visual bounds of the shape in slide coordinates.

--------------------

The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space. These bounds may differ from the shape's model bounds #getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float) and may contain negative coordinates if the rendered content extends beyond the slide origin. The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, SmartArt geometry, and other layout effects that influence the final rendered appearance of the shape. The returned bounds are not clipped to the slide rectangle.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a shape. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a slide. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)