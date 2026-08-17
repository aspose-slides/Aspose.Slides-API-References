---
title: IPortion
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une portion de texte à l'intérieur d'un paragraphe.
type: docs
url: /fr/com.aspose.slides/iportion/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Représente une partie de texte à l'intérieur d'un paragraphe de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Renvoie l'objet de mise en forme qui contient les propriétés de mise en forme définies explicitement pour la portion de texte, sans aucune héritage appliqué. |
| [getText()](#getText--) | Obtient ou définit le texte brut d'une portion. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d'une portion. |
| [getField()](#getField--) | Renvoie un champ de cette portion. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Convertit cette portion en champ automatiquement mis à jour. |
| [addField(String internalString)](#addField-java.lang.String-) | Convertit cette portion en champ automatiquement mis à jour. |
| [removeField()](#removeField--) | Convertit cette portion de champ en portion simple. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui délimite la portion. |
| [getCoordinates()](#getCoordinates--) | Obtient les coordonnées du début de la portion. |

### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Renvoie l'objet de mise en forme qui contient les propriétés de mise en forme définies explicitement pour la portion de texte, sans aucune héritage appliqué. Lecture seule [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

L'objet de mise en forme contient les paramètres de mise en forme définis uniquement pour la portion actuelle, les données héritées ne sont pas appliquées.

Afin d'obtenir les valeurs effectives incluant celles héritées, utilisez la méthode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Retourne :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : Le texte.

**Retourne :**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : Le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

Renvoie un champ de cette portion. Lecture seule [IField](../../com.aspose.slides/ifield).

**Retourne :**
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

Convertit cette portion de champ en portion simple.

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Obtient les coordonnées du rectangle qui délimite la portion. Le rectangle comprend toutes les lignes de texte de la portion, y compris les lignes vides.

--------------------

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
java.awt.geom.Rectangle2D.Float - Rectangle qui délimite la portion java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

Obtient les coordonnées du début de la portion. La coordonnée X du point représente le début de la portion à partir du premier caractère, y compris le porté latéral gauche. La coordonnée Y inclut le porté supérieur.

**Retourne :**
java.awt.geom.Point2D.Float - Coordonnées du début de la portion java.awt.geom.Point2D.Float