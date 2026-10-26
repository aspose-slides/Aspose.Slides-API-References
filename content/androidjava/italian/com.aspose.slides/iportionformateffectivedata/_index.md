---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides per Android via Java API Reference
description: Oggetto immutabile che contiene le proprietà di formattazione della porzione di testo effettiva.
type: docs
url: /it/com.aspose.slides/iportionformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà di formattazione della porzione di testo effettiva.

--------------------

Questa interfaccia è usata insieme all'interfaccia [IPortionFormat](../../com.aspose.slides/iportionformat) per restituire i valori di formattazione effettiva con ereditarietà applicata.
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

Restituisce l'identificatore del segnalibro. Solo lettura String.

**Restituisce:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

Restituisce il collegamento ipertestuale definito per il click del mouse. Solo lettura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

Restituisce il collegamento ipertestuale definito per il passaggio del mouse. Solo lettura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)