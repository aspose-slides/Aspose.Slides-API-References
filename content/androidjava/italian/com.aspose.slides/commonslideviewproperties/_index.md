---
title: CommonSlideViewProperties
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le proprietà comuni della visualizzazione della diapositiva.
type: docs
url: /it/com.aspose.slides/commonslideviewproperties/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Rappresenta le proprietà comuni della visualizzazione della diapositiva.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Instanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Impostazione delle proprietà di visualizzazione della presentazione
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Valore di zoom in percentuale per la visualizzazione della diapositiva
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Valore di zoom in percentuale per la visualizzazione delle note
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getScale()](#getScale--) | Specifica il rapporto di scala della visualizzazione in percentuale. |
| [setScale(int value)](#setScale-int-) | Specifica il rapporto di scala della visualizzazione in percentuale. |
| [getVariableScale()](#getVariableScale--) | Specifica che il contenuto della visualizzazione deve essere scalato automaticamente per adattarsi al meglio alle dimensioni correnti della finestra. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specifica che il contenuto della visualizzazione deve essere scalato automaticamente per adattarsi al meglio alle dimensioni correnti della finestra. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce la raccolta delle guide di disegno. |
### getScale() {#getScale--}
```
public final int getScale()
```


Specifica il rapporto di scala della visualizzazione in percentuale. Lettura/Scrittura int.

**Restituisce:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Specifica il rapporto di scala della visualizzazione in percentuale. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Specifica che il contenuto della visualizzazione deve essere scalato automaticamente per adattarsi al meglio alle dimensioni correnti della finestra. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Specifica che il contenuto della visualizzazione deve essere scalato automaticamente per adattarsi al meglio alle dimensioni correnti della finestra. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Restituisce la raccolta delle guide di disegno. Sola lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Aggiunta della nuova guida di disegno verticale a destra del centro della diapositiva
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Aggiunta della nuova guida di disegno orizzontale sotto il centro della diapositiva
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)