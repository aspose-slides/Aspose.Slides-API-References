---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /cs/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Reprezentuje vlastnosti normálního zobrazení. Normální zobrazení se skládá ze tří oblastí obsahu: samotného snímku, boční oblasti obsahu a spodní oblasti obsahu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obrysu obsahu v některé z oblastí obsahu režimu normálního zobrazení. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obrysu obsahu v některé z oblastí obsahu režimu normálního zobrazení. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Určuje, zda by svislý dělič měl při dostatečně malé boční oblasti přejít do minimalizovaného stavu. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Určuje, zda by svislý dělič měl při dostatečně malé boční oblasti přejít do minimalizovaného stavu. |
| [getVerticalBarState()](#getVerticalBarState--) | Určuje stav, ve kterém by měl být zobrazen svislý dělič. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Určuje stav, ve kterém by měl být zobrazen svislý dělič. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Určuje stav, ve kterém by měl být zobrazen vodorovný dělič. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Určuje stav, ve kterém by měl být zobrazen vodorovný dělič. |
| [getPreferSingleView()](#getPreferSingleView--) | Určuje, zda uživatel preferuje zobrazení jedné oblasti obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Určuje, zda uživatel preferuje zobrazení jedné oblasti obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. |
| [getRestoredLeft()](#getRestoredLeft--) | Tento prvek určuje velikost boční oblasti obsahu normálního zobrazení, když má oblast proměnnou obnovovanou velikost (není ani minimalizována, ani maximalizována). |
| [getRestoredTop()](#getRestoredTop--) | Tento prvek určuje velikost horní oblasti snímku normálního zobrazení, když má oblast proměnnou obnovovanou velikost (není ani minimalizována, ani maximalizována). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```


Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obrysu obsahu v některé z oblastí obsahu režimu normálního zobrazení. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```


Určuje, zda by aplikace měla zobrazovat ikony při zobrazování obrysu obsahu v některé z oblastí obsahu režimu normálního zobrazení. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```


Určuje, zda by svislý dělič měl při dostatečně malé boční oblasti přejít do minimalizovaného stavu. Čtení/zápis boolean.

**Vrací:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```


Určuje, zda by svislý dělič měl při dostatečně malé boční oblasti přejít do minimalizovaného stavu. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```


Určuje stav, ve kterém by měl být zobrazen svislý dělič. Svislý dělič odděluje snímek od boční oblasti obsahu.

**Vrací:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```


Určuje stav, ve kterém by měl být zobrazen svislý dělič. Svislý dělič odděluje snímek od boční oblasti obsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```


Určuje stav, ve kterém by měl být zobrazen vodorovný dělič. Vodorovný dělič odděluje snímek od oblasti obsahu pod snímkem.

**Vrací:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```


Určuje stav, ve kterém by měl být zobrazen vodorovný dělič. Vodorovný dělič odděluje snímek od oblasti obsahu pod snímkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```


Určuje, zda uživatel preferuje zobrazení jedné oblasti obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. Pokud je povoleno, aplikace může zobrazit jednu z oblastí obsahu v celé obrazovce. Čtení/zápis boolean.

**Vrací:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```


Určuje, zda uživatel preferuje zobrazení jedné oblasti obsahu na celé obrazovce místo standardního normálního zobrazení se třemi oblastmi obsahu. Pokud je povoleno, aplikace může zobrazit jednu z oblastí obsahu v celé obrazovce. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```


Tento prvek určuje velikost boční oblasti obsahu normálního zobrazení, když má oblast proměnnou obnovovanou velikost (není ani minimalizována, ani maximalizována). Pouze pro čtení [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Vrací:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```


Tento prvek určuje velikost horní oblasti snímku normálního zobrazení, když má oblast proměnnou obnovovanou velikost (není ani minimalizována, ani maximalizována). Pouze pro čtení [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Vrací:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)