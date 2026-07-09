---
title: IPortion
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une portion de texte à l'intérieur d'un paragraphe de texte.
type: docs
url: /fr/com.aspose.slides/iportion/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Représente une portion de texte à l'intérieur d'un paragraphe de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Renvoie l'objet de formatage qui contient les propriétés de formatage explicitement définies de la portion de texte sans héritage appliqué. |
| [getText()](#getText--) | Obtient ou définit le texte brut d'une portion. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d'une portion. |
| [getField()](#getField--) | Renvoie un champ de cette portion. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Convertit cette portion en champ automatiquement mis à jour. |
| [addField(String internalString)](#addField-java.lang.String-) | Convertit cette portion en champ automatiquement mis à jour. |
| [removeField()](#removeField--) | Convertit cette portion de champ en une portion simple. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui encadre la portion. |
| [getCoordinates()](#getCoordinates--) | Obtient les coordonnées du début de la portion. |

### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Renvoie l'objet de formatage qui contient les propriétés de formatage explicitement définies de la portion de texte sans héritage appliqué. Lecture seule [IPortionFormat](../../com.aspose.slides/iportionformat).

---

L'objet de formatage ne contient que les paramètres de formatage définis pour la portion actuelle, les données héritées ne sont pas appliquées.

Afin d'obtenir les valeurs effectives incluant celles héritées, utilisez la méthode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Retour :**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public abstract String getText()
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : le texte.

**Retour :**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

Renvoie un champ de cette portion. Lecture seule [IField](../../com.aspose.slides/ifield).

**Retour :**
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Convertit cette portion en champ automatiquement mis à jour.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Type de champ [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Convertit cette portion en champ automatiquement mis à jour.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| internalString | java.lang.String | Nom interne du FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```

Convertit cette portion de champ en une portion simple.

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Obtient les coordonnées du rectangle qui encadre la portion. Le rectangle comprend toutes les lignes de texte de la portion, y compris les lignes vides.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
android.graphics.RectF - Rectangle that bounds portion android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()

Obtient les coordonnées du début de la portion. La coordonnée X du point représente le début de la portion à partir du premier caractère, y compris la bordure latérale gauche. La coordonnée Y inclut la bordure supérieure.

**Retour :**
android.graphics.PointF - Coordonnées du début de la portion android.graphics.PointF