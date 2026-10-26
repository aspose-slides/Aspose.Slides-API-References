---
title: IAutoShape
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un AutoShape.
type: docs
url: /fr/com.aspose.slides/iautoshape/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Représente un AutoShape.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Renvoie les verrous d'AutoShape. |
| [getTextFrame()](#getTextFrame--) | Renvoie l'objet TextFrame pour AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Ajoute un nouveau TextFrame à une forme. |
| [isTextBox()](#isTextBox--) | Spécifie si la forme est une zone de texte. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Renvoie les verrous d'AutoShape. Lecture seule [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Renvoie :**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Renvoie l'objet TextFrame pour AutoShape. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture booléen.

**Renvoie :**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Ajoute un nouveau TextFrame à une forme. Si la forme possède déjà un TextFrame, il change simplement son texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte par défaut pour le nouveau TextFrame. |

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe) - Nouvel objet [ITextFrame](../../com.aspose.slides/itextframe).
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Spécifie si la forme est une zone de texte.

--------------------

Si la forme n'est pas spécifiée comme zone de texte, cela ne signifie pas qu'elle ne peut pas contenir de texte. Une zone de texte n'est qu'une forme spécialisée avec des propriétés spécifiques.

**Renvoie :**
boolean