---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides pro Java API Reference
description: Neměnný objekt, který obsahuje vlastnosti formátování efektivní části textu.
type: docs
url: /cs/com.aspose.slides/iportionformateffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Neměnný objekt, který obsahuje vlastnosti formátování efektivní části textu.

--------------------

Toto rozhraní se používá spolu s rozhraním [IPortionFormat](../../com.aspose.slides/iportionformat) k vrácení hodnot efektivního formátování s aplikovaným děděním.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Vrací identifikátor záložky. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Vrací hypertextový odkaz definovaný pro kliknutí myší. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Vrací hypertextový odkaz definovaný pro přejetí myší. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Vrací identifikátor záložky. Pouze ke čtení String.

**Vrací:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Vrací hypertextový odkaz definovaný pro kliknutí myší. Pouze ke čtení [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Vrací hypertextový odkaz definovaný pro přejetí myší. Pouze ke čtení [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)