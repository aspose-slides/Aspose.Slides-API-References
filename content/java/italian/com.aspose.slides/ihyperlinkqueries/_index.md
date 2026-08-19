---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Provide easy access to contained hyperlinks.
type: docs
url: /it/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Fornisce un accesso semplice ai collegamenti ipertestuali contenuti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Removes all contained HyperlinkClick and HyperlinkMouseOver hyperlinks (in all IHyperlinkContainer subobjects). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Recupera tutti gli oggetti secondari IHyperlinkContainer che contengono un HyperlinkClick non nullo. Con l'oggetto IHyperlinkContainer fornito è possibile gestire il suo collegamento ipertestuale (leggere, aggiornare o rimuovere). Vedi l'interfaccia IHyperlinkContainer.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Recupera tutti gli oggetti secondari IHyperlinkContainer che contengono un HyperlinkMouseOver non nullo. Con l'oggetto IHyperlinkContainer fornito è possibile gestire il suo collegamento ipertestuale (leggere, aggiornare o rimuovere). Vedi l'interfaccia IHyperlinkContainer.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Recupera tutti gli oggetti secondari IHyperlinkContainer che contengono un HyperlinkMouseOver non nullo. Con l'oggetto IHyperlinkContainer fornito è possibile gestire il suo collegamento ipertestuale (leggere, aggiornare o rimuovere). Vedi l'interfaccia IHyperlinkContainer.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Rimuove tutti i collegamenti ipertestuali HyperlinkClick e HyperlinkMouseOver contenuti (in tutti gli oggetti secondari IHyperlinkContainer).