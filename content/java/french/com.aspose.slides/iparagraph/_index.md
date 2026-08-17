---
title: IParagraph
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un paragraphe de texte.
type: docs
url: /fr/com.aspose.slides/iparagraph/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Représente un paragraphe de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Renvoie la collection des portions de texte. |
| [getParagraphFormat()](#getParagraphFormat--) | Renvoie l'objet de mise en forme pour ce paragraphe. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joint les segments avec la même mise en forme. |
| [getText()](#getText--) | Obtient ou définit le texte brut d'un paragraphe. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d'un paragraphe. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui délimite le paragraphe. |
| [getLinesCount()](#getLinesCount--) | Obtient le nombre de lignes d'un paragraphe. |
| [getImage()](#getImage--) | Renvoie une image du paragraphe. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Renvoie une image du paragraphe avec l'échelle spécifiée. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Spécifie les propriétés de la portion qui seront utilisées si une autre portion est insérée après la dernière. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Spécifie les propriétés de la portion qui seront utilisées si une autre portion est insérée après la dernière. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Renvoie la collection des portions de texte. Lecture seule [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retourne :**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Renvoie l'objet de mise en forme pour ce paragraphe. Lecture seule [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retourne :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Joint les segments avec la même mise en forme.

### getText() {#getText--}
```
public abstract String getText()
```

Obtient ou définit le texte brut d'un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Retourne :**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtient ou définit le texte brut d'un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Obtient les coordonnées du rectangle qui délimite le paragraphe. Le rectangle inclut toutes les lignes de texte du paragraphe, y compris les lignes vides.

**Retourne :**
java.awt.geom.Rectangle2D.Float - Rectangle qui délimite le paragraphe java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

Obtient le nombre de lignes d'un paragraphe.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
int - Nombre de lignes dans un paragraphe
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Renvoie une image du paragraphe.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
[IImage](../../com.aspose.slides/iimage) - Une image contenant le paragraphe rendu, ou null si le paragraphe ne peut être trouvé dans sa collection parente, n'a pas de limites de rendu valides, ou si une erreur se produit lors du rendu de l'image.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Renvoie une image du paragraphe avec l'échelle spécifiée.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | float | Le facteur d'échelle horizontal appliqué à l'image du paragraphe. |
| scaleY | float | Le facteur d'échelle vertical appliqué à l'image du paragraphe. |

**Retourne :**
[IImage](../../com.aspose.slides/iimage) - Une image contenant le paragraphe rendu, ou null si le paragraphe ne peut être trouvé dans sa collection parente, n'a pas de limites de rendu valides, ou si une erreur se produit lors du rendu de l'image.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Spécifie les propriétés de la portion qui seront utilisées si une autre portion est insérée après la dernière.

**Retourne :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Spécifie les propriétés de la portion qui seront utilisées si une autre portion est insérée après la dernière.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |