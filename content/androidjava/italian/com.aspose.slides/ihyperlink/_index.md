---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta un collegamento ipertestuale.
type: docs
url: /it/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Rappresenta un collegamento ipertestuale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getActionType()](#getActionType--) | Restituisce il tipo dell'azione di HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Specifica l'URL esterno. Se questa proprietà diventa non nulla, allora la proprietà TargetSlide diventa null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto reale della porzione. |
| [getTargetSlide()](#getTargetSlide--) | Se HyperlinkEx punta a una diapositiva specifica, restituisce questa diapositiva. |
| [getTargetFrame()](#getTargetFrame--) | Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore, se esiste. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore, se esiste. |
| [getTooltip()](#getTooltip--) | Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. |
| [getHistory()](#getHistory--) | Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. |
| [getHighlightClick()](#getHighlightClick--) | Determina se il collegamento ipertestuale debba essere evidenziato al clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina se il collegamento ipertestuale debba essere evidenziato al clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina se il suono debba essere interrotto al clic del collegamento ipertestuale. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina se il suono debba essere interrotto al clic del collegamento ipertestuale. |
| [getSound()](#getSound--) | Rappresenta il suono in riproduzione del collegamento ipertestuale. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Rappresenta il suono in riproduzione del collegamento ipertestuale. |
| [getColorSource()](#getColorSource--) | Rappresenta la sorgente del colore del collegamento ipertestuale - sia stili che formato della porzione. |
| [setColorSource(int value)](#setColorSource-int-) | Rappresenta la sorgente del colore del collegamento ipertestuale - sia stili che formato della porzione. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina se le due istanze di Hyperlink sono uguali. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Restituisce il tipo dell'azione di HyperLinkEx. Solo lettura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Restituisce:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Specifica l'URL esterno. Se questa proprietà diventa non nulla, allora la proprietà TargetSlide diventa null. Solo lettura String.

**Restituisce:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto reale della porzione.

--------------------

PowerPoint si comporta in modo specifico per i collegamenti e il relativo testo in una porzione. Consente di creare testo per il collegamento ipertestuale sotto forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando visualizzi il collegamento nella finestra di modifica, verrà modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale del collegamento ipertestuale.

**Restituisce:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Se HyperlinkEx punta a una diapositiva specifica, restituisce questa diapositiva. Se la proprietà diventa non nulla, allora la proprietà ExternalUrl diventa null. Solo lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore, se esiste. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore, se esiste. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Determina se il collegamento ipertestuale debba essere evidenziato al clic. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Determina se il collegamento ipertestuale debba essere evidenziato al clic. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Determina se il suono debba essere interrotto al clic del collegamento ipertestuale. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Determina se il suono debba essere interrotto al clic del collegamento ipertestuale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Rappresenta il suono in riproduzione del collegamento ipertestuale. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Ottieni il primo collegamento ipertestuale della forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Estrai il suono del collegamento ipertestuale in un array di byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  ```


**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Rappresenta il suono in riproduzione del collegamento ipertestuale. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Ottieni il primo collegamento ipertestuale della forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Estrai il suono del collegamento ipertestuale in un array di byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Rappresenta la sorgente del colore del collegamento ipertestuale - sia stili che formato della porzione. Lettura/scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Restituisce:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Rappresenta la sorgente del colore del collegamento ipertestuale - sia stili che formato della porzione. Lettura/scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Determina se le due istanze di Hyperlink sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Il Hyperlink da confrontare con l'Hyperlink corrente. |

**Restituisce:**
boolean - **true** se il Hyperlink specificato è uguale al Hyperlink corrente; altrimenti, **false**.