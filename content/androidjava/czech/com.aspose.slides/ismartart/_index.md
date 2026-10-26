---
title: ISmartArt
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje diagram SmartArt.
type: docs
url: /cs/com.aspose.slides/ismartart/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Reprezentuje diagram SmartArt.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Vrací kolekce všech uzlů v objektu SmartArt. |
| [getNodes()](#getNodes--) | Vrací kolekce kořenových uzlů v objektu SmartArt. |
| [getLayout()](#getLayout--) | Vrátí nebo nastaví rozvržení objektu SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Vrátí nebo nastaví rozvržení objektu SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Vrátí nebo nastaví rychlý styl objektu SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Vrátí nebo nastaví rychlý styl objektu SmartArt. |
| [getColorStyle()](#getColorStyle--) | Vrátí nebo nastaví barevný styl objektu SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Vrátí nebo nastaví barevný styl objektu SmartArt. |
| [isReversed()](#isReversed--) | Vrátí nebo nastaví stav diagramu SmartArt vzhledem k (zleva doprava) LTR nebo (zprava doleva) RTL, pokud diagram podporuje obrácení. |
| [setReversed(boolean value)](#setReversed-boolean-) | Vrátí nebo nastaví stav diagramu SmartArt vzhledem k (zleva doprava) LTR nebo (zprava doleva) RTL, pokud diagram podporuje obrácení. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Vrací kolekce všech uzlů v objektu SmartArt. Pouze ke čtení [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Vrací:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Vrací kolekce kořenových uzlů v objektu SmartArt. Pouze ke čtení [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Vrací:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Vrátí nebo nastaví rozvržení objektu SmartArt. Čtení/zápis [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Vrací:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Vrátí nebo nastaví rozvržení objektu SmartArt. Čtení/zápis [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Vrátí nebo nastaví rychlý styl objektu SmartArt. Čtení/zápis [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Vrací:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Vrátí nebo nastaví rychlý styl objektu SmartArt. Čtení/zápis [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Vrátí nebo nastaví barevný styl objektu SmartArt. Čtení/zápis [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Vrací:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Vrátí nebo nastaví barevný styl objektu SmartArt. Čtení/zápis [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Vrátí nebo nastaví stav diagramu SmartArt vzhledem k (zleva doprava) LTR nebo (zprava doleva) RTL, pokud diagram podporuje obrácení. Čtení/zápis boolean.

**Vrací:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Vrátí nebo nastaví stav diagramu SmartArt vzhledem k (zleva doprava) LTR nebo (zprava doleva) RTL, pokud diagram podporuje obrácení. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |