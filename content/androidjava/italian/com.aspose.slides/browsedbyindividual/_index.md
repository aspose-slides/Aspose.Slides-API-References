---
title: BrowsedByIndividual
second_title: Riferimento API Java per Aspose.Slides per Android
description: Finestra visualizzata da individuo
type: docs
url: /it/com.aspose.slides/browsedbyindividual/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Navigato da individuo (finestra)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Inizializza una nuova istanza della classe BrowsedByIndividual. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Mostra la barra di scorrimento nella finestra |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Mostra la barra di scorrimento nella finestra |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Inizializza una nuova istanza della classe BrowsedByIndividual.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Mostra la barra di scorrimento nella finestra

**Restituisce:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Mostra la barra di scorrimento nella finestra

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |