---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Representuje vlastnosti normálního zobrazení.
type: docs
url: /cs/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Representuje vlastnosti normálního zobrazení. Normální zobrazení se skládá ze tří oblastí obsahu: samotného snímku, boční oblasti obsahu a spodní oblasti obsahu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu obrysu v některé z oblastí obsahu režimu normálního zobrazení. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu obrysu v některé z oblastí obsahu režimu normálního zobrazení. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Určuje, zda by vertikální dělič měl přecházet do minimalizovaného stavu, když je boční oblast dostatečně malá. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Určuje, zda by vertikální dělič měl přecházet do minimalizovaného stavu, když je boční oblast dostatečně malá. |
| [getVerticalBarState()](#getVerticalBarState--) | Určuje stav, ve kterém by měla být zobrazena vertikální dělicí lišta. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Určuje stav, ve kterém by měla být zobrazena vertikální dělicí lišta. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Určuje stav, ve kterém by měla být zobrazena horizontální dělicí lišta. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Určuje stav, ve kterém by měla být zobrazena horizontální dělicí lišta. |
| [getPreferSingleView()](#getPreferSingleView--) | Určuje, zda uživatel upřednostňuje zobrazit jednorázovou oblast obsahu na celou obrazovku místo standardního normálního zobrazení se třemi oblastmi obsahu. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Určuje, zda uživatel upřednostňuje zobrazit jednorázovou oblast obsahu na celou obrazovku místo standardního normálního zobrazení se třemi oblastmi obsahu. |
| [getRestoredLeft()](#getRestoredLeft--) | Tento prvek určuje velikost boční oblasti obsahu normálního zobrazení, když je oblast v proměnné obnovené velikosti (ani minimalizovaná, ani maximalizovaná). |
| [getRestoredTop()](#getRestoredTop--) | Tento prvek určuje velikost horní oblasti snímku normálního zobrazení, když je oblast v proměnné obnovené velikosti (ani minimalizovaná, ani maximalizovaná). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu obrysu v některé z oblastí obsahu režimu normálního zobrazení. Čtení/Zápis boolean.

**Vrací:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obsahu obrysu v některé z oblastí obsahu režimu normálního zobrazení. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Určuje, zda by vertikální dělič měl přecházet do minimalizovaného stavu, když je boční oblast dostatečně malá. Čtení/Zápis boolean.

**Vrací:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Určuje, zda by vertikální dělič měl přecházet do minimalizovaného stavu, když je boční oblast dostatečně malá. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Určuje stav, ve kterém by měla být zobrazena vertikální dělicí lišta. Vertikální dělicí lišta odděluje snímek od boční oblasti obsahu.

**Vrací:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Určuje stav, ve kterém by měla být zobrazena vertikální dělicí lišta. Vertikální dělicí lišta odděluje snímek od boční oblasti obsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Určuje stav, ve kterém by měla být zobrazena horizontální dělicí lišta. Horizontální dělicí lišta odděluje snímek od oblasti obsahu pod snímkem.

**Vrací:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Určuje stav, ve kterém by měla být zobrazena horizontální dělicí lišta. Horizontální dělicí lišta odděluje snímek od oblasti obsahu pod snímkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Určuje, zda uživatel upřednostňuje zobrazit jednorázovou oblast obsahu na celou obrazovku místo standardního normálního zobrazení se třemi oblastmi obsahu. Pokud je povoleno, aplikace může zobrazit jednu z oblastí obsahu v celé obrazovce. Čtení/Zápis boolean.

**Vrací:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Určuje, zda uživatel upřednostňuje zobrazit jednorázovou oblast obsahu na celou obrazovku místo standardního normálního zobrazení se třemi oblastmi obsahu. Pokud je povoleno, aplikace může zobrazit jednu z oblastí obsahu v celé obrazovce. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Tento prvek určuje velikost boční oblasti obsahu normálního zobrazení, když je oblast v proměnné obnovené velikosti (ani minimalizovaná, ani maximalizovaná). Pouze ke čtení [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Vrací:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Tento prvek určuje velikost horní oblasti snímku normálního zobrazení, když je oblast v proměnné obnovené velikosti (ani minimalizovaná, ani maximalizovaná). Pouze ke čtení [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Vrací:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)