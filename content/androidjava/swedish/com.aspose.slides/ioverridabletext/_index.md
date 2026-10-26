---
title: IOverridableText
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar överskrivbar text för ett diagram.
type: docs
url: /sv/com.aspose.slides/ioverridabletext/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Representerar överskrivbar text för ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan innehålla en rik formaterad text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initierar TextFrameForOverriding med texten i paramener "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Kan innehålla en rik formaterad text. Om denna egendom är null så åsidosätter detta formaterade textvärde den automatiskt genererade texten. Automatisk genererad text är en implicit egenskap för datalabeln, enhetsetiketten för värdeaxeln, axelrubriken, diagramrubriken, trendlinjens etikett. Automatisk genererad text formateras med egenskapen IFormattedTextContainer.TextFormat. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Initierar TextFrameForOverriding med texten i paramener "text". Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text för en ny TextFrameForOverriding. |

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe) - Textram [ITextFrame](../../com.aspose.slides/itextframe)