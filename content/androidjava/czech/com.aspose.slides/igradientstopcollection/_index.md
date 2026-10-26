---
title: IGradientStopCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci gradientových zastávek.
type: docs
url: /cs/com.aspose.slides/igradientstopcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Reprezentuje kolekci gradientových zastávek.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací gradientovou zastávku podle indexu. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní gradientovou zastávku na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny gradientové zastávky z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Vrací gradientovou zastávku podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | float | Pozice nové gradientové zastávky. |
| color | java.lang.Integer | Barva nové gradientové zastávky. |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index nové gradientové zastávky v kolekci.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | float | Pozice nové gradientové zastávky. |
| presetColor | int | Barva nové gradientové zastávky. |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index nové gradientové zastávky v kolekci.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | float | Pozice nové gradientové zastávky. |
| schemeColor | int | Barva nové gradientové zastávky. |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index nové gradientové zastávky v kolekci.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kam bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| color | java.lang.Integer | Barva nové gradientové zastávky. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kam bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| presetColor | int | Barva nové gradientové zastávky. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kam bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| schemeColor | int | Barva nové gradientové zastávky. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní gradientovou zastávku na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index gradientové zastávky, která má být smazána. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny gradientové zastávky z kolekce.