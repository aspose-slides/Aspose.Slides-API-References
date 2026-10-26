---
title: Hyperlink
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje hypertextový odkaz.
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

Představuje hypertextový odkaz.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Vytvoří instanci hypertextového odkazu. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Vytvoří instanci hypertextového odkazu, který ukazuje na konkrétní snímek. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Vytvoří instanci hypertextového odkazu pomocí jiného hypertextového odkazu jako zdroje, přepisuje sekundární vlastnosti. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Vrací speciální hypertextový odkaz „nedělej nic“. |
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
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Představuje hypertextový odkaz nastavený pro tuto část bez ohledu na skutečný obsah části. |
| [getTargetFrame()](#getTargetFrame--) | Vrací rámec v rámci nadřazené HTML sady rámců pro cíl nadřazeného hypertextového odkazu, pokud existuje. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Vrací rámec v rámci nadřazené HTML sady rámců pro cíl nadřazeného hypertextového odkazu, pokud existuje. |
| [getTooltip()](#getTooltip--) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. |
| [getHistory()](#getHistory--) | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho volání. |
| [setHistory(boolean value)](#setHistory-boolean-) | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho volání. |
| [getHighlightClick()](#getHighlightClick--) | Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. |
| [getSound()](#getSound--) | Představuje přehrávaný zvuk hypertextového odkazu. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Představuje přehrávaný zvuk hypertextového odkazu. |
| [getColorSource()](#getColorSource--) | Představuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. |
| [setColorSource(int value)](#setColorSource-int-) | Představuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda jsou dvě instance Hyperlink rovny. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Určuje, zda jsou dvě instance Hyperlink rovny. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testuje dva hypertextové odkazy na rovnost. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testuje dva hypertextové odkazy na nerovnost. |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách jako hashovací tabulka. |
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

Vytvoří instanci hypertextového odkazu pomocí jiného hypertextového odkazu jako zdroje, přepisuje sekundární vlastnosti.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Zdrojový hypertextový odkaz |
| targetFrame | java.lang.String | Cílový rámec |
| tooltip | java.lang.String | Text tooltipu |
| history | boolean | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho volání. |
| stopSoundsOnClick | boolean | Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. |
| highlightClick | boolean | Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení, typ long.

**Vrací:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Vrací speciální hypertextový odkaz „nedělej nic“. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Vrací speciální hypertextový odkaz „přehrát mediální soubor“. Používá se v AudioFrame a VideoFrame. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Vrací hypertextový odkaz na následující snímek. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Vrací hypertextový odkaz na předchozí snímek. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Vrací hypertextový odkaz na první snímek prezentace. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Vrací hypertextový odkaz na poslední snímek prezentace. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Vrací hypertextový odkaz na naposledy zobrazený snímek. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Vrací hypertextový odkaz, který ukončuje prezentaci. Pouze ke čtení [Hyperlink](../../com.aspose.slides/hyperlink).

**Vrací:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Vrací typ akce hypertextového odkazu. Pouze ke čtení [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Vrací:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Určuje externí URL. Pouze ke čtení String.

**Vrací:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Pokud hypertextový odkaz cílí na konkrétní snímek, vrací tento snímek. Pouze ke čtení [ISlide](../../com.aspose.slides/islide).

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Představuje hypertextový odkaz nastavený pro tuto část bez ohledu na skutečný obsah části.

--------------------

PowerPoint se chová specificky pro odkazy a jejich odpovídající text v části. Umožňuje vytvořit text hypertextového odkazu ve formě platné URL, odlišné od skutečné adresy odkazu. V takovém případě, když zobrazujete odkaz v okně úprav, bude změněn tak, aby odpovídal textové části. Tato vlastnost představuje původní hodnotu hypertextového odkazu.

**Vrací:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Vrací rámec v rámci nadřazené HTML sady rámců pro cíl nadřazeného hypertextového odkazu, pokud existuje. Čtení/zápis String.

**Vrací:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Vrací rámec v rámci nadřazené HTML sady rámců pro cíl nadřazeného hypertextového odkazu, pokud existuje. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Čtení/zápis String.

**Vrací:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho volání. Čtení/zápis boolean.

**Vrací:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán do seznamu zobrazených hypertextových odkazů při jeho volání. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. Čtení/zápis boolean.

**Vrací:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Určuje, zda má být hypertextový odkaz zvýrazněn při kliknutí. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. Čtení/zápis boolean.

**Vrací:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Určuje, zda má být zvuk zastaven při kliknutí na hypertextový odkaz. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Představuje přehrávaný zvuk hypertextového odkazu. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

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

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Představuje přehrávaný zvuk hypertextového odkazu. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

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

Představuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. Čtení/zápis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Vrací:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Představuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. Čtení/zápis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

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
| obj | java.lang.Object | Hyperlink, se kterým se porovnává aktuální Hyperlink. |

**Vrací:**
boolean – **true** pokud je zadaný Hyperlink roven aktuálnímu Hyperlink; jinak **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Určuje, zda jsou dvě instance Hyperlink rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink, se kterým se porovnává aktuální Hyperlink. |

**Vrací:**
boolean – **true** pokud je zadaný Hyperlink roven aktuálnímu Hyperlink; jinak **false**.
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

**Vrací:**
boolean – **true** pokud jsou hypertextové odkazy rovny.
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

**Vrací:**
boolean – **false** pokud jsou hypertextové odkazy rovny.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách jako hashovací tabulka.

**Vrací:**
int – Hash kód pro URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject