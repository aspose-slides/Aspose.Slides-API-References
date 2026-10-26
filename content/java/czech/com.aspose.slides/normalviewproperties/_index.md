---
title: NormalViewProperties
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje vlastnosti normálního zobrazení.
type: docs
url: /cs/com.aspose.slides/normalviewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Reprezentuje vlastnosti normálního zobrazení. Normální zobrazení se skládá ze tří oblastí obsahu: samotného snímku, postranní oblasti obsahu a spodní oblasti obsahu.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Vytvořte objekt prezentace, který představuje soubor prezentace
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

## Metody

| Metoda | Popis |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu osnovy v kterékoliv oblasti obsahu režimu normálního zobrazení. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu osnovy v kterékoliv oblasti obsahu režimu normálního zobrazení. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Určuje, zda by svislý rozdělovač měl přecházet do zmenšeného stavu, když je postranní oblast dostatečně malá. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Určuje, zda by svislý rozdělovač měl přecházet do zmenšeného stavu, když je postranní oblast dostatečně malá. |
| [getVerticalBarState()](#getVerticalBarState--) | Určuje stav, ve kterém by měl být zobrazen svislý rozdělovač. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Určuje stav, ve kterém by měl být zobrazen svislý rozdělovač. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Určuje stav, ve kterém by měl být zobrazen vodorovný rozdělovač. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Určuje stav, ve kterém by měl být zobrazen vodorovný rozdělovač. |
| [getPreferSingleView()](#getPreferSingleView--) | Určuje, zda uživatel preferuje zobrazit jednorázovou oblast obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Určuje, zda uživatel preferuje zobrazit jednorázovou oblast obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. |
| [getRestoredLeft()](#getRestoredLeft--) | Tento prvek určuje velikost postranní oblasti obsahu normálního zobrazení, když je oblast v proměnné obnovené velikosti (ne zmenšená ani maximalizovaná). |
| [getRestoredTop()](#getRestoredTop--) | Tento prvek určuje velikost horní oblasti snímku normálního zobrazení, když je oblast v proměnné obnovené velikosti (ne zmenšená ani maximalizovaná). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu osnovy v kterékoliv oblasti obsahu režimu normálního zobrazení. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu osnovy v kterékoliv oblasti obsahu režimu normálního zobrazení. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Určuje, zda by svislý rozdělovač měl přecházet do zmenšeného stavu, když je postranní oblast dostatečně malá. Čtení/zápis boolean.

**Vrací:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Určuje, zda by svislý rozdělovač měl přecházet do zmenšeného stavu, když je postranní oblast dostatečně malá. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Určuje stav, ve kterém by měl být zobrazen svislý rozdělovač. Svislý rozdělovač odděluje snímek od postranní oblasti obsahu.

**Vrací:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Určuje stav, ve kterém by měl být zobrazen svislý rozdělovač. Svislý rozdělovač odděluje snímek od postranní oblasti obsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Určuje stav, ve kterém by měl být zobrazen vodorovný rozdělovač. Vodorovný rozdělovač odděluje snímek od oblasti obsahu pod snímkem.

**Vrací:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Určuje stav, ve kterém by měl být zobrazen vodorovný rozdělovač. Vodorovný rozdělovač odděluje snímek od oblasti obsahu pod snímkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Určuje, zda uživatel preferuje zobrazit jednorázovou oblast obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. Pokud je povoleno, aplikace může zobrazit jednu z oblastí obsahu v celé okně. Čtení/zápis boolean.

**Vrací:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Určuje, zda uživatel preferuje zobrazit jednorázovou oblast obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. Pokud je povoleno, aplikace může zobrazit jednu z oblastí obsahu v celé okně. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Tento prvek určuje velikost postranní oblasti obsahu normálního zobrazení, když je oblast v proměnné obnovené velikosti (ne zmenšená ani maximalizovaná). Pouze pro čtení [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Vrací:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Tento prvek určuje velikost horní oblasti snímku normálního zobrazení, když je oblast v proměnné obnovené velikosti (ne zmenšená ani maximalizovaná). Pouze pro čtení [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Vrací:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)