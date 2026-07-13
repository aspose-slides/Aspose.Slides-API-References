---
title: XpsOptions
second_title: Riferimento API Java per Aspose.Slides per Android
description: Fornisce opzioni che controllano come una presentazione viene salvata nel formato XPS.
type: docs
url: /it/com.aspose.slides/xpsoptions/
---
**Eredità:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**  
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)  
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata nel formato XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Salva la presentazione in un documento XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Istanzia la classe TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Salva i MetaFile come PNG
>      options.setSaveMetafilesAsPng(true);
>      // Salva la presentazione in un documento XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Costruttore predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificare se il documento generato deve includere le diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificare se il documento generato deve includere le diapositive nascoste o meno. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True per convertire tutti i metafile utilizzati in una presentazione in immagini PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True per convertire tutti i metafile utilizzati in una presentazione in immagini PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True per disegnare una cornice nera attorno a ciascuna diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True per disegnare una cornice nera attorno a ciascuna diapositiva. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Costruttore predefinito.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specificare se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è **false**.

**Restituisce:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specificare se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True per convertire tutti i metafile utilizzati in una presentazione in immagini PNG. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **true**.

**Restituisce:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True per convertire tutti i metafile utilizzati in una presentazione in immagini PNG. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **true**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True per disegnare una cornice nera attorno a ciascuna diapositiva. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **false**.

**Restituisce:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True per disegnare una cornice nera attorno a ciascuna diapositiva. Booleano di lettura/scrittura.

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |