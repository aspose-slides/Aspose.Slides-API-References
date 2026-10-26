---
title: IGradientStopCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av gradientstopp.
type: docs
url: /sv/com.aspose.slides/igradientstopcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Representerar en samling av gradientstopp.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar gradientstoppen med index. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Skapar en ny gradientstop och lägger till den i slutet av samlingen. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Skapar en ny gradientstop och lägger till den i slutet av samlingen. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Skapar en ny gradientstop och lägger till den i slutet av samlingen. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Skapar en ny gradientstop och inför den på det angivna indexet i samlingen. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Skapar en ny gradientstop och inför den på det angivna indexet i samlingen. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Skapar en ny gradientstop och inför den på det angivna indexet i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en gradientstop på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla gradientstopp från en samling. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Returnerar gradientstoppen med index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Skapar en ny gradientstop och lägger till den i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för den nya gradientstoppen. |
| color | java.lang.Integer | Färg för den nya gradientstoppen. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index för den nya gradientstoppen i samlingen.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Skapar en ny gradientstop och lägger till den i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för den nya gradientstoppen. |
| presetColor | int | Färg för den nya gradientstoppen. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index för den nya gradientstoppen i samlingen.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Skapar en ny gradientstop och lägger till den i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för den nya gradientstoppen. |
| schemeColor | int | Färg för den nya gradientstoppen. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index för den nya gradientstoppen i samlingen.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Skapar en ny gradientstop och inför den på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där den nya gradientstoppen ska införas. |
| position | float | Position för den nya gradientstoppen. |
| color | java.lang.Integer | Färg för den nya gradientstoppen. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Skapar en ny gradientstop och inför den på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där den nya gradientstoppen ska införas. |
| position | float | Position för den nya gradientstoppen. |
| presetColor | int | Färg för den nya gradientstoppen. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Skapar en ny gradientstop och inför den på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där den nya gradientstoppen ska införas. |
| position | float | Position för den nya gradientstoppen. |
| schemeColor | int | Färg för den nya gradientstoppen. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort en gradientstop på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en gradientstop som ska raderas. |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla gradientstopp från en samling.