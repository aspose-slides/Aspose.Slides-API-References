---
title: ModernComment
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un commentaire sur une diapositive.
type: docs
url: /fr/com.aspose.slides/moderncomment/
---
**Héritage :**  
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject  
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
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
| [getTextSelectionStart()](#getTextSelectionStart--) | Obtient ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Obtient ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Obtient ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Obtient ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. |
| [getStatus()](#getStatus--) | Obtient ou définit l'état du commentaire. |
| [setStatus(byte value)](#setStatus-byte-) | Obtient ou définit l'état du commentaire. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

Renvoie une forme associée au commentaire. Lecture seule [IShape](../../com.aspose.slides/ishape).

**Renvoie:**  
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Obtient ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Renvoie:**  
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Obtient ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Obtient ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Renvoie:**  
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Obtient ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à AutoShape. Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Obtient ou définit l'état du commentaire. Lecture/écriture [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Renvoie:**  
byte

### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Obtient ou définit l'état du commentaire. Lecture/écriture [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie:**  
com.aspose.slides.IDOMObject