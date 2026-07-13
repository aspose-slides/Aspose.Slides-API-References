---
title: IMathElementCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av matematiska element MathElement.
type: docs
url: /sv/com.aspose.slides/imathelementcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Representerar en samling av matematiska element (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Lägger till ett matematiskt element i slutet av samlingen. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Bestämmer indexet för ett specifikt matematiskt element i samlingen. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Infogar ett matematiskt element i samlingen på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopierar till specificerad array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


Hämtar elementet på det angivna indexet. Skrivskyddad [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för objektet som ska hämtas. |

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Returnerar:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


Lägger till ett matematiskt element i slutet av samlingen.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement som ska läggas till i slutet av samlingen. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


Bestämmer indexet för ett specifikt matematiskt element i samlingen.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Elementet som ska sökas i samlingen. |

**Returnerar:**
int - Indexet för objektet om det hittas i samlingen; annars -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


Infogar ett matematiskt element i samlingen på det angivna indexet.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där IMathElement ska infogas. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement att infoga. |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla element från samlingen.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```


Bestämmer om samlingen innehåller ett specifikt värde.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objektet som ska sökas i samlingen. |

**Returnerar:**
boolean - true om objektet finns i samlingen; annars false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


Tar bort den första förekomsten av ett specifikt objekt från samlingen.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objektet som ska tas bort från samlingen. |

**Returnerar:**
boolean - true om objektet lyckades tas bort från samlingen; annars false. Den här metoden returnerar också false om objektet inte finns i den ursprungliga samlingen.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort elementet på det angivna indexet i samlingen.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


Kopiera till specificerad array.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array att kopiera till. |
| arrayIndex | int | Index att börja kopiera från. |