---
title: IGradientStopCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling gradient stops voor.
type: docs
url: /nl/com.aspose.slides/igradientstopcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Stelt een verzameling gradient stops voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de gradient stop op basis van de index. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een gradient stop op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle gradient stops uit een collectie. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Retourneert de gradient stop op basis van de index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | float | Positie van de nieuwe gradient stop. |
| color | java.lang.Integer | Kleur van de nieuwe gradient stop. |

**Retourneert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index van de nieuwe gradient stop in de collectie.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | float | Positie van de nieuwe gradient stop. |
| presetColor | int | Kleur van de nieuwe gradient stop. |

**Retourneert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index van de nieuwe gradient stop in de collectie.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | float | Positie van de nieuwe gradient stop. |
| schemeColor | int | Kleur van de nieuwe gradient stop. |

**Retourneert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index van de nieuwe gradient stop in de collectie.

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index in de collectie waar de nieuwe gradient stop wordt ingevoegd. |
| position | float | Positie van de nieuwe gradient stop. |
| color | java.lang.Integer | Kleur van de nieuwe gradient stop. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index in de collectie waar de nieuwe gradient stop wordt ingevoegd. |
| position | float | Positie van de nieuwe gradient stop. |
| presetColor | int | Kleur van de nieuwe gradient stop. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index in de collectie waar de nieuwe gradient stop wordt ingevoegd. |
| position | float | Positie van de nieuwe gradient stop. |
| schemeColor | int | Kleur van de nieuwe gradient stop. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert een gradient stop op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gradient stop die verwijderd moet worden. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle gradient stops uit een collectie.