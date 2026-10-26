---
title: IXpsOptions
second_title: Riferimento API Java per Aspose.Slides per Android
description: Fornisce opzioni che controllano come una presentazione viene salvata nel formato XPS.
type: docs
url: /it/com.aspose.slides/ixpsoptions/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata nel formato XPS.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True per convertire tutti i metafili usati nella presentazione in immagini PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True per convertire tutti i metafili usati nella presentazione in immagini PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True per disegnare un bordo nero attorno a ciascuna diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True per disegnare un bordo nero attorno a ciascuna diapositiva. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True per convertire tutti i metafili usati nella presentazione in immagini PNG. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **true**.

**Restituisce:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True per convertire tutti i metafili usati nella presentazione in immagini PNG. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **true**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True per disegnare un bordo nero attorno a ciascuna diapositiva. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True per disegnare un bordo nero attorno a ciascuna diapositiva. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è **false**.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |