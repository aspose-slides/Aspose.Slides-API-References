---
title: Hyperlink
second_title: Riferimento API di Aspose.Slides per Java
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

Rappresenta un collegamento ipertestuale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Crea un'istanza di un collegamento ipertestuale. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Crea un'istanza di un collegamento ipertestuale che punta a una diapositiva specifica. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Crea un'istanza di un collegamento ipertestuale usando un altro collegamento come sorgente, sovrascrivendo le proprietà secondarie. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Restituisce un collegamento ipertestuale speciale "non fare nulla". |
| [getMedia()](#getMedia--) | Restituisce un collegamento ipertestuale speciale "riproduci file multimediale". |
| [getNextSlide()](#getNextSlide--) | Restituisce un collegamento ipertestuale alla diapositiva successiva. |
| [getPreviousSlide()](#getPreviousSlide--) | Restituisce un collegamento ipertestuale alla diapositiva precedente. |
| [getFirstSlide()](#getFirstSlide--) | Restituisce un collegamento ipertestuale alla prima diapositiva della presentazione. |
| [getLastSlide()](#getLastSlide--) | Restituisce un collegamento ipertestuale all'ultima diapositiva della presentazione. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Restituisce un collegamento ipertestuale all'ultima diapositiva visualizzata. |
| [getEndShow()](#getEndShow--) | Restituisce un collegamento ipertestuale che termina la presentazione. |
| [getActionType()](#getActionType--) | Restituisce il tipo di azione del collegamento ipertestuale. |
| [getExternalUrl()](#getExternalUrl--) | Specifica l'URL esterno. |
| [getTargetSlide()](#getTargetSlide--) | Se il collegamento ipertestuale punta a una diapositiva specifica, restituisce quella diapositiva. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto reale della porzione. |
| [getTargetFrame()](#getTargetFrame--) | Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore quando esiste. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore quando esiste. |
| [getTooltip()](#getTooltip--) | Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. |
| [getHistory()](#getHistory--) | Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti visualizzati quando viene invocato. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti visualizzati quando viene invocato. |
| [getHighlightClick()](#getHighlightClick--) | Determina se il collegamento ipertestuale debba essere evidenziato al clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina se il collegamento ipertestuale debba essere evidenziato al clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina se il suono debba essere interrotto al clic sul collegamento ipertestuale. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina se il suono debba essere interrotto al clic sul collegamento ipertestuale. |
| [getSound()](#getSound--) | Rappresenta il suono in riproduzione del collegamento ipertestuale. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Rappresenta il suono in riproduzione del collegamento ipertestuale. |
| [getColorSource()](#getColorSource--) | Rappresenta la sorgente del colore del collegamento ipertestuale – stili o formato della porzione. |
| [setColorSource(int value)](#setColorSource-int-) | Rappresenta la sorgente del colore del collegamento ipertestuale – stili o formato della porzione. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se le due istanze di Hyperlink sono uguali. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina se le due istanze di Hyperlink sono uguali. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Verifica l'uguaglianza di due collegamenti ipertestuali. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Verifica la disuguaglianza di due collegamenti ipertestuali. |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo specifico, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Crea un'istanza di un collegamento ipertestuale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL del collegamento ipertestuale. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Crea un'istanza di un collegamento ipertestuale che punta a una diapositiva specifica. Nota: il collegamento creato deve essere assegnato a un oggetto della stessa presentazione, altrimenti il collegamento sarà salvato come NoAction.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva di destinazione. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Crea un'istanza di un collegamento ipertestuale usando un altro collegamento come sorgente, sovrascrivendo le proprietà secondarie.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Collegamento ipertestuale sorgente |
| targetFrame | java.lang.String | Frame di destinazione |
| tooltip | java.lang.String | Testo tooltip |
| history | boolean | Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti visualizzati quando viene invocato. |
| stopSoundsOnClick | boolean | Determina se il suono debba essere interrotto al clic sul collegamento ipertestuale. |
| highlightClick | boolean | Determina se il collegamento ipertestuale debba essere evidenziato al clic. |

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

Restituisce un collegamento ipertestuale speciale "non fare nulla". Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Restituisce un collegamento ipertestuale speciale "riproduci file multimediale". Usato in AudioFrame e VideoFrame. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Restituisce un collegamento ipertestuale alla diapositiva successiva. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Restituisce un collegamento ipertestuale alla diapositiva precedente. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Restituisce un collegamento ipertestuale alla prima diapositiva della presentazione. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Restituisce un collegamento ipertestuale all'ultima diapositiva della presentazione. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Restituisce un collegamento ipertestuale all'ultima diapositiva visualizzata. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Restituisce un collegamento ipertestuale che termina la presentazione. Solo lettura [Hyperlink](../../com.aspose.slides/hyperlink).

**Restituisce:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Restituisce il tipo di azione del collegamento ipertestuale. Solo lettura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

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

Se il collegamento ipertestuale punta a una diapositiva specifica, restituisce quella diapositiva. Solo lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto reale della porzione.

--------------------

PowerPoint si comporta in modo specifico per i collegamenti e il loro testo corrispondente in una porzione. Consente di creare testo per il collegamento ipertestuale sotto forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando si visualizza il collegamento nella finestra di modifica, verrà modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale del collegamento ipertestuale.

**Restituisce:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore quando esiste. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore quando esiste. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Restituisce la stringa che può essere visualizzata in un'interfaccia utente associata al collegamento ipertestuale genitore. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti visualizzati quando viene invocato. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Determina se il target del collegamento ipertestuale genitore debba essere aggiunto a un elenco di collegamenti visualizzati quando viene invocato. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Determina se il collegamento ipertestuale debba essere evidenziato al clic. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Determina se il collegamento ipertestuale debba essere evidenziato al clic. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Determina se il suono debba essere interrotto al clic sul collegamento ipertestuale. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Determina se il suono debba essere interrotto al clic sul collegamento ipertestuale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
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


**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
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
public final int getColorSource()
```

Rappresenta la sorgente del colore del collegamento ipertestuale – stili o formato della porzione. Lettura/scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Restituisce:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Rappresenta la sorgente del colore del collegamento ipertestuale – stili o formato della porzione. Lettura/scrittura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

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
| obj | java.lang.Object | Il Hyperlink da confrontare con l'Hyperlink corrente. |

**Restituisce:**
boolean - **true** se il Hyperlink specificato è uguale all'Hyperlink corrente; altrimenti, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Determina se le due istanze di Hyperlink sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Il Hyperlink da confrontare con l'Hyperlink corrente. |

**Restituisce:**
boolean - **true** se il Hyperlink specificato è uguale all'Hyperlink corrente; altrimenti, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Verifica l'uguaglianza di due collegamenti ipertestuali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primo collegamento ipertestuale da testare. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Secondo collegamento ipertestuale da testare. |

**Restituisce:**
boolean - **true** se i collegamenti ipertestuali sono uguali.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Verifica la disuguaglianza di due collegamenti ipertestuali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primo collegamento ipertestuale da testare. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Secondo collegamento ipertestuale da testare. |

**Restituisce:**
boolean - **false** se i collegamenti ipertestuali sono uguali.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funziona come funzione hash per un tipo specifico, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int - Codice hash per un URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject