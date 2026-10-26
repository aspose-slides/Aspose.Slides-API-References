---
title: AutoShape
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une AutoShape.
type: docs
url: /fr/com.aspose.slides/autoshape/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Représente une AutoShape.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Renvoie les verrous de la forme. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Renvoie les verrous de l'autoshape. |
| [getTextFrame()](#getTextFrame--) | Renvoie l'objet TextFrame pour l'AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Ajoute un nouveau TextFrame à une forme. |
| [isTextBox()](#isTextBox--) | Spécifie si la forme est une zone de texte. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Renvoie les verrous de la forme. Lecture seule [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Renvoie :**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Renvoie les verrous de l'autoshape. Lecture seule [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Renvoie :**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Renvoie l'objet TextFrame pour l'AutoShape. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture boolean.

**Renvoie :**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Ajoute un nouveau TextFrame à une forme. Si la forme possède déjà un TextFrame, il modifie simplement son texte.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // Instantiates Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adds an AutoShape with type set as Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Adds TextFrame to the Rectangle
>      ashp.addTextFrame(" ");
>      // Accesses the text frame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Creates the Paragraph object for text frame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Creates a Portion object for the paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // Sets the text
>      portion.setText("Aspose TextBox");
>      // Saves the presentation to disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Add an AutoShape with type set as Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Add TextFrame to the Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Gets the text format of TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Specifies the number of columns in TextFrame
>      format.setColumnCount(3);
>      // Specifies the spacing between columns
>      format.setColumnSpacing(10);
>      // Saves the presentation
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Default text for a new TextFrame. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()

Spécifie si la forme est une zone de texte.

--------------------

Si la forme n'est pas spécifiée comme étant une zone de texte, cela ne signifie pas qu'elle ne peut pas contenir de texte. Une zone de texte n'est qu'une forme spécialisée avec des propriétés spécifiques.

**Renvoie :**
boolean