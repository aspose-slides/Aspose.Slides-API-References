---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta le proprietà comuni della visualizzazione delle diapositive.
type: docs
url: /it/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Rappresenta le proprietà comuni della visualizzazione delle diapositive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getScale()](#getScale--) | Specifica il rapporto di scala della vista in percentuale. |
| [setScale(int value)](#setScale-int-) | Specifica il rapporto di scala della vista in percentuale. |
| [getVariableScale()](#getVariableScale--) | Specifica che il contenuto della vista dovrebbe ridimensionarsi automaticamente per adattarsi al meglio alla dimensione corrente della finestra. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specifica che il contenuto della vista dovrebbe ridimensionarsi automaticamente per adattarsi al meglio alla dimensione corrente della finestra. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce la collezione delle guide di disegno. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Specifica il rapporto di scala della vista in percentuale. Lettura/Scrittura int.

**Restituisce:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Specifica il rapporto di scala della vista in percentuale. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Specifica che il contenuto della vista dovrebbe ridimensionarsi automaticamente per adattarsi al meglio alla dimensione corrente della finestra. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Specifica che il contenuto della vista dovrebbe ridimensionarsi automaticamente per adattarsi al meglio alla dimensione corrente della finestra. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Restituisce la collezione delle guide di disegno. Solo lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)