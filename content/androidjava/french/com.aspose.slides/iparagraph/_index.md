---
title: IParagraph
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente un paragraphe de texte.
type: docs
url: /fr/com.aspose.slides/iparagraph/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Représente un paragraphe de texte.  
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Renvoie la collection des portions de texte. |
| [getParagraphFormat()](#getParagraphFormat--) | Renvoie l’objet de mise en forme pour ce paragraphe. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les portions avec la même mise en forme. |
| [getText()](#getText--) | Obtient ou définit le texte brut d’un paragraphe. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d’un paragraphe. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui encadre le paragraphe. |
| [getLinesCount()](#getLinesCount--) | Obtient le nombre de lignes d’un paragraphe. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Spécifie les propriétés de la portion à utiliser si une autre portion est insérée après la dernière. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Spécifie les propriétés de la portion à utiliser si une autre portion est insérée après la dernière. |

### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Renvoie la collection des portions de texte. Lecture seule [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retour :**  
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Renvoie l’objet de mise en forme pour ce paragraphe. Lecture seule [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retour :**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Fusionne les portions avec la même mise en forme.

### getText() {#getText--}
```
public abstract String getText()
```

Obtient ou définit le texte brut d’un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Retour :**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtient ou définit le texte brut d’un paragraphe. Lecture/écriture String.

Valeur : Le texte.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Obtient les coordonnées du rectangle qui encadre le paragraphe. Le rectangle comprend toutes les lignes de texte du paragraphe, y compris les lignes vides.

**Retour :**  
android.graphics.RectF - Rectangle qui encadre le paragraphe android.graphics.RectF

### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)

Spécifie les propriétés de la portion à utiliser si une autre portion est insérée après la dernière.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |