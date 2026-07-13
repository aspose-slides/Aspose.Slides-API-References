---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta una guida di disegno regolabile.
type: docs
url: /it/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Rappresenta una guida di disegno regolabile.
## Metodi

| Method | Description |
| --- | --- |
| [getOrientation()](#getOrientation--) | Restituisce o imposta l'orientamento della guida di disegno. |
| [setOrientation(byte value)](#setOrientation-byte-) | Restituisce o imposta l'orientamento della guida di disegno. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione della guida di disegno in punti dall'angolo in alto a sinistra della diapositiva. |
| [setPosition(float value)](#setPosition-float-) | Restituisce o imposta la posizione della guida di disegno in punti dall'angolo in alto a sinistra della diapositiva. |
| [getColor()](#getColor--) | Restituisce o imposta il colore della guida di disegno. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Restituisce o imposta il colore della guida di disegno. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

Restituisce o imposta l'orientamento della guida di disegno. Lettura/scrittura [Orientation](../../com.aspose.slides/orientation).

**Restituisce:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

Restituisce o imposta l'orientamento della guida di disegno. Lettura/scrittura [Orientation](../../com.aspose.slides/orientation).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Restituisce o imposta la posizione della guida di disegno in punti dall'angolo in alto a sinistra della diapositiva. Lettura/scrittura float.

--------------------

L'intervallo tipico di valori è da zero all'altezza della diapositiva per una guida orizzontale e da zero alla larghezza della diapositiva per una guida verticale.

**Restituisce:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Restituisce o imposta la posizione della guida di disegno in punti dall'angolo in alto a sinistra della diapositiva. Lettura/scrittura float.

--------------------

L'intervallo tipico di valori è da zero all'altezza della diapositiva per una guida orizzontale e da zero alla larghezza della diapositiva per una guida verticale.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Restituisce o imposta il colore della guida di disegno. Lettura/scrittura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Restituisce o imposta il colore della guida di disegno. Lettura/scrittura java.lang.Integer.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |