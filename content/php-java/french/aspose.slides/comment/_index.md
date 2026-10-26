---
title: Comment
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/comment/
---
## Comment classe

Représente un commentaire sur une diapositive.

### getAuthor {#getAuthor}

| Name | Description |
| --- | --- |
| getAuthor () | Renvoie l'auteur d'un commentaire. Lecture seule ICommentAuthor. |

**Returns:**
[CommentAuthor](../commentauthor)

---

### getCreatedTime {#getCreatedTime}

| Name | Description |
| --- | --- |
| getCreatedTime () | Renvoie ou définit l'heure de création d'un commentaire. Définir cette propriété à java.util.Date(Long.MIN_VALUE) signifie qu'aucune heure de commentaire n'est définie. Lecture/écriture java.util.Date. L'heure du commentaire est un paramètre optionnel. |

**Returns:**
Date

---

### getParentComment {#getParentComment}

| Name | Description |
| --- | --- |
| getParentComment () | Obtient ou définit le commentaire parent. Lecture/écriture IComment. |

**Returns:**
[Comment](../comment), [ModernComment](../moderncomment)

**Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancé lorsque la définition de la valeur entraîne une référence circulaire |

---

### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | Renvoie ou définit la position d'un commentaire sur une diapositive. Lecture/écriture java.awt.geom.Point2D.Float. |

**Returns:**
Point2D.Float

---

### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Renvoie ou définit la diapositive parent d'un commentaire. Lecture seule ISlide. |

**Returns:**
[Slide](../slide)

---

### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Renvoie ou définit le texte brut d'un commentaire de diapositive. Lecture/écriture String. |

**Returns:**
String

---

### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Supprime le commentaire et toutes ses réponses de la collection parente. |

**Returns:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancé si le commentaire est déjà supprimé |

---

### setCreatedTime {#setCreatedTime}

| Name | Description |
| --- | --- |
| setCreatedTime (Date) | Renvoie ou définit l'heure de création d'un commentaire. Définir cette propriété à java.util.Date(Long.MIN_VALUE) signifie qu'aucune heure de commentaire n'est définie. Lecture/écriture java.util.Date. L'heure du commentaire est un paramètre optionnel. |

**Returns:**
void

---

### setParentComment {#setParentComment}

| Name | Description |
| --- | --- |
| setParentComment ([Comment](../comment)) | Obtient ou définit le commentaire parent. Lecture/écriture IComment. |

**Returns:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancé lorsque la définition de la valeur entraîne une référence circulaire |

---

### setParentComment {#setParentComment}

| Name | Description |
| --- | --- |
| setParentComment ([ModernComment](../moderncomment)) | Obtient ou définit le commentaire parent. Lecture/écriture IComment. |

**Returns:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancé lorsque la définition de la valeur entraîne une référence circulaire |

---

### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (Point2D.Float) | Renvoie ou définit la position d'un commentaire sur une diapositive. Lecture/écriture java.awt.geom.Point2D.Float. |

**Returns:**
void

---

### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Renvoie ou définit le texte brut d'un commentaire de diapositive. Lecture/écriture String. |

**Returns:**
void

---