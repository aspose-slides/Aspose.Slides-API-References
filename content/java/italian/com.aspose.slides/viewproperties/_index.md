---
title: ViewProperties
second_title: Riferimento API di Aspose.Slides per Java
description: Proprietà della vista a livello di presentazione.
type: docs
url: /it/com.aspose.slides/viewproperties/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Proprietà della vista a livello di presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLastView()](#getLastView--) | Specifica la modalità di visualizzazione che è stata usata quando il documento della presentazione è stato salvato per l'ultima volta. |
| [setLastView(int value)](#setLastView-int-) | Specifica la modalità di visualizzazione che è stata usata quando il documento della presentazione è stato salvato per l'ultima volta. |
| [getShowComments()](#getShowComments--) | Specifica se i commenti della diapositiva devono essere mostrati. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifica se i commenti della diapositiva devono essere mostrati. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Rappresenta le proprietà della vista normale. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifica le proprietà di visualizzazione comuni associate alla modalità di visualizzazione della diapositiva. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifica le proprietà di visualizzazione comuni associate alla modalità di visualizzazione delle note. |
| [getGridSpacing()](#getGridSpacing--) | Restituisce o imposta la spaziatura della griglia che deve essere usata per la griglia sottostante al documento della presentazione, in punti. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Restituisce o imposta la spaziatura della griglia che deve essere usata per la griglia sottostante al documento della presentazione, in punti. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Specifică la modalità di visualizzazione che è stata usata quando il documento della presentazione è stato salvato per l'ultima volta. Lettura/scrittura [ViewType](../../com.aspose.slides/viewtype).

**Restituisce:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Specifică la modalità di visualizzazione che è stata usata quando il documento della presentazione è stato salvato per l'ultima volta. Lettura/scrittura [ViewType](../../com.aspose.slides/viewtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Specifică se i commenti della diapositiva devono essere mostrati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Specifică se i commenti della diapositiva devono essere mostrati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Rappresenta le proprietà della vista normale. La vista normale è composta da tre regioni di contenuto: la diapositiva stessa, una regione di contenuto laterale e una regione di contenuto inferiore. Sola lettura [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Restituisce:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Specifică le proprietà di visualizzazione comuni associate alla modalità di visualizzazione della diapositiva. Sola lettura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Restituisce:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Specifică le proprietà di visualizzazione comuni associate alla modalità di visualizzazione delle note. Sola lettura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Restituisce:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Restituisce o imposta la spaziatura della griglia che deve essere usata per la griglia sottostante al documento della presentazione, in punti. Lettura/scrittura float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Il valore della spaziatura della griglia deve essere un numero positivo. L'intervallo tipico è da 1 mm (2.8349607 punti) a 2 pollici (144 punti).

**Restituisce:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Restituisce o imposta la spaziatura della griglia che deve essere usata per la griglia sottostante al documento della presentazione, in punti. Lettura/scrittura float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Il valore della spaziatura della griglia deve essere un numero positivo. L'intervallo tipico è da 1 mm (2.8349607 punti) a 2 pollici (144 punti).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Sola lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject