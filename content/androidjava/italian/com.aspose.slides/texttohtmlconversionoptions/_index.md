---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Opzioni per estrarre HTML dal testo Pptx.
type: docs
url: /it/com.aspose.slides/texttohtmlconversionoptions/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Opzioni per estrarre HTML dal testo Pptx.
## Constructors

| Costruttore | Descrizione |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Methods

| Metodo | Descrizione |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Restituisce o imposta il valore, indicando se aggiungere le intestazioni Clipboard. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Restituisce o imposta il valore, indicando se aggiungere le intestazioni Clipboard. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno verrà memorizzato. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno verrà memorizzato. |
| [getEncodingName()](#getEncodingName--) | Restituisce o imposta il nome della codifica HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Restituisce o imposta il nome della codifica HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Restituisce o imposta il valore, indicando se aggiungere le intestazioni Clipboard. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Restituisce o imposta il valore, indicando se aggiungere le intestazioni Clipboard. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. Lettura/scrittura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Restituisce:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. Lettura/scrittura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno verrà memorizzato. Lettura/scrittura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Restituisce:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno verrà memorizzato. Lettura/scrittura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Restituisce o imposta il nome della codifica HTML. Questo valore sarà salvato nel file HTML generato, ma spetta al chiamante assicurarsi che il file venga salvato in questa codifica. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Restituisce o imposta il nome della codifica HTML. Questo valore sarà salvato nel file HTML generato, ma spetta al chiamante assicurarsi che il file venga salvato in questa codifica. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |