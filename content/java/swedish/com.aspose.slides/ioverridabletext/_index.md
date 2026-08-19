---
title: IOverridableText
second_title: Aspose.Slides för Java API-referens
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
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initierar TextFrameForOverriding med texten i parametern "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Kan innehålla en rik formaterad text. Om denna egenskap inte är null så åsidosätter detta formaterade textvärde den automatiskt genererade texten. Den automatiskt genererade texten är en implicit egenskap för datamärket, enheten för displayen på värdeaxeln, axelns titel, diagramtitel, trendlinjens etikett. Den automatiskt genererade texten formateras med IFormattedTextContainer.TextFormat-egenskapen. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Initierar TextFrameForOverriding med texten i parametern "text". Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text för en ny TextFrameForOverriding. |

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe) - Textram [ITextFrame](../../com.aspose.slides/itextframe)