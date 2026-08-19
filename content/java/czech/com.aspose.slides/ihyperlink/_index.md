---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Representuje hypertextový odkaz.
type: docs
url: /cs/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Representuje hypertextový odkaz.
## Metody

| Metoda | Popis |
| --- | --- |
| [getActionType()](#getActionType--) | Vrací typ akce HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Určuje externí URL. Pokud se tato vlastnost stane nenulovou, pak se vlastnost TargetSlide nastaví na null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representuje hypertextový odkaz, který je nastaven pro tuto část bez ohledu na skutečný obsah části. |
| [getTargetSlide()](#getTargetSlide--) | Pokud HyperlinkEx cílí na konkrétní snímek, vrací tento snímek. |
| [getTargetFrame()](#getTargetFrame--) | Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. |
| [getTooltip()](#getTooltip--) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. |
| [getHistory()](#getHistory--) | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. |
| [setHistory(boolean value)](#setHistory-boolean-) | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. |
| [getHighlightClick()](#getHighlightClick--) | Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. |
| [getSound()](#getSound--) | Representuje přehrávaný zvuk hypertextového odkazu. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representuje přehrávaný zvuk hypertextového odkazu. |
| [getColorSource()](#getColorSource--) | Representuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. |
| [setColorSource(int value)](#setColorSource-int-) | Representuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Určuje, zda jsou dvě instance Hyperlink rovny. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Vrací typ akce HyperLinkEx. Pouze pro čtení [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Vrací:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Určuje externí URL. Pokud se tato vlastnost stane nenulovou, pak se vlastnost TargetSlide nastaví na null. Pouze pro čtení String.

**Vrací:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Representuje hypertextový odkaz, který je nastaven pro tuto část bez ohledu na skutečný obsah části.

--------------------

PowerPoint se specificky chová k odkazům a jejich odpovídajícímu textu v části. Umožňuje vytvořit text pro hypertextový odkaz ve formě platné URL, odlišné od skutečné adresy odkazu. V tomto případě, když odkaz zobrazíte v editačním okně, bude upraven tak, aby odpovídal textové části. Tato vlastnost představuje původní hodnotu hypertextového odkazu.

**Vrací:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Pokud HyperlinkEx cílí na konkrétní snímek, vrací tento snímek. Pokud se tato vlastnost stane nenulovou, pak se vlastnost ExternalUrl nastaví na null. Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Vrací:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. Čtení/Zápis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Čtení/Zápis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. Čtení/Zápis boolean.

**Vrací:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. Čtení/Zápis boolean.

**Vrací:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. Čtení/Zápis boolean.

**Vrací:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Representuje přehrávaný zvuk hypertextového odkazu. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá první hypertextový odkaz tvaru
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahuje zvuk hypertextového odkazu do pole bajtů
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Representuje přehrávaný zvuk hypertextového odkazu. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá první hypertextový odkaz tvaru
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahuje zvuk hypertextového odkazu do pole bajtů
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Representuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. Čtení/Zápis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Vrací:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Representuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. Čtení/Zápis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Určuje, zda jsou dvě instance Hyperlink rovny.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink, se kterým se porovnává aktuální Hyperlink. |

**Vrací:**
boolean - **true** pokud je zadaný Hyperlink roven aktuálnímu Hyperlinku; jinak **false**.