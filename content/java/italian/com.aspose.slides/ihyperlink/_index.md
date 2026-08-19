---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un collegamento ipertestuale.
type: docs
url: /it/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Rappresenta un collegamento ipertestuale.
## Methods

| Metodo | Descrizione |
| --- | --- |
| [getActionType()](#getActionType--) | Restituisce il tipo dell'azione di HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Specifica l'URL esterno. Se questa proprietà diventa non nulla, allora la proprietà TargetSlide diventa nulla. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto effettivo della porzione. |
| [getTargetSlide()](#getTargetSlide--) | Se HyperlinkEx punta a una slide specifica, restituisce questa slide. |
| [getTargetFrame()](#getTargetFrame--) | Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore, se esiste. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore, se esiste. |
| [getTooltip()](#getTooltip--) | Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. |
| [getHistory()](#getHistory--) | Determina se il target del collegamento ipertestuale genitore deve essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina se il target del collegamento ipertestuale genitore deve essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. |
| [getHighlightClick()](#getHighlightClick--) | Determina se il collegamento ipertestuale deve essere evidenziato al click. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina se il collegamento ipertestuale deve essere evidenziato al click. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina se il suono deve essere interrotto al click del collegamento ipertestuale. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina se il suono deve essere interrotto al click del collegamento ipertestuale. |
| [getSound()](#getSound--) | Rappresenta il suono in riproduzione del collegamento ipertestuale. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Rappresenta il suono in riproduzione del collegamento ipertestuale. |
| [getColorSource()](#getColorSource--) | Rappresenta l'origine del colore del collegamento ipertestuale: stili o formato della porzione. |
| [setColorSource(int value)](#setColorSource-int-) | Rappresenta l'origine del colore del collegamento ipertestuale: stili o formato della porzione. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina se le due istanze di Hyperlink sono uguali. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Restituisce il tipo dell'azione di HyperLinkEx. Sola lettura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Restituisce:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Specifica l'URL esterno. Se questa proprietà diventa non nulla, allora la proprietà TargetSlide diventa nulla. Sola lettura String.

**Restituisce:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto effettivo della porzione.

--------------------

PowerPoint si comporta in modo specifico per i collegamenti e il loro testo corrispondente in una porzione. Consente di creare testo per il collegamento ipertestuale sotto forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando visualizzi il collegamento nella finestra di modifica, verrà modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale del collegamento ipertestuale.

**Restituisce:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Se HyperlinkEx punta a una slide specifica, restituisce questa slide. Se la proprietà diventa non nulla, allora la proprietà ExternalUrl diventa nulla. Sola lettura [ISlide](../../com.aspose.slides/islide).

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

Determina se il target del collegamento ipertestuale genitore deve essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Determina se il target del collegamento ipertestuale genitore deve essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Determina se il collegamento ipertestuale deve essere evidenziato al click. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Determina se il collegamento ipertestuale deve essere evidenziato al click. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Determina se il suono deve essere interrotto al click del collegamento ipertestuale. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Determina se il suono deve essere interrotto al click del collegamento ipertestuale. Lettura/scrittura boolean.

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
>      // Ottieni il collegamento ipertestuale della prima forma
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
>      // Ottieni il collegamento ipertestuale della prima forma
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

Rappresenta l'origine del colore del collegamento ipertestuale: stili o formato della porzione. Lettura/scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Restituisce:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Rappresenta l'origine del colore del collegamento ipertestuale: stili o formato della porzione. Lettura/scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

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
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Il Hyperlink da confrontare con il Hyperlink corrente. |

**Restituisce:**
boolean - **true** se il Hyperlink specificato è uguale al Hyperlink corrente; altrimenti, **false**.