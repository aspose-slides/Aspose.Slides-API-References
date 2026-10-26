---
title: SlideSize
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le dimensioni e l'orientamento di una diapositiva.
type: docs
url: /it/com.aspose.slides/slidesize/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Rappresenta le dimensioni e l'orientamento di una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Ottiene le dimensioni della diapositiva in punti. |
| [getType()](#getType--) | Ottiene il tipo di dimensione della diapositiva. |
| [getOrientation()](#getOrientation--) | Ottiene o imposta l'orientamento della diapositiva. |
| [setOrientation(int value)](#setOrientation-int-) | Ottiene o imposta l'orientamento della diapositiva. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Imposta la dimensione della diapositiva per tipo e scala il contenuto esistente. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Imposta esplicitamente le dimensioni della diapositiva e scala il contenuto esistente. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


Restituisce le dimensioni della diapositiva in punti.

--------------------

Assegnare un nuovo valore reimposta la proprietà \#getType.getType a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e imposta \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Restituisce:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```


Restituisce il tipo di dimensione della diapositiva.

--------------------

Assegnare qualsiasi valore diverso da [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) regola \#getSize.getSize in base alle dimensioni predefinite, mantenendo l'attuale \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Restituisce:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Ottiene o imposta l'orientamento della diapositiva.

--------------------

Modificando questo valore si scambiano la larghezza e l'altezza della diapositiva.

**Restituisce:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Ottiene o imposta l'orientamento della diapositiva.

--------------------

Modificando questo valore si scambiano la larghezza e l'altezza della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Imposta la dimensione della diapositiva per tipo e scala il contenuto esistente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | La dimensione predefinita della diapositiva da applicare. |
| scaleType | int | La modalità di ridimensionamento del contenuto da utilizzare. |

--------------------

Assegnare qualsiasi valore diverso da [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) regola \#getSize.getSize in base al tipo selezionato, preservando \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Imposta esplicitamente le dimensioni della diapositiva e scala il contenuto esistente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | float | La nuova larghezza della diapositiva, in punti. |
| height | float | La nuova altezza della diapositiva, in punti. |
| scaleType | int | La modalità di ridimensionamento del contenuto da utilizzare. |

--------------------

Questo reimposta la proprietà \#getType.getType a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e imposta \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |