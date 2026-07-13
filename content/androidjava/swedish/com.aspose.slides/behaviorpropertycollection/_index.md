---
title: BehaviorPropertyCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar tidsinställningsegenskaper för effektbeteendet.
type: docs
url: /sv/com.aspose.slides/behaviorpropertycollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Representerar tidsinställningsegenskaper för effektbeteendet.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet egenskaper som lagras i samlingen. |
| [isReadOnly()](#isReadOnly--) | Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Lägger till en ny egenskap i samlingen. |
| [add(String propertyValue)](#add-java.lang.String-) | Lägger till en ny egenskap i samlingen. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Bestämmer index för ett specifikt objekt i Listan. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Bestämmer index för ett specifikt objekt efter egenskapsvärde i Listan. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Infogar en ny egenskap i samlingen på det angivna indexet. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Infogar en ny egenskap (med specificerat egenskapsvärde) i samlingen på det angivna indexet. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med start vid ett specifikt Array-index. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Tar bort angiven egenskap från samlingen. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Tar bort angiven egenskap från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort egenskap vid angivet index. |
| [clear()](#clear--) | Tar bort alla egenskaper från samlingen. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en egenskap vid angivet index. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Sätter en egenskap vid angivet index. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### size() {#size--}
```
public final int size()
```

Returnerar antalet egenskaper som lagras i samlingen. Skrivskyddad int.

**Returnerar:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. Skrivskyddad boolean.

**Returnerar:**
boolean - true om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad; annars false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Lägger till en ny egenskap i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Egenskap att lägga till. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Lägger till en ny egenskap i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | Värde på egenskapen som ska läggas till. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Bestämmer index för ett specifikt objekt i Listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Objektet att leta efter i Listan. |

**Returnerar:**
int - Index för objektet om det hittas i listan; annars -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Bestämmer index för ett specifikt objekt efter egenskapsvärde i Listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | värde på egenskapen |

**Returnerar:**
int - Index för egenskapen med det angivna värdet
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Infogar en ny egenskap i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index där en ny egenskap ska infogas. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Egenskap att lägga till. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Infogar en ny egenskap (med specificerat egenskapsvärde) i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index där en ny egenskap ska infogas. |
| propertyValue | java.lang.String | Värde på egenskapen som ska läggas till. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med start vid ett specifikt Array-index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Den endimensionella Array som är mål för elementen som kopierats från [IGenericCollection](../../com.aspose.slides/igenericcollection). Arrayen måste ha nollbaserad indexering. |
| arrayIndex | int | Det nollbaserade indexet i arrayen där kopieringen börjar. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Tar bort angiven egenskap från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Egenskap att ta bort. |

**Returnerar:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Tar bort angiven egenskap från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | Värde på egenskapen som ska tas bort. |

**Returnerar:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort egenskap vid angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den egenskap som ska tas bort. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla egenskaper från samlingen.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Egenskapen att leta efter i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om item finns i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | Värde på egenskapen att leta efter i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om propertyValue finns i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Returnerar en egenskap vid angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en egenskap att returnera. |

**Returnerar:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animationsbeteendeegenskap.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Sätter en egenskap vid angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en egenskap att returnera. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Returnerar:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Returnerar:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Returnerar:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - En java.util.Iterator för hela samlingen.