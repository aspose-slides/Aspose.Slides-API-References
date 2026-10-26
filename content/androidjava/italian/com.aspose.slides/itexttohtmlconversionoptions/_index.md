---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opzioni per estrarre HTML dal testo Pptx.
type: docs
url: /it/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opzioni per estrarre HTML dal testo Pptx.
## Metodi

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Restituisce o imposta il valore, indicando se devono essere aggiunte intestazioni Clipboard. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Restituisce o imposta il valore, indicando se devono essere aggiunte intestazioni Clipboard. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno sarà memorizzato. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno sarà memorizzato. |
| [getEncodingName()](#getEncodingName--) | Restituisce o imposta il nome della codifica HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Restituisce o imposta il nome della codifica HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


Restituisce o imposta il valore, indicando se devono essere aggiunte intestazioni Clipboard. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


Restituisce o imposta il valore, indicando se devono essere aggiunte intestazioni Clipboard. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. Lettura/Scrittura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Restituisce:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


Restituisce o imposta la profondità di ereditarietà per le proprietà del testo. Lettura/Scrittura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno sarà memorizzato. Lettura/Scrittura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Restituisce:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


Restituisce o imposta un oggetto callback che controlla come l'oggetto esterno sarà memorizzato. Lettura/Scrittura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


Restituisce o imposta il nome della codifica HTML. Questo valore sarà salvato nel file HTML generato, ma spetta al chiamante assicurarsi che il file venga salvato con questa codifica. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


Restituisce o imposta il nome della codifica HTML. Questo valore sarà salvato nel file HTML generato, ma spetta al chiamante assicurarsi che il file venga salvato con questa codifica. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |