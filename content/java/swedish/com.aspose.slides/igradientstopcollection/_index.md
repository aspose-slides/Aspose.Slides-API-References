---
title: IGradientStopCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling gradientstopp.
type: docs
url: /sv/com.aspose.slides/igradientstopcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Representerar en samling av gradientstopp.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar gradientstoppet vid index. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Skapar en ny gradientstopp och lägger till den i slutet av samlingen. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Skapar en ny gradientstopp och lägger till den i slutet av samlingen. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Skapar en ny gradientstopp och lägger till den i slutet av samlingen. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Skapar en ny gradientstopp och infogar den på angivet index i samlingen. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Skapar en ny gradientstopp och infogar den på angivet index i samlingen. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Skapar en ny gradientstopp och infogar den på angivet index i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en gradientstopp på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla gradientstopp från en samling. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Returnerar gradientstoppet vid index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```


Skapar en ny gradientstopp och lägger till den i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för den nya gradientstoppet. |
| color | java.awt.Color | Färg för den nya gradientstoppet. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) – Index för den nya gradientstoppet i samlingen.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Skapar en ny gradientstopp och lägger till den i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för den nya gradientstoppet. |
| presetColor | int | Färg för den nya gradientstoppet. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) – Index för den nya gradientstoppet i samlingen.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Skapar en ny gradientstopp och lägger till den i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för den nya gradientstoppet. |
| schemeColor | int | Färg för den nya gradientstoppet. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) – Index för den nya gradientstoppet i samlingen.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```


Skapar en ny gradientstopp och infogar den på angivet index i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där den nya gradientstoppet ska infogas. |
| position | float | Position för den nya gradientstoppet. |
| color | java.awt.Color | Färg för den nya gradientstoppet. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Skapar en ny gradientstopp och infogar den på angivet index i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där den nya gradientstoppet ska infogas. |
| position | float | Position för den nya gradientstoppet. |
| presetColor | int | Färg för den nya gradientstoppet. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Skapar en ny gradientstopp och infogar den på angivet index i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där den nya gradientstoppet ska infogas. |
| position | float | Position för den nya gradientstoppet. |
| schemeColor | int | Färg för den nya gradientstoppet. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort en gradientstopp på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en gradientstopp som ska tas bort. |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla gradientstopp från en samling.