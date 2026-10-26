---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som innehåller effektiva formatinställningar för textavsnitt.
type: docs
url: /sv/com.aspose.slides/iportionformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Oföränderligt objekt som innehåller effektiva formatinställningar för textavsnitt.

--------------------

Detta gränssnitt används tillsammans med [IPortionFormat](../../com.aspose.slides/iportionformat)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returnerar bokmärkesidentifierare. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returnerar hyperlänken som definierats för musklick. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returnerar hyperlänken som definierats för musöver. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Returnerar bokmärkesidentifierare. Läs-endast String.

**Returnerar:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Returnerar hyperlänken som definierats för musklick. Läs-endast [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Returnerar hyperlänken som definierats för musöver. Läs-endast [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink)