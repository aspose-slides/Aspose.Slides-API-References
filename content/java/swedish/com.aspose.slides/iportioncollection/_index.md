---
title: IPortionCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av portioner.
type: docs
url: /sv/com.aspose.slides/iportioncollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Representerar en samling av portioner.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Lägger till en Portion i slutet av samlingen. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Bestämmer indexet för en specifik portion i samlingen. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Infogar en Portion i samlingen på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Lägger till en Portion i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionen som ska läggas till i slutet av samlingen. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Bestämmer indexet för en specifik portion i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Portionen som ska lokaliseras i samlingen. |

**Returnerar:**
int - Indexet för item om det hittas i samlingen; annars -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Infogar en Portion i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Portion ska infogas. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionen som ska infogas. |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objektet som ska lokaliseras i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om item hittas i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objektet som ska tas bort från [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om item framgångsrikt togs bort från [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false. Denna metod returnerar också false om item inte finns i den ursprungliga [IGenericCollection](../../com.aspose.slides/igenericcollection).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |