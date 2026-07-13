---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta le dimensioni e l'orientamento di una diapositiva.
type: docs
url: /it/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Rappresenta le dimensioni e l'orientamento di una diapositiva.
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Restituisce le dimensioni della diapositiva in punti. |
| [getType()](#getType--) | Restituisce il tipo di dimensione della diapositiva. |
| [getOrientation()](#getOrientation--) | Ottiene o imposta l'orientamento della diapositiva. |
| [setOrientation(int value)](#setOrientation-int-) | Ottiene o imposta l'orientamento della diapositiva. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Imposta la dimensione della diapositiva per tipo e ridimensiona il contenuto esistente. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Imposta esplicitamente le dimensioni della diapositiva e ridimensiona il contenuto esistente. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Restituisce le dimensioni della diapositiva in punti.

--------------------

L'assegnazione di un nuovo valore reimposta la \#getType.getType property a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e imposta la \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Restituisce:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

Restituisce il tipo di dimensione della diapositiva.

--------------------

L'assegnazione di qualsiasi valore diverso da [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) regola la \#getSize.getSize secondo le dimensioni predefinite, mantenendo l'attuale \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Restituisce:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Ottiene o imposta l'orientamento della diapositiva.

--------------------

Modificando questo valore si scambiano la larghezza e l'altezza della diapositiva.

**Restituisce:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Ottiene o imposta l'orientamento della diapositiva.

--------------------

Modificando questo valore si scambiano la larghezza e l'altezza della diapositiva.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

Imposta la dimensione della diapositiva per tipo e ridimensiona il contenuto esistente.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | La dimensione predefinita della diapositiva da applicare. |
| scaleType | int | La modalità di ridimensionamento del contenuto da utilizzare. |

--------------------

L'assegnazione di qualsiasi valore diverso da [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) regola la \#getSize.getSize in base al tipo selezionato, preservando la \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Imposta esplicitamente le dimensioni della diapositiva e ridimensiona il contenuto esistente.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | La nuova larghezza della diapositiva, in punti. |
| height | float | La nuova altezza della diapositiva, in punti. |
| scaleType | int | La modalità di ridimensionamento del contenuto da utilizzare. |

--------------------

Questo reimposta la \#getType.getType property a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e imposta la \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |