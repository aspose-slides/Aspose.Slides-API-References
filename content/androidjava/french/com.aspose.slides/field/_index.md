---
title: Field
second_title: Référence de l'API Java pour Aspose.Slides sur Android
description: Représente un champ.
type: docs
url: /fr/com.aspose.slides/field/
---
**Héritage:**  
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IField](../../com.aspose.slides/ifield)  
```
public final class Field extends DomObject<Portion> implements IField
```

Représente un champ.  
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie ou définit le type du champ. |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | Renvoie ou définit le type du champ. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'un paragraphe. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'un paragraphe. |
### getType() {#getType--}
```
public final IFieldType getType()
```

Renvoie ou définit le type du champ. Lecture/écriture [IFieldType](../../com.aspose.slides/ifieldtype).

**Renvoie:**  
[IFieldType](../../com.aspose.slides/ifieldtype)
### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```

Renvoie ou définit le type du champ. Lecture/écriture [IFieldType](../../com.aspose.slides/ifieldtype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parente d'un paragraphe. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente d'un paragraphe. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie:**  
[IPresentation](../../com.aspose.slides/ipresentation)