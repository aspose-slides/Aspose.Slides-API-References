---
title: NormalViewProperties
second_title: Aspose.Slides Androidhoz – Java API hivatkozás
description: A normál nézet tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/normalviewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

A normál nézet tulajdonságait képviseli. A normál nézet három tartalmi régióból áll: a diát magát, egy oldali tartalmi régiót és egy alsó tartalmi régiót.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Példányosít egy prezentáció objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Módszerek

| Method | Leírás |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha vázlat tartalmat jelenít meg a normál nézet valamelyik tartalmi régiójában. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha vázlat tartalmat jelenít meg a normál nézet valamelyik tartalmi régiójában. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Megadja, hogy a függőleges elválasztó minimális állapotba csapódjon-e, ha az oldali régió elég kicsi. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Megadja, hogy a függőleges elválasztó minimális állapotba csapódjon-e, ha az oldali régió elég kicsi. |
| [getVerticalBarState()](#getVerticalBarState--) | Megadja, hogy a függőleges elválasztó sáv milyen állapotban legyen megjelenítve. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Megadja, hogy a függőleges elválasztó sáv milyen állapotban legyen megjelenítve. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Megadja, hogy a vízszintes elválasztó sáv milyen állapotban legyen megjelenítve. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Megadja, hogy a vízszintes elválasztó sáv milyen állapotban legyen megjelenítve. |
| [getPreferSingleView()](#getPreferSingleView--) | Megadja, hogy a felhasználó a három tartalmi régióból álló szabványos normál nézet helyett egy teljesablakos egyetlen tartalmi régiót részesít-e előnyben. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Megadja, hogy a felhasználó a három tartalmi régióból álló szabványos normál nézet helyett egy teljesablakos egyetlen tartalmi régiót részesít-e előnyben. |
| [getRestoredLeft()](#getRestoredLeft--) | Ez az elem meghatározza az oldali tartalmi régió méretét a normál nézetben, amikor a régió változó, helyreállított méretű (nem minimalizált vagy maximalizált). |
| [getRestoredTop()](#getRestoredTop--) | Ez az elem meghatározza a felső diarégió méretét a normál nézetben, amikor a régió változó, helyreállított méretű (nem minimalizált vagy maximalizált). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha vázlat tartalmat jelenít meg a normál nézet valamelyik tartalmi régiójában. Olvasás/írás, boolean.

**Visszatérési érték:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha vázlat tartalmat jelenít meg a normál nézet valamelyik tartalmi régiójában. Olvasás/írás, boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Megadja, hogy a függőleges elválasztó minimális állapotba csapódjon-e, ha az oldali régió elég kicsi. Olvasás/írás, boolean.

**Visszatérési érték:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Megadja, hogy a függőleges elválasztó minimális állapotba csapódjon-e, ha az oldali régió elég kicsi. Olvasás/írás, boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Megadja, hogy a függőleges elválasztó sáv milyen állapotban legyen megjelenítve. Egy függőleges elválasztó sáv elválasztja a diát az oldali tartalmi régiótól.

**Visszatérési érték:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Megadja, hogy a függőleges elválasztó sáv milyen állapotban legyen megjelenítve. Egy függőleges elválasztó sáv elválasztja a diát az oldali tartalmi régiótól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Megadja, hogy a vízszintes elválasztó sáv milyen állapotban legyen megjelenítve. Egy vízszintes elválasztó sáv elválasztja a diát a diától alatta lévő tartalmi régiótól.

**Visszatérési érték:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Megadja, hogy a vízszintes elválasztó sáv milyen állapotban legyen megjelenítve. Egy vízszintes elválasztó sáv elválasztja a diát a diától alatta lévő tartalmi régiótól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Megadja, hogy a felhasználó a három tartalmi régióból álló szabványos normál nézet helyett egy teljesablakos egyetlen tartalmi régiót részesít-e előnyben. Ha engedélyezve van, az alkalmazás egy tartalmi régiót jeleníthet meg az egész ablakban. Olvasás/írás, boolean.

**Visszatérési érték:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Megadja, hogy a felhasználó a három tartalmi régióból álló szabványos normál nézet helyett egy teljesablakos egyetlen tartalmi régiót részesít-e előnyben. Ha engedélyezve van, az alkalmazás egy tartalmi régiót jeleníthet meg az egész ablakban. Olvasás/írás, boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Ez az elem meghatározza az oldali tartalmi régió méretét a normál nézetben, amikor a régió változó, helyreállított méretű (nem minimalizált vagy maximalizált). Csak olvasás [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatérési érték:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Ez az elem meghatározza a felső diarégió méretét a normál nézetben, amikor a régió változó, helyreállított méretű (nem minimalizált vagy maximalizált). Csak olvasás [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatérési érték:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)