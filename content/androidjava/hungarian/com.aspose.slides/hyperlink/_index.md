---
title: Hyperlink
second_title: Aspose.Slides Android számára Java API referencia
description: Egy hiperhivatkozást reprezentál.
type: docs
url: /hu/com.aspose.slides/hyperlink/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Az összes megvalósított interfész:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Egy hiperhivatkozást reprezentál.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Létrehozza egy hiperhivatkozás példányát. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Létrehozza egy hiperhivatkozás példányát, amely egy adott diára mutat. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Létrehozza egy hiperhivatkozás példányát egy másik hiperhivatkozás forrásként való használatával, felülírva a másodlagos tulajdonságokat. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Visszaad egy speciális „ne csináljon semmit” hiperhivatkozást. |
| [getMedia()](#getMedia--) | Visszaad egy speciális „mediafájl lejátszása” hiperhivatkozást. |
| [getNextSlide()](#getNextSlide--) | Visszaad egy hiperhivatkozást a következő diára. |
| [getPreviousSlide()](#getPreviousSlide--) | Visszaad egy hiperhivatkozást az előző diára. |
| [getFirstSlide()](#getFirstSlide--) | Visszaad egy hiperhivatkozást a bemutató első diájára. |
| [getLastSlide()](#getLastSlide--) | Visszaad egy hiperhivatkozást a bemutató utolsó diájára. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Visszaad egy hiperhivatkozást az utolsó megtekintett diára. |
| [getEndShow()](#getEndShow--) | Visszaad egy hiperhivatkozást, amely befejezi a bemutatót. |
| [getActionType()](#getActionType--) | Visszaad a Hyperlink műveletének típusát. |
| [getExternalUrl()](#getExternalUrl--) | Meghatározza a külső URL-t. |
| [getTargetSlide()](#getTargetSlide--) | Ha a Hyperlink konkrét diát céloz, visszaadja ezt a diát. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Egy hiperhivatkozást reprezentál, amely erre a részre van beállítva a rész tényleges tartalmától függetlenül. |
| [getTargetFrame()](#getTargetFrame--) | Visszaad a szülő HTML keretcsoporton belüli keretet, amely a szülő hiperhivatkozás célja, ha létezik. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Visszaad a szülő HTML keretcsoporton belüli keretet, amely a szülő hiperhivatkozás célja, ha létezik. |
| [getTooltip()](#getTooltip--) | Visszaad a karakterláncot, amely felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz társítva. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Visszaad a karakterláncot, amely felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz társítva. |
| [getHistory()](#getHistory--) | Megállapítja, hogy a szülő hiperhivatkozás célja fel legyen-e véve a megtekintett hiperhivatkozások listájába, amikor meghívják. |
| [setHistory(boolean value)](#setHistory-boolean-) | Megállapítja, hogy a szülő hiperhivatkozás célja fel legyen-e véve a megtekintett hiperhivatkozások listájába, amikor meghívják. |
| [getHighlightClick()](#getHighlightClick--) | Megállapítja, hogy a hiperhivatkozást ki kell-e emelni kattintáskor. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Megállapítja, hogy a hiperhivatkozást ki kell-e emelni kattintáskor. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Megállapítja, hogy a hangot le kell-e állítani a hiperhivatkozásra kattintáskor. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Megállapítja, hogy a hangot le kell-e állítani a hiperhivatkozásra kattintáskor. |
| [getSound()](#getSound--) | A hiperhivatkozás lejátszott hangját reprezentálja. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | A hiperhivatkozás lejátszott hangját reprezentálja. |
| [getColorSource()](#getColorSource--) | A hiperhivatkozás színének forrását reprezentál – legyen az stílus vagy részformátum. |
| [setColorSource(int value)](#setColorSource-int-) | A hiperhivatkozás színének forrását reprezentál – legyen az stílus vagy részformátum. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Két hiperhivatkozást tesztel egyenlőségre. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Két hiperhivatkozást tesztel egyenlőtlenségre. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típusra, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash táblában való használatra. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Létrehozza egy hiperhivatkozás példányát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hiperváltás URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Létrehozza egy hiperhivatkozás példányát, amely egy adott diára mutat. **Megjegyzés:** a létrehozott hiperhivatkozást ugyanazon bemutató egy objektumához kell rendelni, különben a link NoActionként lesz mentve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Létrehozza egy hiperhivatkozás példányát egy másik hiperhivatkozás forrásként való használatával, felülírva a másodlagos tulajdonságokat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Forrás hiperhivatkozás |
| targetFrame | java.lang.String | Célkeret |
| tooltip | java.lang.String | Buboréksúgó szöveg |
| history | boolean | Megállapítja, hogy a szülő hiperhivatkozás célja fel legyen-e véve a megtekintett hiperhivatkozások listájába, amikor meghívják. |
| stopSoundsOnClick | boolean | Megállapítja, hogy a hangot le kell-e állítani a hiperhivatkozásra kattintáskor. |
| highlightClick | boolean | Megállapítja, hogy a hiperhivatkozást ki kell-e emelni kattintáskor. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Visszaad egy speciális „ne csináljon semmit” hiperhivatkozást. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Visszaad egy speciális „mediafájl lejátszása” hiperhivatkozást. AudioFrame és VideoFrame esetén használható. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Visszaad egy hiperhivatkozást a következő diára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Visszaad egy hiperhivatkozást az előző diára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Visszaad egy hiperhivatkozást a bemutató első diájára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Visszaad egy hiperhivatkozást a bemutató utolsó diájára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Visszaad egy hiperhivatkozást az utolsó megtekintett diára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Visszaad egy hiperhivatkozást, amely befejezi a bemutatót. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Visszaad a Hyperlink műveletének típusát. Csak olvasható [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Visszatér:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Meghatározza a külső URL-t. Csak olvasható String.

**Visszatér:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Ha a Hyperlink konkrét diát céloz, visszaadja ezt a diát. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Egy hiperhivatkozást reprezentál, amely erre a részre van beállítva a rész tényleges tartalmától függetlenül.

PowerPoint speciálisan kezeli a linkeket és a hozzájuk tartozó szöveget egy részben. Lehetővé teszi, hogy a hiperhivatkozás szövegét egy érvényes URL-ként hozza létre, amely eltér a link valós címétől. Ebben az esetben, amikor a szerkesztőablakban megtekinti a linket, a szöveg részéhez igazítva módosul. Ez a tulajdonság a hiperhivatkozás eredeti értékét képviseli.

**Visszatér:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Visszaad a szülő HTML keretcsoporton belüli keretet, amely a szülő hiperhivatkozás célja, ha létezik. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Visszaad a szülő HTML keretcsoporton belüli keretet, amely a szülő hiperhivatkozás célja, ha létezik. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Visszaad a karakterláncot, amely felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz társítva. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Visszaad a karakterláncot, amely felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz társítva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Megállapítja, hogy a szülő hiperhivatkozás célja fel legyen-e véve a megtekintett hiperhivatkozások listájába, amikor meghívják. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Megállapítja, hogy a szülő hiperhivatkozás célja fel legyen-e véve a megtekintett hiperhivatkozások listájába, amikor meghívják. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Megállapítja, hogy a hiperhivatkozást ki kell-e emelni kattintáskor. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Megállapítja, hogy a hiperhivatkozást ki kell-e emelni kattintáskor. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Megállapítja, hogy a hangot le kell-e állítani a hiperhivatkozásra kattintáskor. Olvasás/írás boolean.

**Visszatér:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Megállapítja, hogy a hangot le kell-e állítani a hiperhivatkozásra kattintáskor. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

A hiperhivatkozás lejátszott hangját reprezentálja. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Első alakzat hiperhivatkozásának lekérése
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // A hiperhivatkozás hangjának kinyerése bájt tömbbe
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

A hiperhivatkozás lejátszott hangját reprezentálja. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Az első alakzat hiperhivatkozásának lekérése
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // A hiperhivatkozás hangjának kinyerése bájt tömbbe
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

A hiperhivatkozás színének forrását reprezentál – legyen az stílus vagy részformátum. Olvasás/írás [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Visszatér:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

A hiperhivatkozás színének forrását reprezentál – legyen az stílus vagy részformátum. Olvasás/írás [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a két Hyperlink példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A Hyperlink, amelyet az aktuális Hyperlinkkel hasonlítanak össze. |

**Visszatér:**
boolean - **true** ha a megadott Hyperlink egyenlő az aktuális Hyperlinkkel; egyébként **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Megállapítja, hogy a két Hyperlink példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | A Hyperlink, amelyet az aktuális Hyperlinkkel hasonlítanak össze. |

**Visszatér:**
boolean - **true** ha a megadott Hyperlink egyenlő az aktuális Hyperlinkkel; egyébként **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Két hiperhivatkozást tesztel egyenlőségre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Első tesztelendő hiperhivatkozás. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Második tesztelendő hiperhivatkozás. |

**Visszatér:**
boolean - **true** ha a hiperhivatkozások egyenlők.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Két hiperhivatkozást tesztel egyenlőtlenségre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Első tesztelendő hiperhivatkozás. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Második tesztelendő hiperhivatkozás. |

**Visszatér:**
boolean - **false** ha a hiperhivatkozások egyenlők.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típusra, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash táblában való használatra.

**Visszatér:**
int - URL hash kódja.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaad Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject