---
title: Hyperlink
second_title: Aspose.Slides Java API referencia
description: Egy hiperhivatkozást reprezentál.
type: docs
url: /hu/com.aspose.slides/hyperlink/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Hipert linket reprezentál.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Létrehoz egy hipert link példányt. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Létrehoz egy hipert link példányt, amely egy adott diára mutat. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Létrehoz egy hipert link példányt egy másik hipert link forrásként használva, felülírva a másodlagos tulajdonságokat. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Visszaad egy speciális "ne csinálj semmit" hipert linket. |
| [getMedia()](#getMedia--) | Visszaad egy speciális "mediafile lejátszása" hipert linket. |
| [getNextSlide()](#getNextSlide--) | Visszaad egy hipert linket a következő diára. |
| [getPreviousSlide()](#getPreviousSlide--) | Visszaad egy hipert linket az előző diára. |
| [getFirstSlide()](#getFirstSlide--) | Visszaad egy hipert linket a bemutató első diájára. |
| [getLastSlide()](#getLastSlide--) | Visszaad egy hipert linket a bemutató utolsó diájára. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Visszaad egy hipert linket az utoljára megtekintett diára. |
| [getEndShow()](#getEndShow--) | Visszaad egy hipert linket, amely befejezi a bemutatót. |
| [getActionType()](#getActionType--) | Visszaad a Hipert link műveletének típusát. |
| [getExternalUrl()](#getExternalUrl--) | Megadja a külső URL-t. |
| [getTargetSlide()](#getTargetSlide--) | Ha a Hipert link egy adott diát céloz, visszaadja ezt a diát. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Egy hipert linket reprezentál, amely erre a részre van beállítva a tényleges tartalomtól függetlenül. |
| [getTargetFrame()](#getTargetFrame--) | Visszaadja a szülő HTML frameset keretét a szülő hipert link céljához, ha létezik. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Visszaadja a szülő HTML frameset keretét a szülő hipert link céljához, ha létezik. |
| [getTooltip()](#getTooltip--) | Visszaadja a karakterláncot, amely felhasználói felületen megjelenhet a szülő hipert linkhez kapcsolódóan. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Visszaadja a karakterláncot, amely felhasználói felületen megjelenhet a szülő hipert linkhez kapcsolódóan. |
| [getHistory()](#getHistory--) | Meghatározza, hogy a szülő hipert link célja hozzáadandó-e a megtekintett hipert linkek listájához, amikor meghívják. |
| [setHistory(boolean value)](#setHistory-boolean-) | Meghatározza, hogy a szülő hipert link célja hozzáadandó-e a megtekintett hipert linkek listájához, amikor meghívják. |
| [getHighlightClick()](#getHighlightClick--) | Meghatározza, hogy a hipert linket kattintáskor ki kell-e emelni. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Meghatározza, hogy a hipert linket kattintáskor ki kell-e emelni. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Meghatározza, hogy a hangot le kell-e állítani hipert link kattintáskor. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Meghatározza, hogy a hangot le kell-e állítani hipert link kattintáskor. |
| [getSound()](#getSound--) | A hipert link lejátszott hangját reprezentálja. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | A hipert link lejátszott hangját reprezentálja. |
| [getColorSource()](#getColorSource--) | A hipert link szín forrását reprezentálja – akár stílusok, akár részformátum. |
| [setColorSource(int value)](#setColorSource-int-) | A hipert link szín forrását reprezentálja – akár stílusok, akár részformátum. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a két Hipert link példány egyenlő-e. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Megállapítja, hogy a két Hipert link példány egyenlő-e. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Két hipert linket tesztel az egyenlőségre. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Két hipert linket tesztel a különbözőségre. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash táblában való használatra. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Létrehoz egy hipert link példányt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hipert link URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Létrehoz egy hipert link példányt, amely egy adott diára mutat. Megjegyzés: a létrehozott hipert linket ugyanabból a bemutatóból származó objektumhoz kell hozzárendelni, ellenkező esetben a link NoAction-ként lesz mentve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Létrehoz egy hipert link példányt egy másik hipert link forrásként használva, felülírva a másodlagos tulajdonságokat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Forrás hipert link |
| targetFrame | java.lang.String | Cél keret |
| tooltip | java.lang.String | Buborékszöveg |
| history | boolean | Meghatározza, hogy a szülő hipert link célja hozzáadandó-e a megtekintett hipert linkek listájához, amikor meghívják. |
| stopSoundsOnClick | boolean | Meghatározza, hogy a hangot le kell-e állítani hipert link kattintáskor. |
| highlightClick | boolean | Meghatározza, hogy a hipert linket kattintáskor ki kell-e emelni. |

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

Visszaad egy speciális "ne csinálj semmit" hipert linket. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Visszaad egy speciális "mediafile lejátszása" hipert linket. Használják AudioFrame és VideoFrame esetén. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Visszaad egy hipert linket a következő diára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Visszaad egy hipert linket az előző diára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Visszaad egy hipert linket a bemutató első diájára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Visszaad egy hipert linket a bemutató utolsó diájára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Visszaad egy hipert linket az utoljára megtekintett diára. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Visszaad egy hipert linket, amely befejezi a bemutatót. Csak olvasható [Hyperlink](../../com.aspose.slides/hyperlink).

**Visszatér:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Visszaad a Hipert link műveletének típusát. Csak olvasható [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Visszatér:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Megadja a külső URL-t. Csak olvasható String.

**Visszatér:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Ha a Hipert link egy adott diát céloz, visszaadja ezt a diát. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Egy hipert linket reprezentál, amely erre a részre van beállítva a tényleges tartalomtól függetlenül.

--------------------

A PowerPoint speciálisan kezeli a hivatkozásokat és azokhoz tartozó szöveget egy részben. Lehetővé teszi, hogy a hipert link szövegét egy érvényes URL formájában hozza létre, amely eltér a hivatkozás tényleges címétől. Ebben az esetben, amikor a szerkesztőablakban megtekinti a hivatkozást, az a szövegrésznek megfelelően módosul. Ez a tulajdonság a hipert link eredeti értékét reprezentálja.

**Visszatér:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Visszaadja a szülő HTML frameset keretét a szülő hipert link céljához, ha létezik. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Visszaadja a szülő HTML frameset keretét a szülő hipert link céljához, ha létezik. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Visszaadja a karakterláncot, amely felhasználói felületen megjelenhet a szülő hipert linkhez kapcsolódóan. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Visszaadja a karakterláncot, amely felhasználói felületen megjelenhet a szülő hipert linkhez kapcsolódóan. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Meghatározza, hogy a szülő hipert link célja hozzáadandó-e a megtekintett hipert linkek listájához, amikor meghívják. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Meghatározza, hogy a szülő hipert link célja hozzáadandó-e a megtekintett hipert linkek listájához, amikor meghívják. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Meghatározza, hogy a hipert linket kattintáskor ki kell-e emelni. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Meghatározza, hogy a hipert linket kattintáskor ki kell-e emelni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Meghatározza, hogy a hangot le kell-e állítani hipert link kattintáskor. Olvasás/írás boolean.

**Visszatér:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Meghatározza, hogy a hangot le kell-e állítani hipert link kattintáskor. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

A hipert link lejátszott hangját reprezentálja. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Az első alakzat hiperhivatkozásának lekérdezése
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Kinyeri a hiperhivatkozás hangját byte tömbben
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

A hipert link lejátszott hangját reprezentálja. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Az első alakzat hiperhivatkozásának lekérdezése
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Kinyeri a hiperhivatkozás hangját byte tömbben
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

A hipert link szín forrását reprezentálja – akár stílusok, akár részformátum. Olvasás/írás [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Visszatér:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

A hipert link szín forrását reprezentálja – akár stílusok, akár részformátum. Olvasás/írás [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a két Hipert link példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A Hipert link, amelyet a jelenlegi Hipert linkkel összehasonlítanak. |

**Visszatér:**
boolean - **true** ha a megadott Hipert link egyenlő a jelenlegi Hipert linkkel; egyébként **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Megállapítja, hogy a két Hipert link példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | A Hipert link, amelyet a jelenlegi Hipert linkkel összehasonlítanak. |

**Visszatér:**
boolean - **true** ha a megadott Hipert link egyenlő a jelenlegi Hipert linkkel; egyébként **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Két hipert linket tesztel az egyenlőségre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Első hipert link a teszthez. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Második hipert link a teszthez. |

**Visszatér:**
boolean - **true** ha a hipert linkek egyenlőek.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Két hipert linket tesztel a különbözőségre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Első hipert link a teszthez. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Második hipert link a teszthez. |

**Visszatér:**
boolean - **false** ha a hipert linkek egyenlőek.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash táblában való használatra.

**Visszatér:**
int - Hash kód egy URL-hez.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject