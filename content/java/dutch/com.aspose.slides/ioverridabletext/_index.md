---
title: IOverridableText
second_title: Aspose.Slides voor Java API-referentie
description: Stelt overschrijfbare tekst voor een diagram voor.
type: docs
url: /nl/com.aspose.slides/ioverridabletext/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Stelt overschrijfbare tekst voor een diagram voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan een rijk opgemaakte tekst bevatten. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialiseer TextFrameForOverriding met de tekst in parameter "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekstwaarde automatisch gegenereerde tekst. Automatisch gegenereerde tekst is een impliciete eigenschap van het gegevenslabel, het weergave-eenheidlabel van de waardas, de as-titel, de diagramtitel, het label van de trendlijn. Automatisch gegenereerde tekst wordt opgemaakt met de IFormattedTextContainer.TextFormat eigenschap. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retourwaarde:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Initialiseer TextFrameForOverriding met de tekst in parameter "text". Als TextFrameForOverriding al is geïnitialiseerd, wordt de tekst simpelweg aangepast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst voor een nieuw TextFrameForOverriding. |

**Retourwaarde:**
[ITextFrame](../../com.aspose.slides/itextframe) - Tekstframe [ITextFrame](../../com.aspose.slides/itextframe)