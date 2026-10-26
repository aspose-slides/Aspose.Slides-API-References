---
title: IModernComment
second_title: Référence API Aspose.Slides pour Java
description: Représente un commentaire sur une diapositive.
type: docs
url: /fr/com.aspose.slides/imoderncomment/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Représente un commentaire sur une diapositive.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getShape()](#getShape--) | Renvoie une forme associée au commentaire. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Renvoie ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Renvoie ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Renvoie ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Renvoie ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [getStatus()](#getStatus--) | Renvoie ou définit l'état du commentaire. |
| [setStatus(byte value)](#setStatus-byte-) | Renvoie ou définit l'état du commentaire. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Renvoie une forme associée au commentaire. Lecture seule [IShape](../../com.aspose.slides/ishape).

**Renvoie :**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Renvoie ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Renvoie :**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Renvoie ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Renvoie ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Renvoie :**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Renvoie ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Renvoie ou définit l'état du commentaire. Lecture/écriture [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Renvoie :**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Renvoie ou définit l'état du commentaire. Lecture/écriture [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |