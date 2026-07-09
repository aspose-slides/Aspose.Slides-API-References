---
title: Portion
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente une partie de texte à l'intérieur d'un paragraphe de texte.
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

Représente une partie de texte à l'intérieur d'un paragraphe de texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Portion()](#Portion--) | Initialise une nouvelle instance de la classe Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Initialise une nouvelle instance de la classe Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Initialise une nouvelle instance de la classe Portion. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Renvoie l'objet de formatage qui contient les propriétés de formatage définies explicitement de la portion de texte sans appliquer l'héritage. |
| [getText()](#getText--) | Obtient ou définit le texte brut d'une portion. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d'une portion. |
| [getField()](#getField--) | Renvoie un champ de cette portion. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Convertit cette portion en champ automatiquement mis à jour. |
| [addField(String internalString)](#addField-java.lang.String-) | Convertit cette portion en champ automatiquement mis à jour. |
| [removeField()](#removeField--) | Convertit cette portion de champ en portion simple. |
| [getRect()](#getRect--) | Obtient les coordonnées du rectangle qui encadre la portion. |
| [getCoordinates()](#getCoordinates--) | Obtient les coordonnées du début de la portion. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'un texte. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'un texte. |
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

Renvoie l'objet de formatage qui contient les propriétés de formatage définies explicitement de la portion de texte sans appliquer l'héritage. Lecture seule [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

L'objet de formatage contient les paramètres de formatage définis uniquement pour la portion actuelle, les données héritées ne sont pas appliquées.

Afin d'obtenir les valeurs effectives y compris celles héritées, utilisez la méthode [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Renvoie :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : le texte.

**Renvoie :**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Obtient ou définit le texte brut d'une portion. Lecture/écriture String.

Valeur : le texte.

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

Convertit cette portion en champ automatiquement mis à jour.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Convertit cette portion en champ automatiquement mis à jour.

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
public final RectF getRect()
```

Obtient les coordonnées du rectangle qui encadre la portion. Le rectangle comprend toutes les lignes de texte de la portion, y compris les lignes vides.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```


Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing.

**Returns:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a text. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente d'un texte. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject