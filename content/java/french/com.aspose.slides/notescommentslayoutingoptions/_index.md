---
title: NotesCommentsLayoutingOptions
second_title: Référence API Aspose.Slides for Java
description: Fournit des options qui contrôlent l'apparence de la mise en page des notes et des commentaires dans le document exporté.
type: docs
url: /fr/com.aspose.slides/notescommentslayoutingoptions/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
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
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Obtient ou définit la couleur de la zone des commentaires (S'applique uniquement si les commentaires sont affichés à droite). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Obtient ou définit la couleur de la zone des commentaires (S'applique uniquement si les commentaires sont affichés à droite). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (S'applique uniquement si les commentaires sont affichés à droite). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (S'applique uniquement si les commentaires sont affichés à droite). |
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

**Retour :**
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

Par défaut, **NotesPositions.None**.

**Retour :**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Obtient ou définit la position des notes sur la page.

--------------------

Par défaut, **NotesPositions.None**.

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

Par défaut, **CommentsPositions.None**.

**Retour :**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Obtient ou définit la position des commentaires sur la page.

--------------------

Par défaut, **CommentsPositions.None**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```


Obtient ou définit la couleur de la zone des commentaires (S'applique uniquement si les commentaires sont affichés à droite).

--------------------

Par défaut, **Color.SkyBlue**.

**Retour :**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```


Obtient ou définit la couleur de la zone des commentaires (S'applique uniquement si les commentaires sont affichés à droite).

--------------------

Par défaut, **Color.SkyBlue**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (S'applique uniquement si les commentaires sont affichés à droite).

--------------------

La valeur minimale et par défaut est **150**.

**Retour :**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Obtient ou définit la largeur de la zone de sortie des commentaires en pixels (S'applique uniquement si les commentaires sont affichés à droite).

--------------------

La valeur minimale et par défaut est **150**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |