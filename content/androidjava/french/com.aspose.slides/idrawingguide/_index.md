---
title: IDrawingGuide
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un guide de dessin réglable.
type: docs
url: /fr/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Représente un guide de dessin réglable.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOrientation()](#getOrientation--) | Renvoie ou définit l'orientation du guide de dessin. |
| [setOrientation(byte value)](#setOrientation-byte-) | Renvoie ou définit l'orientation du guide de dessin. |
| [getPosition()](#getPosition--) | Renvoie ou définit la position du guide de dessin en points depuis le coin supérieur gauche de la diapositive. |
| [setPosition(float value)](#setPosition-float-) | Renvoie ou définit la position du guide de dessin en points depuis le coin supérieur gauche de la diapositive. |
| [getColor()](#getColor--) | Renvoie ou définit la couleur du guide de dessin. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Renvoie ou définit la couleur du guide de dessin. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Renvoie ou définit l'orientation du guide de dessin. Lecture/écriture [Orientation](../../com.aspose.slides/orientation).

**Renvoie:**  
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Renvoie ou définit l'orientation du guide de dessin. Lecture/écriture [Orientation](../../com.aspose.slides/orientation).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Renvoie ou définit la position du guide de dessin en points depuis le coin supérieur gauche de la diapositive. Lecture/écriture float.

--------------------

La plage de valeurs typique va de zéro à la hauteur de la diapositive pour un guide horizontal et de zéro à la largeur de la diapositive pour un guide vertical.

**Renvoie:**  
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Renvoie ou définit la position du guide de dessin en points depuis le coin supérieur gauche de la diapositive. Lecture/écriture float.

--------------------

La plage de valeurs typique va de zéro à la hauteur de la diapositive pour un guide horizontal et de zéro à la largeur de la diapositive pour un guide vertical.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Renvoie ou définit la couleur du guide de dessin. Lecture/écriture java.lang.Integer.

**Renvoie:**  
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Renvoie ou définit la couleur du guide de dessin. Lecture/écriture java.lang.Integer.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |