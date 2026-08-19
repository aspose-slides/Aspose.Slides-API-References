---
title: Hyperlink
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje hypertextový odkaz.
type: docs
url: /cs/com.aspose.slides/hyperlink/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Reprezentuje hypertextový odkaz.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Vytvoří instanci hypertextového odkazu. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Vytvoří instanci hypertextového odkazu, který ukazuje na konkrétní snímek. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Vytvoří instanci hypertextového odkazu pomocí jiného hypertextového odkazu jako zdroje, přepisující sekundární vlastnosti. |

## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Vrací speciální hypertextový odkaz „nic nedělej“. |
| [getMedia()](#getMedia--) | Vrací speciální hypertextový odkaz „přehrát mediální soubor“. |
| [getNextSlide()](#getNextSlide--) | Vrací hypertextový odkaz na následující snímek. |
| [getPreviousSlide()](#getPreviousSlide--) | Vrací hypertextový odkaz na předchozí snímek. |
| [getFirstSlide()](#getFirstSlide--) | Vrací hypertextový odkaz na první snímek prezentace. |
| [getLastSlide()](#getLastSlide--) | Vrací hypertextový odkaz na poslední snímek prezentace. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Vrací hypertextový odkaz na naposledy zobrazený snímek. |
| [getEndShow()](#getEndShow--) | Vrací hypertextový odkaz, který ukončuje prezentaci. |
| [getActionType()](#getActionType--) | Vrací typ akce hypertextového odkazu. |
| [getExternalUrl()](#getExternalUrl--) | Určuje externí URL. |
| [getTargetSlide()](#getTargetSlide--) | Pokud hypertextový odkaz cílí na konkrétní snímek, vrací tento snímek. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Reprezentuje hypertextový odkaz nastavený pro tuto část nezávisle na jejím skutečném obsahu. |
| [getTargetFrame()](#getTargetFrame--) | Vrací rámec v nadřazené HTML sadě rámců pro cíl nadřazeného hypertextového odkazu, pokud existuje. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Vrací rámec v nadřazené HTML sadě rámců pro cíl nadřazeného hypertextového odkazu, pokud existuje. |
| [getTooltip()](#getTooltip--) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. |
| [getHistory()](#getHistory--) | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. |
| [setHistory(boolean value)](#setHistory-boolean-) | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. |
| [getHighlightClick()](#getHighlightClick--) | Určuje, zda má být hypertextový odkaz při kliknutí zvýrazněn. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Určuje, zda má být hypertextový odkaz při kliknutí zvýrazněn. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Určuje, zda má být při kliknutí na hypertextový odkaz zastavena zvuková stopa. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Určuje, zda má být při kliknutí na hypertextový odkaz zastavena zvuková stopa. |
| [getSound()](#getSound--) | Reprezentuje přehrávaný zvuk hypertextového odkazu. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Reprezentuje přehrávaný zvuk hypertextového odkazu. |
| [getColorSource()](#getColorSource--) | Reprezentuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. |
| [setColorSource(int value)](#setColorSource-int-) | Reprezentuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda jsou dvě instance Hyperlink rovny. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Určuje, zda jsou dvě instance Hyperlink rovny. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testuje dva hypertextové odkazy na rovnost. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testuje dva hypertextové odkazy na nerovnost. |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách jako je hash tabulka. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Vytvoří instanci hypertextového odkazu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL hypertextového odkazu. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Vytvoří instanci hypertextového odkazu, který ukazuje na konkrétní snímek. Poznámka: vytvořený hypertextový odkaz by měl být přiřazen k nějakému objektu ze stejné prezentace, jinak bude odkaz uložen jako NoAction.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Cílový snímek. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Vytvoří instanci hypertextového odkazu pomocí jiného hypertextového odkazu jako zdroje, přepisující sekundární vlastnosti.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Zdrojový hypertextový odkaz |
| targetFrame | java.lang.String | Cílový rámec |
| tooltip | java.lang.String | Text bublinové nápovědy |
| history | boolean | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. |
| stopSoundsOnClick | boolean | Určuje, zda má být při kliknutí na hypertextový odkaz zastavena zvuková stopa. |
| highlightClick | boolean | Určuje, zda má být hypertextový odkaz při kliknutí zvýrazněn. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Návratová hodnota:**  
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Vrací speciální hypertextový odkaz „nic nedělej“. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Vrací speciální hypertextový odkaz „přehrát mediální soubor“. Používá se v AudioFrame a VideoFrame. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Vrací hypertextový odkaz na následující snímek. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Vrací hypertextový odkaz na předchozí snímek. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Vrací hypertextový odkaz na první snímek prezentace. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Vrací hypertextový odkaz na poslední snímek prezentace. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Vrací hypertextový odkaz na naposledy zobrazený snímek. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Vrací hypertextový odkaz, který ukončuje prezentaci. Pouze pro čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Návratová hodnota:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Vrací typ akce hypertextového odkazu. Pouze pro čtení [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Návratová hodnota:**  
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Určuje externí URL. Pouze pro čtení String.

**Návratová hodnota:**  
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Pokud hypertextový odkaz cílí na konkrétní snímek, vrací tento snímek. Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Návratová hodnota:**  
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Reprezentuje hypertextový odkaz nastavený pro tuto část nezávisle na jejím skutečném obsahu.

--------------------

PowerPoint se chová specificky k odkazům a jejich odpovídajícímu textu v části. Umožňuje vytvořit text pro hypertextový odkaz ve formě platné URL, odlišný od skutečné adresy odkazu. V takovém případě, když zobrazíte odkaz v editačním okně, bude změněn tak, aby odpovídal textové části. Tato vlastnost představuje původní hodnotu hypertextového odkazu.

**Návratová hodnota:**  
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. Čtení/Zápis String.

**Návratová hodnota:**  
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Čtení/Zápis String.

**Návratová hodnota:**  
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. Čtení/Zápis boolean.

**Návratová hodnota:**  
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho vyvolání. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Určuje, zda má být hypertextový odkaz při kliknutí zvýrazněn. Čtení/Zápis boolean.

**Návratová hodnota:**  
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Určuje, zda má být hypertextový odkaz při kliknutí zvýrazněn. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Určuje, zda má být při kliknutí na hypertextový odkaz zastavena zvuková stopa. Čtení/Zápis boolean.

**Návratová hodnota:**  
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Určuje, zda má být při kliknutí na hypertextový odkaz zastavena zvuková stopa. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Reprezentuje přehrávaný zvuk hypertextového odkazu. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá hypertextový odkaz prvního tvaru
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

**Návratová hodnota:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Reprezentuje přehrávaný zvuk hypertextového odkazu. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá hypertextový odkaz prvního tvaru
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Reprezentuje zdroj barvy hypertextového odkazu – buď styly nebo formát části. Čtení/Zápis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Návratová hodnota:**  
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Reprezentuje zdroj barvy hypertextového odkazu – buď styly nebo formát části. Čtení/Zápis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda jsou dvě instance Hyperlink rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Hypertextový odkaz, se kterým se porovnává aktuální Hyperlink. |

**Návratová hodnota:**  
boolean - **true** pokud je zadaný Hyperlink roven aktuálnímu Hyperlinku; jinak **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Určuje, zda jsou dvě instance Hyperlink rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hypertextový odkaz, se kterým se porovnává aktuální Hyperlink. |

**Návratová hodnota:**  
boolean - **true** pokud je zadaný Hyperlink roven aktuálnímu Hyperlinku; jinak **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Testuje dva hypertextové odkazy na rovnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | První hypertextový odkaz k testování. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Druhý hypertextový odkaz k testování. |

**Návratová hodnota:**  
boolean - **true** pokud jsou hypertextové odkazy rovny.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Testuje dva hypertextové odkazy na nerovnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | První hypertextový odkaz k testování. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Druhý hypertextový odkaz k testování. |

**Návratová hodnota:**  
boolean - **false** pokud jsou hypertextové odkazy rovny.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách jako je hash tabulka.

**Návratová hodnota:**  
int - Hash kód pro URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Návratová hodnota:**  
com.aspose.slides.IDOMObject