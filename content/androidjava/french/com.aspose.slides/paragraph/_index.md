---
title: Paragraph
second_title: Référence API Java pour Aspose.Slides for Android
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
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Constructeur de copie qui initialise une nouvelle instance d’une classe Paragraph. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Renvoie la collection de portions de texte. |
| [getParagraphFormat()](#getParagraphFormat--) | Renvoie l’objet de formatage pour ce paragraphe. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les runs avec le même formatage. |
| [getText()](#getText--) | Obtient ou définit le texte brut d’un paragraphe. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d’un paragraphe. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui encadre le paragraphe. |
| [getLinesCount()](#getLinesCount--) | Obtient le nombre de lignes d’un paragraphe. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Spécifie les propriétés de la portion à utiliser si une autre portion est insérée après la dernière. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Spécifie les propriétés de la portion à utiliser si une autre portion est insérée après la dernière. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d’un paragraphe. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d’un paragraphe. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Initialise une nouvelle instance de la classe Paragraph avec les propriétés par défaut.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Constructeur de copie qui initialise une nouvelle instance d’une classe Paragraph.

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

Renvoie l’objet de formatage pour ce paragraphe. Lecture seule [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

L’objet de formatage contient les paramètres de formatage définis uniquement pour le paragraphe actuel, les données héritées n’étant pas appliquées.

Pour obtenir les valeurs effectives incluant celles héritées, utilisez la méthode [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Renvoie :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Fusionne les runs avec le même formatage.

### getText() {#getText--}
```
public final String getText()
```

Obtient ou définit le texte brut d’un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Renvoie :**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Obtient ou définit le texte brut d’un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Obtient les coordonnées du rectangle qui encadre le paragraphe. Le rectangle comprend toutes les lignes de texte du paragraphe, y compris les lignes vides.

**Renvoie :**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Obtient le nombre de lignes d’un paragraphe.

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

**Returns:**
int - Lines count in a paragraph
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a paragraph. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()


Renvoie la présentation parent d’un paragraphe. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)