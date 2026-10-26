---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Fournit des options qui contrôlent l'apparence de la mise en page des notes et des commentaires dans le document exporté.
type: docs
url: /fr/com.aspose.slides/notescommentslayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Fournit des options qui contrôlent l'apparence de la mise en page des notes et des commentaires dans le document exporté.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Constructeur par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Obtient ou définit la visibilité des commentaires qui n'ont pas d'auteur. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Obtient ou définit la visibilité des commentaires qui n'ont pas d'auteur. |
| [getNotesPosition()](#getNotesPosition--) | Obtient ou définit la position des notes sur la page. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Obtient ou définit la position des notes sur la page. |
| [getCommentsPosition()](#getCommentsPosition--) | Obtient ou définit la position des commentaires sur la page. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Obtient ou définit la position des commentaires sur la page. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Obtient ou définit la couleur de la zone des commentaires (s'applique uniquement si les commentaires sont affichés à droite). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Obtient ou définit la couleur de la zone des commentaires (s'applique uniquement si les commentaires sont affichés à droite). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (s'applique uniquement si les commentaires sont affichés à droite). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (s'applique uniquement si les commentaires sont affichés à droite). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Constructeur par défaut.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Obtient ou définit la visibilité des commentaires qui n'ont pas d'auteur. Si vrai, les commentaires seront affichés. (S'applique uniquement si les commentaires sont affichés).

--------------------

La valeur par défaut est **false**.

**Retourne :**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Obtient ou définit la visibilité des commentaires qui n'ont pas d'auteur. Si vrai, les commentaires seront affichés. (S'applique uniquement si les commentaires sont affichés).

--------------------

La valeur par défaut est **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Obtient ou définit la position des notes sur la page.

--------------------

La valeur par défaut est **NotesPositions.None**.

**Retourne :**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Obtient ou définit la position des notes sur la page.

--------------------

La valeur par défaut est **NotesPositions.None**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Obtient ou définit la position des commentaires sur la page.

--------------------

La valeur par défaut est **CommentsPositions.None**.

**Retourne :**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Obtient ou définit la position des commentaires sur la page.

--------------------

La valeur par défaut est **CommentsPositions.None**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


Obtient ou définit la couleur de la zone des commentaires (s'applique uniquement si les commentaires sont affichés à droite).

--------------------

La valeur par défaut est **SkyBlue**.

**Retourne :**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


Obtient ou définit la couleur de la zone des commentaires (s'applique uniquement si les commentaires sont affichés à droite).

--------------------

La valeur par défaut est **SkyBlue**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (s'applique uniquement si les commentaires sont affichés à droite).

--------------------

La valeur minimale et par défaut est **150**.

**Retourne :**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (s'applique uniquement si les commentaires sont affichés à droite).

--------------------

La valeur minimale et par défaut est **150**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |