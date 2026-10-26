---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /it/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Proprietà della visualizzazione a livello di presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLastView()](#getLastView--) | Specifica la modalità di visualizzazione usata quando il documento della presentazione è stato salvato l'ultima volta. |
| [setLastView(int value)](#setLastView-int-) | Specifica la modalità di visualizzazione usata quando il documento della presentazione è stato salvato l'ultima volta. |
| [getShowComments()](#getShowComments--) | Specifica se i commenti della diapositiva devono essere mostrati. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifica se i commenti della diapositiva devono essere mostrati. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifica le proprietà comuni della visualizzazione associate alla modalità di visualizzazione della diapositiva. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifica le proprietà comuni della visualizzazione associate alla modalità di visualizzazione delle note. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Rappresenta le proprietà della visualizzazione normale. |
| [getGridSpacing()](#getGridSpacing--) | Restituisce o imposta la spaziatura della griglia da usare per la griglia sottostante il documento della presentazione, in punti. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Restituisce o imposta la spaziatura della griglia da usare per la griglia sottostante il documento della presentazione, in punti. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Specifica la modalità di visualizzazione usata quando il documento della presentazione è stato salvato l'ultima volta. Lettura/scrittura [ViewType](../../com.aspose.slides/viewtype).

**Restituisce:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Specifica la modalità di visualizzazione usata quando il documento della presentazione è stato salvato l'ultima volta. Lettura/scrittura [ViewType](../../com.aspose.slides/viewtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Specifica se i commenti della diapositiva devono essere mostrati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Specifica se i commenti della diapositiva devono essere mostrati. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Specifica le proprietà comuni della visualizzazione associate alla modalità di visualizzazione della diapositiva. Solo lettura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Restituisce:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Specifica le proprietà comuni della visualizzazione associate alla modalità di visualizzazione delle note. Solo lettura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Restituisce:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Rappresenta le proprietà della visualizzazione normale. La visualizzazione normale è composta da tre regioni di contenuto: la diapositiva stessa, una regione laterale di contenuto e una regione inferiore di contenuto. Solo lettura [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Restituisce:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Restituisce o imposta la spaziatura della griglia da usare per la griglia sottostante il documento della presentazione, in punti. Lettura/scrittura float.

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

Il valore della spaziatura della griglia deve essere un numero positivo. L'intervallo tipico è da 1 mm (2,8349607 punti) a 2 pollici (144 punti).

**Restituisce:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Restituisce o imposta la spaziatura della griglia da usare per la griglia sottostante il documento della presentazione, in punti. Lettura/scrittura float.

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

Il valore della spaziatura della griglia deve essere un numero positivo. L'intervallo tipico è da 1 mm (2,8349607 punti) a 2 pollici (144 punti).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |