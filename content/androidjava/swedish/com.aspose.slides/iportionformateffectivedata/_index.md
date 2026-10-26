---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller effektiva egenskaper för formatering av textavsnitt.
type: docs
url: /sv/com.aspose.slides/iportionformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Oföränderligt objekt som innehåller effektiva formateringsegenskaper för textavsnitt.

--------------------

Detta gränssnitt används tillsammans med gränssnittet [IPortionFormat](../../com.aspose.slides/iportionformat) för att returnera effektiva formateringsvärden med ärftlighet tillämpad.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returnerar bokmärkesidentifierare. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returnerar hyperlänken som definierats för mus-klick. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returnerar hyperlänken som definierats för muspekning. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Returnerar bokmärkesidentifierare. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Returnerar hyperlänken som definierats för mus-klick. Skrivskyddad [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Returnerar hyperlänken som definierats för muspekning. Skrivskyddad [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink)