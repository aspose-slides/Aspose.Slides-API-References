---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a hyperlink.
type: docs
url: /hu/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Egy hiperhivatkozást ábrázol.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getActionType()](#getActionType--) | Visszaadja a HyperLinkEx műveletének típusát. |
| [getExternalUrl()](#getExternalUrl--) | Megadja a külső URL-t. Ha ez a tulajdonság nem null, akkor a TargetSlide tulajdonság null lesz. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Egy hiperhivatkozást ábrázol, amelyet ennek a résznek állítanak be a tényleges tartalmától függetlenül. |
| [getTargetSlide()](#getTargetSlide--) | Ha a HyperlinkEx egy adott diára mutat, visszaadja azt a diát. |
| [getTargetFrame()](#getTargetFrame--) | Visszaadja a szülő HTML keretcsoportban lévő keretet, amely a szülő hiperhivatkozás célja, ha létezik. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Visszaadja a szülő HTML keretcsoportban lévő keretet, amely a szülő hiperhivatkozás célja, ha létezik. |
| [getTooltip()](#getTooltip--) | Visszaadja azt a karakterláncot, amely a felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz kapcsolódóan. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Visszaadja azt a karakterláncot, amely a felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz kapcsolódóan. |
| [getHistory()](#getHistory--) | Meghatározza, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívásra kerül. |
| [setHistory(boolean value)](#setHistory-boolean-) | Meghatározza, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívásra kerül. |
| [getHighlightClick()](#getHighlightClick--) | Meghatározza, hogy a hiperhivatkozást kattintáskor ki kell-e emelni. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Meghatározza, hogy a hiperhivatkozást kattintáskor ki kell-e emelni. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Meghatározza, hogy a hangot le kell-e állítani a hiperhivatkozás kattintásakor. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Meghatározza, hogy a hangot le kell-e állítani a hiperhivatkozás kattintásakor. |
| [getSound()](#getSound--) | A hiperhivatkozás lejátszott hangját ábrázolja. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | A hiperhivatkozás lejátszott hangját ábrázolja. |
| [getColorSource()](#getColorSource--) | A hiperhivatkozás színforrását ábrázolja – legyen az stílus vagy részformátum. |
| [setColorSource(int value)](#setColorSource-int-) | A hiperhivatkozás színforrását ábrázolja – legyen az stílus vagy részformátum. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Meghatározza, hogy a két Hyperlink példány egyenlő-e. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


Visszaadja a HyperLinkEx műveletének típusát. Csak olvasható [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Visszatér:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


Megadja a külső URL-t. Ha ez a tulajdonság nem null, akkor a TargetSlide tulajdonság null lesz. Csak olvasható String.

**Visszatér:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


Egy hiperhivatkozást ábrázol, amelyet ennek a résznek állítanak be a tényleges tartalmától függetlenül.

PowerPoint különleges módon kezeli a hivatkozásokat és a hozzájuk tartozó szöveget egy részben. Lehetővé teszi, hogy a hiperhivatkozáshoz szöveget hozzunk létre egy érvényes URL formájában, ami eltér a hivatkozás tényleges címétől. Ebben az esetben, amikor a szerkesztőablakban megtekinti a hivatkozást, az a szövegrészhez igazodik. Ez a tulajdonság a hiperhivatkozás eredeti értékét ábrázolja.

**Visszatér:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Ha a HyperlinkEx egy adott diára mutat, visszaadja azt a diát. Ha a tulajdonság nem null, akkor az ExternalUrl tulajdonság null lesz. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


Visszaadja a szülő HTML keretcsoportban lévő keretet, amely a szülő hiperhivatkozás célja, ha létezik. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


Visszaadja a szülő HTML keretcsoportban lévő keretet, amely a szülő hiperhivatkozás célja, ha létezik. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


Visszaadja azt a karakterláncot, amely a felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz kapcsolódóan. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


Visszaadja azt a karakterláncot, amely a felhasználói felületen megjelenhet a szülő hiperhivatkozáshoz kapcsolódóan. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


Meghatározza, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívásra kerül. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


Meghatározza, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívásra kerül. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


Meghatározza, hogy a hiperhivatkozást kattintáskor ki kell-e emelni. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


Meghatározza, hogy a hiperhivatkozást kattintáskor ki kell-e emelni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


Meghatározza, hogy a hangot le kell-e állítani a hiperhivatkozás kattintásakor. Olvasás/írás boolean.

**Visszatér:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


Meghatározza, hogy a hangot le kell-e állítani a hiperhivatkozás kattintásakor. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


A hiperhivatkozás lejátszott hangját ábrázolja. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Az első alakzat hiperhivatkozását lekéri
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // A hiperhivatkozás hangját byte tömbként kinyeri
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
public abstract void setSound(IAudio value)
```


A hiperhivatkozás lejátszott hangját ábrázolja. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Az első alakzat hiperhivatkozását lekéri
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // A hiperhivatkozás hangját byte tömbként kinyeri
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
public abstract int getColorSource()
```


A hiperhivatkozás színforrását ábrázolja – legyen az stílus vagy részformátum. Olvasás/írás [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Visszatér:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


A hiperhivatkozás színforrását ábrázolja – legyen az stílus vagy részformátum. Olvasás/írás [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


Meghatározza, hogy a két Hyperlink példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | A Hyperlink, amelyet az aktuális Hyperlinkkel hasonlítanak össze. |

**Visszatér:**
boolean - **true** ha a megadott Hyperlink egyenlő az aktuális Hyperlinkkel; egyébként **false**.