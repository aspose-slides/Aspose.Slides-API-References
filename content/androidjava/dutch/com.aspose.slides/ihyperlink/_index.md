---
title: IHyperlink
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een hyperlink voor.
type: docs
url: /nl/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Stelt een hyperlink voor.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getActionType()](#getActionType--) | Retourneert het type van de actie van HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Specificeert de externe URL. Als deze eigenschap niet null wordt, dan wordt eigenschap TargetSlide null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Stelt een hyperlink voor die is ingesteld voor dit gedeelte, ongeacht de feitelijke inhoud van het gedeelte. |
| [getTargetSlide()](#getTargetSlide--) | Als de HyperlinkEx een specifieke dia target, retourneert deze dia. |
| [getTargetFrame()](#getTargetFrame--) | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink wanneer die bestaat. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink wanneer die bestaat. |
| [getTooltip()](#getTooltip--) | Retourneert de tekenreeks die eventueel in een gebruikersinterface wordt getoond als geassocieerd met de bovenliggende hyperlink. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Retourneert de tekenreeks die eventueel in een gebruikersinterface wordt getoond als geassocieerd met de bovenliggende hyperlink. |
| [getHistory()](#getHistory--) | Bepaalt of het doel van de bovenliggende hyperlink aan een lijst met bekeken hyperlinks wordt toegevoegd wanneer deze wordt aangeroepen. |
| [setHistory(boolean value)](#setHistory-boolean-) | Bepaalt of het doel van de bovenliggende hyperlink aan een lijst met bekeken hyperlinks wordt toegevoegd wanneer deze wordt aangeroepen. |
| [getHighlightClick()](#getHighlightClick--) | Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Bepaalt of het geluid moet worden gestopt bij een hyperlinkklik. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Bepaalt of het geluid moet worden gestopt bij een hyperlinkklik. |
| [getSound()](#getSound--) | Stelt het afspelende geluid van de hyperlink voor. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Stelt het afspelende geluid van de hyperlink voor. |
| [getColorSource()](#getColorSource--) | Stelt de bron van de hyperlinkkleur voor – ofwel stijlen of gedeelte-indeling. |
| [setColorSource(int value)](#setColorSource-int-) | Stelt de bron van de hyperlinkkleur voor – ofwel stijlen of gedeelte-indeling. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Bepaalt of de twee Hyperlink-instanties gelijk zijn. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Retourneert het type van de actie van HyperLinkEx. Alleen-lezen [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Retourneert:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Specificeert de externe URL. Als deze eigenschap niet null wordt, wordt eigenschap TargetSlide null. Alleen-lezen String.

**Retourneert:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Stelt een hyperlink voor die voor dit gedeelte is ingesteld, ongeacht de feitelijke inhoud van het gedeelte.

--------------------

PowerPoint gedraagt zich specifiek voor koppelingen en hun bijbehorende tekst in een gedeelte. Het staat toe om tekst voor de hyperlink te maken in de vorm van een geldige URL, verschillend van het werkelijke adres van de koppeling. In dit geval, wanneer je de koppeling bekijkt in het bewerkingsvenster, wordt deze aangepast om overeen te komen met het tekstdelen. Deze eigenschap stelt de oorspronkelijke waarde van de hyperlink voor.

**Retourneert:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Als de HyperlinkEx een specifieke dia target, retourneert deze dia. Als de eigenschap niet null wordt, wordt eigenschap ExternalUrl null. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink wanneer die bestaat. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink wanneer die bestaat. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Retourneert de tekenreeks die eventueel in een gebruikersinterface wordt getoond als geassocieerd met de bovenliggende hyperlink. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Retourneert de tekenreeks die eventueel in een gebruikersinterface wordt getoond als geassocieerd met de bovenliggende hyperlink. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Bepaalt of het doel van de bovenliggende hyperlink aan een lijst met bekeken hyperlinks wordt toegevoegd wanneer deze wordt aangeroepen. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Bepaalt of het doel van de bovenliggende hyperlink aan een lijst met bekeken hyperlinks wordt toegevoegd wanneer deze wordt aangeroepen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Bepaalt of het geluid moet worden gestopt bij een hyperlinkklik. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Bepaalt of het geluid moet worden gestopt bij een hyperlinkklik. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Stelt het afspelende geluid van de hyperlink voor. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

---
> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haal de eerste vorm hyperlink op
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Haal het hyperlinkgeluid op als byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Stelt het afspelende geluid van de hyperlink voor. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

---
> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haal de eerste vorm hyperlink op
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Haal het hyperlinkgeluid op als byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Stelt de bron van de hyperlinkkleur voor – ofwel stijlen of gedeelte-indeling. Lezen/schrijven [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Retourneert:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Stelt de bron van de hyperlinkkleur voor – ofwel stijlen of gedeelte-indeling. Lezen/schrijven [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Bepaalt of de twee Hyperlink-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | De Hyperlink om te vergelijken met de huidige Hyperlink. |

**Retourneert:**
boolean - **true** als de opgegeven Hyperlink gelijk is aan de huidige Hyperlink; anders **false**.