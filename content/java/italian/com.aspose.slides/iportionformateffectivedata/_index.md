---
title: IPortionFormatEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che contiene le proprietà di formattazione della porzione di testo efficace.
type: docs
url: /it/com.aspose.slides/iportionformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà di formattazione della porzione di testo efficace.

--------------------

Questa interfaccia è utilizzata insieme all'interfaccia [IPortionFormat](../../com.aspose.slides/iportionformat) per restituire i valori di formattazione efficaci con ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Restituisce l'identificatore del segnalibro. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Restituisce il collegamento ipertestuale definito per il click del mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Restituisce il collegamento ipertestuale definito per il passaggio del mouse. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Restituisce l'identificatore del segnalibro. Read-only String.

**Restituisce:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

Restituisce il collegamento ipertestuale definito per il click del mouse. Read-only [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

Restituisce il collegamento ipertestuale definito per il passaggio del mouse. Read-only [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)