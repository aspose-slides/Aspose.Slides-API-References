---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Rappresenta una guida di disegno regolabile.
type: docs
url: /it/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Rappresenta una guida di disegno regolabile.
## Methods

| Metodo | Descrizione |
| --- | --- |
| [getOrientation()](#getOrientation--) | Restituisce o imposta l'orientamento della guida di disegno. |
| [setOrientation(byte value)](#setOrientation-byte-) | Restituisce o imposta l'orientamento della guida di disegno. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione della guida di disegno in punti dal punto in alto a sinistra della diapositiva. |
| [setPosition(float value)](#setPosition-float-) | Restituisce o imposta la posizione della guida di disegno in punti dal punto in alto a sinistra della diapositiva. |
| [getColor()](#getColor--) | Restituisce o imposta il colore della guida di disegno. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Restituisce o imposta il colore della guida di disegno. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Restituisce o imposta l'orientamento della guida di disegno. Lettura/Scrittura [Orientation](../../com.aspose.slides/orientation).

**Restituisce:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Restituisce o imposta l'orientamento della guida di disegno. Lettura/Scrittura [Orientation](../../com.aspose.slides/orientation).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Restituisce o imposta la posizione della guida di disegno in punti dal punto in alto a sinistra della diapositiva. Lettura/Scrittura float.

--------------------

L'intervallo di valori tipico va da zero all'altezza della diapositiva per una guida orizzontale e da zero alla larghezza della diapositiva per una guida verticale.

**Restituisce:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Restituisce o imposta la posizione della guida di disegno in punti dal punto in alto a sinistra della diapositiva. Lettura/Scrittura float.

--------------------

L'intervallo di valori tipico va da zero all'altezza della diapositiva per una guida orizzontale e da zero alla larghezza della diapositiva per una guida verticale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Restituisce o imposta il colore della guida di disegno. Lettura/Scrittura java.awt.Color.

**Restituisce:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Restituisce o imposta il colore della guida di disegno. Lettura/Scrittura java.awt.Color.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.Color |  |