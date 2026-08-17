---
title: AutoShape
second_title: Référence de l'API Aspose.Slides pour Java
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

Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture booléen.

**Renvoie :**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture booléen.

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
>  // Instancie la présentation
>  Presentation pres = new Presentation();
>  try {
>      // Récupère la première diapositive de la présentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Ajoute une AutoShape avec le type défini comme Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Ajoute un TextFrame au Rectangle
>      ashp.addTextFrame(" ");
>      // Accède au cadre de texte
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Crée l'objet Paragraph pour le cadre de texte
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Crée un objet Portion pour le paragraphe
>      IPortion portion = para.getPortions().get_Item(0);
>      // Définit le texte
>      portion.setText("Aspose TextBox");
>      // Enregistre la présentation sur le disque
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Récupère la première diapositive de la présentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Ajoute une AutoShape avec le type défini comme Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Ajoute un TextFrame au Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Récupère le format du texte du TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Spécifie le nombre de colonnes dans le TextFrame
>      format.setColumnCount(3);
>      // Spécifie l'espacement entre les colonnes
>      format.setColumnSpacing(10);
>      // Enregistre la présentation
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte par défaut pour un nouveau TextFrame. |

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Spécifie si la forme est une zone de texte.

--------------------

Si la forme n'est pas spécifiée comme zone de texte, cela ne signifie pas qu'elle ne peut pas contenir de texte. Une zone de texte n'est qu'une forme spécialisée avec des propriétés spécifiques.

**Renvoie :**
boolean