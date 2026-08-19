---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Rappresenta la dimensione e l'orientamento di una diapositiva.
type: docs
url: /it/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Rappresenta la dimensione e l'orientamento di una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Gets the slide dimensions in points. |
| [getType()](#getType--) | Gets the slide size type. |
| [getOrientation()](#getOrientation--) | Gets or sets the slide orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the slide orientation. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Sets the slide size by type and scales existing content. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Sets the slide dimensions explicitly and scales existing content. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Ottiene le dimensioni della diapositiva in punti.

--------------------

Assegnare un nuovo valore ripristina la proprietà #getType.getType a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e imposta #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**Restituisce:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Ottiene il tipo di dimensione della diapositiva.

--------------------

Assegnare qualsiasi valore diverso da [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) regola #getSize.getSize in base alle dimensioni predefinite, mantenendo l'attuale #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**Restituisce:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Ottiene o imposta l'orientamento della diapositiva.

--------------------

Modificando questo valore si scambiano larghezza e altezza della diapositiva.

**Restituisce:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Ottiene o imposta l'orientamento della diapositiva.

--------------------

Modificando questo valore si scambiano larghezza e altezza della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Imposta la dimensione della diapositiva per tipo e scala il contenuto esistente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | La dimensione della diapositiva predefinita da applicare. |
| scaleType | int | La modalità di scalatura del contenuto da utilizzare. |

--------------------

Assegnare qualsiasi valore diverso da [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) regola #getSize.getSize in base al tipo selezionato, preservando #getOrientation.getOrientation/#setOrientation(int).setOrientation(int). |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Imposta esplicitamente le dimensioni della diapositiva e scala il contenuto esistente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | float | La nuova larghezza della diapositiva, in punti. |
| height | float | La nuova altezza della diapositiva, in punti. |
| scaleType | int | La modalità di scalatura del contenuto da utilizzare. |

--------------------

Questo ripristina la proprietà #getType.getType a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e imposta la \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |