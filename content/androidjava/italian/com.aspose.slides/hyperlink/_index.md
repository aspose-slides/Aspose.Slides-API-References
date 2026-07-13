---
title: Hyperlink
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un collegamento ipertestuale.
type: docs
url: /it/com.aspose.slides/hyperlink/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Rappresenta un Hyperlink.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Crea un'istanza di un Hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Crea un'istanza di un Hyperlink che punta a una diapositiva specifica. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Crea un'istanza di un Hyperlink utilizzando un altro Hyperlink come origine, sovrascrivendo le proprietà secondarie. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Restituisce un Hyperlink speciale "non fare nulla". |
| [getMedia()](#getMedia--) | Restituisce un Hyperlink speciale "riproduci file multimediale". |
| [getNextSlide()](#getNextSlide--) | Restituisce un Hyperlink alla diapositiva successiva. |
| [getPreviousSlide()](#getPreviousSlide--) | Restituisce un Hyperlink alla diapositiva precedente. |
| [getFirstSlide()](#getFirstSlide--) | Restituisce un Hyperlink alla prima diapositiva della presentazione. |
| [getLastSlide()](#getLastSlide--) | Restituisce un Hyperlink all'ultima diapositiva della presentazione. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Restituisce un Hyperlink all'ultima diapositiva visualizzata. |
| [getEndShow()](#getEndShow--) | Restituisce un Hyperlink che termina lo spettacolo. |
| [getActionType()](#getActionType--) | Restituisce il tipo di azione dell'Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Specifica l'URL esterno. |
| [getTargetSlide()](#getTargetSlide--) | Se l'Hyperlink punta a una diapositiva specifica, restituisce quella diapositiva. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Rappresenta un Hyperlink impostato per questa porzione indipendentemente dal contenuto reale della porzione. |
| [getTargetFrame()](#getTargetFrame--) | Restituisce il frame all'interno del frameset HTML genitore per il target dell'Hyperlink genitore quando esiste. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Restituisce il frame all'interno del frameset HTML genitore per il target dell'Hyperlink genitore quando esiste. |
| [getTooltip()](#getTooltip--) | Restituisce la stringa che può essere mostrata in un'interfaccia utente associata all'Hyperlink genitore. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Restituisce la stringa che può essere mostrata in un'interfaccia utente associata all'Hyperlink genitore. |
| [getHistory()](#getHistory--) | Determina se il target dell'Hyperlink genitore debba essere aggiunto a una lista di Hyperlink visualizzati quando viene invocato. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina se il target dell'Hyperlink genitore debba essere aggiunto a una lista di Hyperlink visualizzati quando viene invocato. |
| [getHighlightClick()](#getHighlightClick--) | Determina se l'Hyperlink debba essere evidenziato al clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina se l'Hyperlink debba essere evidenziato al clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina se il suono debba essere interrotto al clic sull'Hyperlink. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina se il suono debba essere interrotto al clic sull'Hyperlink. |
| [getSound()](#getSound--) | Rappresenta il suono in riproduzione dell'Hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Rappresenta il suono in riproduzione dell'Hyperlink. |
| [getColorSource()](#getColorSource--) | Rappresenta la sorgente del colore dell'Hyperlink - stili o formato della porzione. |
| [setColorSource(int value)](#setColorSource-int-) | Rappresenta la sorgente del colore dell'Hyperlink - stili o formato della porzione. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se le due istanze di Hyperlink sono uguali. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina se le due istanze di Hyperlink sono uguali. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Verifica l'uguaglianza di due Hyperlink. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Verifica la disuguaglianza di due Hyperlink. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Crea un'istanza di un Hyperlink.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL dell'Hyperlink. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Crea un'istanza di un Hyperlink che punta a una diapositiva specifica. Nota: l'Hyperlink creato deve essere assegnato a qualche oggetto della stessa presentazione, altrimenti il collegamento verrà salvato come NoAction.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva target. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Crea un'istanza di un Hyperlink utilizzando un altro Hyperlink come origine, sovrascrivendo le proprietà secondarie.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink di origine |
| targetFrame | java.lang.String | Frame di destinazione |
| tooltip | java.lang.String | Testo tooltip |
| history | boolean | Determina se il target dell'Hyperlink genitore debba essere aggiunto a una lista di Hyperlink visualizzati quando viene invocato. |
| stopSoundsOnClick | boolean | Determina se il suono debba essere interrotto al clic sull'Hyperlink. |
| highlightClick | boolean | Determina se l'Hyperlink debba essere evidenziato al clic. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Restituisce un Hyperlink speciale "non fare nulla". Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Restituisce un Hyperlink speciale "riproduci file multimediale". Usato in AudioFrame e VideoFrame. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Restituisce un Hyperlink alla diapositiva successiva. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Restituisce un Hyperlink alla diapositiva precedente. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Restituisce un Hyperlink alla prima diapositiva della presentazione. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Restituisce un Hyperlink all'ultima diapositiva della presentazione. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Restituisce un Hyperlink all'ultima diapositiva visualizzata. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Restituisce un Hyperlink che termina lo spettacolo. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Restituisce il tipo di azione dell'Hyperlink. Solo lettura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Restituisce:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Specifica l'URL esterno. Solo lettura String.

**Restituisce:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Se l'Hyperlink punta a una diapositiva specifica, restituisce quella diapositiva. Solo lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Rappresenta un Hyperlink impostato per questa porzione indipendentemente dal contenuto reale della porzione.

--------------------

PowerPoint si comporta in modo specifico per i collegamenti e il loro testo corrispondente in una porzione. Consente di creare testo per l'Hyperlink sotto forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando visualizzi il collegamento nella finestra di modifica, verrà modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale dell'Hyperlink.

**Restituisce:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Restituisce il frame all'interno del frameset HTML genitore per il target dell'Hyperlink genitore quando esiste. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Restituisce il frame all'interno del frameset HTML genitore per il target dell'Hyperlink genitore quando esiste. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Restituisce la stringa che può essere mostrata in un'interfaccia utente associata all'Hyperlink genitore. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Restituisce la stringa che può essere mostrata in un'interfaccia utente associata all'Hyperlink genitore. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Determina se il target dell'Hyperlink genitore debba essere aggiunto a una lista di Hyperlink visualizzati quando viene invocato. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Determina se il target dell'Hyperlink genitore debba essere aggiunto a una lista di Hyperlink visualizzati quando viene invocato. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Determina se l'Hyperlink debba essere evidenziato al clic. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Determina se l'Hyperlink debba essere evidenziato al clic. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Determina se il suono debba essere interrotto al clic sull'Hyperlink. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Determina se il suono debba essere interrotto al clic sull'Hyperlink. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Rappresenta il suono in riproduzione dell'Hyperlink. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

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
public final void setSound(IAudio value)
```

Rappresenta il suono in riproduzione dell'Hyperlink. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

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
public final int getColorSource()
```

Rappresenta la sorgente del colore dell'Hyperlink - stili o formato della porzione. Lettura/Scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Restituisce:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Rappresenta la sorgente del colore dell'Hyperlink - stili o formato della porzione. Lettura/Scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se le due istanze di Hyperlink sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'Hyperlink da confrontare con l'Hyperlink corrente. |

**Restituisce:**
boolean - **true** se l'Hyperlink specificato è uguale all'Hyperlink corrente; altrimenti, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Determina se le due istanze di Hyperlink sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | L'Hyperlink da confrontare con l'Hyperlink corrente. |

**Restituisce:**
boolean - **true** se l'Hyperlink specificato è uguale all'Hyperlink corrente; altrimenti, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Verifica l'uguaglianza di due Hyperlink.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primo Hyperlink da testare. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Secondo Hyperlink da testare. |

**Restituisce:**
boolean - **true** se gli Hyperlink sono uguali.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Verifica la disuguaglianza di due Hyperlink.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primo Hyperlink da testare. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Secondo Hyperlink da testare. |

**Restituisce:**
boolean - **false** se gli Hyperlink sono uguali.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funge da funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int - Codice hash per un URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject