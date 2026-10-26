---
title: Paragraph
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un paragraphe de texte.
type: docs
url: /fr/com.aspose.slides/paragraph/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Représente un paragraphe de texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initialise une nouvelle instance de la classe Paragraph avec les propriétés par défaut. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Constructeur de copie qui initialise une nouvelle instance de la classe Paragraph. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Renvoie la collection de portions de texte. |
| [getParagraphFormat()](#getParagraphFormat--) | Renvoie l'objet de mise en forme pour ce paragraphe. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joint les runs avec la même mise en forme. |
| [getText()](#getText--) | Obtient ou définit le texte simple d'un paragraphe. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte simple d'un paragraphe. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui encadre le paragraphe. |
| [getLinesCount()](#getLinesCount--) | Obtient le nombre de lignes dans un paragraphe. |
| [getImage()](#getImage--) | Renvoie une image du paragraphe. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Renvoie une image du paragraphe avec l'échelle spécifiée. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Spécifie les propriétés de la portion qui doivent être utilisées si une autre portion est insérée après la dernière. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Spécifie les propriétés de la portion qui doivent être utilisées si une autre portion est insérée après la dernière. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'un paragraphe. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'un paragraphe. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Initialise une nouvelle instance de la classe Paragraph avec les propriétés par défaut.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Constructeur de copie qui initialise une nouvelle instance de la classe Paragraph.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Renvoie la collection de portions de texte. Lecture seule [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Renvoie :**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Renvoie l'objet de mise en forme pour ce paragraphe. Lecture seule [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

L'objet de mise en forme contient les paramètres de mise en forme définis uniquement pour le paragraphe actuel, les données héritées ne sont pas appliquées.

Afin d'obtenir les valeurs effectives incluant les héritées, utilisez la méthode [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Renvoie :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Joint les runs avec la même mise en forme.

### getText() {#getText--}
```
public final String getText()
```


Obtient ou définit le texte simple d'un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Renvoie :**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtient ou définit le texte simple d'un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


Obtient les coordonnées du rectangle qui encadre le paragraphe. Le rectangle comprend toutes les lignes de texte du paragraphe, y compris les lignes vides.

**Renvoie :**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Obtient le nombre de lignes dans un paragraphe.

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


**Renvoie :**
int - Nombre de lignes dans un paragraphe
### getImage() {#getImage--}
```
public final IImage getImage()
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


**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Une image contenant le paragraphe rendu, ou null si le paragraphe ne peut pas être trouvé dans sa collection parent, n'a pas de limites de rendu valides, ou si une erreur survient lors du rendu de l'image.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
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

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Une image contenant le paragraphe rendu, ou null si le paragraphe ne peut pas être trouvé dans sa collection parent, n'a pas de limites de rendu valides, ou si une erreur survient lors du rendu de l'image.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Spécifie les propriétés de la portion qui doivent être utilisées si une autre portion est insérée après la dernière.

**Renvoie :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Spécifie les propriétés de la portion qui doivent être utilisées si une autre portion est insérée après la dernière.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Renvoie la diapositive parente d'un paragraphe. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Renvoie la présentation parente d'un paragraphe. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)