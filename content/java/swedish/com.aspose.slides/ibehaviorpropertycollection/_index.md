---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar tidsinställningar för effektbeteendet.
type: docs
url: /sv/com.aspose.slides/ibehaviorpropertycollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Representerar tidsinställningar för effektbeteendet.
## Metoder

| Method | Description |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Lägger till en ny egenskap i samlingen. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Bestämmer indexet för ett specifikt objekt efter egenskapsvärde i listan. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Infogar en ny egenskap (med det angivna egenskapsvärdet) i samlingen på angivet index. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Tar bort angiven egenskap från samlingen. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Lägger till en ny egenskap i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | Värde på egenskapen att lägga till. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Bestämmer indexet för ett specifikt objekt efter egenskapsvärde i listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | värde på egenskapen |

**Returnerar:**
int - Index för egenskapen med angivet värde
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Infogar en ny egenskap (med det angivna egenskapsvärdet) i samlingen på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index där en ny egenskap ska infogas. |
| propertyValue | java.lang.String | Värde på egenskapen att lägga till. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Tar bort angiven egenskap från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | Värde på egenskapen att ta bort. |

**Returnerar:**
boolean - Sant om en egenskap togs bort framgångsrikt boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | Värde på egenskapen att hitta i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - sant om propertyValue hittas i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars falskt.