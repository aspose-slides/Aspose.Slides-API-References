---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Fornisce un facile accesso ai collegamenti ipertestuali contenuti.
type: docs
url: /it/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Fornisce un facile accesso ai collegamenti ipertestuali contenuti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Ottiene tutti gli oggetti IHyperlinkContainer che contengono un HyperlinkClick non nullo. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Ottiene tutti gli oggetti IHyperlinkContainer che contengono un HyperlinkMouseOver non nullo. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Ottiene tutti gli oggetti IHyperlinkContainer che contengono un HyperlinkMouseOver non nullo. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Rimuove tutti i collegamenti HyperlinkClick e HyperlinkMouseOver contenuti (in tutti gli oggetti IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Ottiene tutti gli oggetti IHyperlinkContainer che contengono un HyperlinkClick non nullo. Con l'oggetto IHyperlinkContainer fornito è possibile gestire il suo collegamento ipertestuale (leggere, aggiornare o rimuovere). Vedi l'interfaccia IHyperlinkContainer.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Ottiene tutti gli oggetti IHyperlinkContainer che contengono un HyperlinkMouseOver non nullo. Con l'oggetto IHyperlinkContainer fornito è possibile gestire il suo collegamento ipertestuale (leggere, aggiornare o rimuovere). Vedi l'interfaccia IHyperlinkContainer.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Ottiene tutti gli oggetti IHyperlinkContainer che contengono un HyperlinkMouseOver non nullo. Con l'oggetto IHyperlinkContainer fornito è possibile gestire il suo collegamento ipertestuale (leggere, aggiornare o rimuovere). Vedi l'interfaccia IHyperlinkContainer.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Rimuove tutti i collegamenti ipertestuali HyperlinkClick e HyperlinkMouseOver contenuti (in tutti gli oggetti IHyperlinkContainer).