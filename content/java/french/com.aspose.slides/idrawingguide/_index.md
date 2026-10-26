---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /fr/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Représente un guide de dessin ajustable.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOrientation()](#getOrientation--) | Renvoie ou définit l'orientation du guide de dessin. |
| [setOrientation(byte value)](#setOrientation-byte-) | Renvoie ou définit l'orientation du guide de dessin. |
| [getPosition()](#getPosition--) | Renvoie ou définit la position du guide de dessin en points depuis le coin supérieur gauche de la diapositive. |
| [setPosition(float value)](#setPosition-float-) | Renvoie ou définit la position du guide de dessin en points depuis le coin supérieur gauche de la diapositive. |
| [getColor()](#getColor--) | Renvoie ou définit la couleur du guide de dessin. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Renvoie ou définit la couleur du guide de dessin. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Renvoie ou définit l'orientation du guide de dessin. Lecture/écriture [Orientation](../../com.aspose.slides/orientation).

**Renvoie :**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Renvoie ou définit l'orientation du guide de dessin. Lecture/écriture [Orientation](../../com.aspose.slides/orientation).

**Paramètres :**
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

**Renvoie :**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Renvoie ou définit la position du guide de dessin en points depuis le coin supérieur gauche de la diapositive. Lecture/écriture float.

--------------------

La plage de valeurs typique va de zéro à la hauteur de la diapositive pour un guide horizontal et de zéro à la largeur de la diapositive pour un guide vertical.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Renvoie ou définit la couleur du guide de dessin. Lecture/écriture java.awt.Color.

**Renvoie :**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Renvoie ou définit la couleur du guide de dessin. Lecture/écriture java.awt.Color.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |