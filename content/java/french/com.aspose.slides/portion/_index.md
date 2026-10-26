---
title: Portion
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une portion de texte à l'intérieur d'un paragraphe.
type: docs
url: /fr/com.aspose.slides/portion/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Représente une partie de texte à l'intérieur d'un paragraphe.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Portion()](#Portion--) | Initialise une nouvelle instance de la classe Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Initialise une nouvelle instance de la classe Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Initialise une nouvelle instance de la classe Portion. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Renvoie l'objet de mise en forme qui contient les propriétés de formatage explicitement définies de la portion de texte, sans héritage appliqué. |
| [getText()](#getText--) | Obtient ou définit le texte brut d'une portion. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d'une portion. |
| [getField()](#getField--) | Renvoie un champ de cette portion. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Convertit cette portion en champ mis à jour automatiquement. |
| [addField(String internalString)](#addField-java.lang.String-) | Convertit cette portion en champ mis à jour automatiquement. |
| [removeField()](#removeField--) | Convertit cette portion de champ en portion simple. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui encadre la portion. |
| [getCoordinates()](#getCoordinates--) | Obtient les coordonnées du début de la portion. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente du texte. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente du texte. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Initialise une nouvelle instance de la classe Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Initialise une nouvelle instance de la classe Portion.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Initialise une nouvelle instance de la classe Portion.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Renvoie l'objet de mise en forme qui contient les propriétés de formatage explicitement définies de la portion de texte, sans héritage appliqué. Lecture seule [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

L'objet de mise en forme contient les paramètres de formatage définis uniquement pour la portion actuelle, les données héritées ne sont pas appliquées.

Afin d'obtenir les valeurs effectives incluant celles héritées, utilisez la méthode [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Renvoie :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : Le texte.

**Renvoie :**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : Le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Renvoie un champ de cette portion. Lecture seule [IField](../../com.aspose.slides/ifield).

**Renvoie :**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Convertit cette portion en champ mis à jour automatiquement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Convertit cette portion en champ mis à jour automatiquement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| internalString | java.lang.String | Nom interne du FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Convertit cette portion de champ en portion simple.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Obtient les coordonnées du rectangle qui encadre la portion. Le rectangle inclut toutes les lignes de texte de la portion, y compris les lignes vides.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
> {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(1).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Obtient les coordonnées du début de la portion. La coordonnée X du point représente le début de la portion depuis le premier caractère, y compris le débordement latéral gauche. La coordonnée Y inclut le débordement supérieur.

**Renvoie :**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parente du texte. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente du texte. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject