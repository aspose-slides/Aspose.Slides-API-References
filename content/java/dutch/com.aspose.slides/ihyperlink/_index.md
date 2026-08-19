---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Stelt een hyperlink voor.
type: docs
url: /nl/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Stelt een hyperlink voor.
## Methoden

| Method | Description |
| --- | --- |
| [getActionType()](#getActionType--) | Retourneert het type van de actie van HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Specificeert de externe URL. Als deze eigenschap niet null wordt, wordt eigenschap TargetSlide null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Stelt een hyperlink voor die is ingesteld voor dit gedeelte, ongeacht de feitelijke inhoud van het gedeelte. |
| [getTargetSlide()](#getTargetSlide--) | Als de HyperlinkEx zich op een specifieke dia richt, wordt die dia geretourneerd. |
| [getTargetFrame()](#getTargetFrame--) | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink, indien aanwezig. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink, indien aanwezig. |
| [getTooltip()](#getTooltip--) | Retourneert de tekenreeks die mogelijk in een gebruikersinterface wordt weergegeven en geassocieerd is met de bovenliggende hyperlink. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Retourneert de tekenreeks die mogelijk in een gebruikersinterface wordt weergegeven en geassocieerd is met de bovenliggende hyperlink. |
| [getHistory()](#getHistory--) | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. |
| [setHistory(boolean value)](#setHistory-boolean-) | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. |
| [getHighlightClick()](#getHighlightClick--) | Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Bepaalt of het geluid moet worden gestopt bij een klik op de hyperlink. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Bepaalt of het geluid moet worden gestopt bij een klik op de hyperlink. |
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

**Retour:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Specificeert de externe URL. Als deze eigenschap niet null wordt, wordt eigenschap TargetSlide null. Alleen-lezen String.

**Retour:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Stelt een hyperlink voor die is ingesteld voor dit gedeelte, ongeacht de feitelijke inhoud van het gedeelte.

--------------------

PowerPoint reageert specifiek voor koppelingen en hun overeenkomstige tekst in een gedeelte. Het maakt het mogelijk om tekst voor de hyperlink te creëren in de vorm van een geldige URL, verschillend van het daadwerkelijke adres van de koppeling. In dit geval, wanneer u de koppeling bekijkt in het bewerkingsvenster, wordt deze aangepast om overeen te komen met het tekstgedeelte. Deze eigenschap stelt de oorspronkelijke waarde van de hyperlink voor.

**Retour:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Als de HyperlinkEx zich op een specifieke dia richt, wordt die dia geretourneerd. Als de eigenschap niet null wordt, wordt eigenschap ExternalUrl null. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Retour:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink, indien aanwezig. Lezen/schrijven String.

**Retour:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink, indien aanwezig. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Retourneert de tekenreeks die mogelijk in een gebruikersinterface wordt weergegeven en geassocieerd is met de bovenliggende hyperlink. Lezen/schrijven String.

**Retour:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Retourneert de tekenreeks die mogelijk in een gebruikersinterface wordt weergegeven en geassocieerd is met de bovenliggende hyperlink. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. Lezen/schrijven boolean.

**Retour:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. Lezen/schrijven boolean.

**Retour:**
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

Bepaalt of het geluid moet worden gestopt bij een klik op de hyperlink. Lezen/schrijven boolean.

**Retour:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Bepaalt of het geluid moet worden gestopt bij een klik op de hyperlink. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Stelt het afspelende geluid van de hyperlink voor. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haal de eerste vormhyperlink op
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraheer het hyperlinkgeluid in een byte-array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retour:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Stelt het afspelende geluid van de hyperlink voor. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haal de eerste vormhyperlink op
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraheer het hyperlinkgeluid in een byte-array
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

**Retour:**
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

**Retour:**
boolean - **true** als de opgegeven Hyperlink gelijk is aan de huidige Hyperlink; anders, **false**.