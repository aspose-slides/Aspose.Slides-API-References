---
title: ICommonSlideViewProperties
second_title: Aspose.Slides per Java API Reference
description: Rappresenta le proprietà comuni della visualizzazione della diapositiva.
type: docs
url: /it/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Rappresenta le proprietà comuni della visualizzazione della diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getScale()](#getScale--) | Specifica il rapporto di scala della visualizzazione in percentuale. |
| [setScale(int value)](#setScale-int-) | Specifica il rapporto di scala della visualizzazione in percentuale. |
| [getVariableScale()](#getVariableScale--) | Specifica che il contenuto della visualizzazione deve ridimensionarsi automaticamente per adattarsi al meglio alle dimensioni attuali della finestra. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specifica che il contenuto della visualizzazione deve ridimensionarsi automaticamente per adattarsi al meglio alle dimensioni attuali della finestra. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce la raccolta delle guide di disegno. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Specifică il rapporto di scala della visualizzazione in percentuale. Lettura/scrittura int.

**Restituisce:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Specifică il rapporto di scala della visualizzazione in percentuale. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Specifică che il contenuto della visualizzazione deve ridimensionarsi automaticamente per adattarsi al meglio alle dimensioni attuali della finestra. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Specifică che il contenuto della visualizzazione deve ridimensionarsi automaticamente per adattarsi al meglio alle dimensioni attuali della finestra. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Restituisce la raccolta delle guide di disegno. Sola lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Aggiunta della nuova guida di disegno verticale a destra del centro della diapositiva
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
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