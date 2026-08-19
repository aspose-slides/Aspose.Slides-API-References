---
title: IMathElementCollection
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een collectie wiskundige elementen MathElement voor.
type: docs
url: /nl/com.aspose.slides/imathelementcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Stelt een verzameling wiskundige elementen (MathElement) voor.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Voegt een wiskundig element toe aan het einde van de collectie. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Bepaalt de index van een specifiek wiskundig element in de collectie. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Voegt een wiskundig element in de collectie in op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Bepaalt of de collectie een specifieke waarde bevat. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Verwijdert de eerste instantie van een specifiek object uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopieer naar opgegeven array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het op te halen item |

**Retourwaarden:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Retourwaarden:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

Voegt een wiskundig element toe aan het einde van de collectie.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | De IMathElement die aan het einde van de collectie moet worden toegevoegd. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

Bepaalt de index van een specifiek wiskundig element in de collectie.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het element dat in de collectie moet worden gezocht. |

**Retourwaarden:**
int - De index van het item als het gevonden wordt in de collectie; anders -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Voegt een wiskundig element in de collectie in op de opgegeven index.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop IMathElement moet worden ingevoegd. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | De IMathElement die moet worden ingevoegd. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de collectie.

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

Bepaalt of de collectie een specifieke waarde bevat.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het object dat in de collectie moet worden gezocht. |

**Retourwaarden:**
boolean - true als het item wordt gevonden in de collectie; anders false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Verwijdert de eerste instantie van een specifiek object uit de collectie.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het object dat uit de collectie moet worden verwijderd. |

**Retourwaarden:**
boolean - true als het item met succes is verwijderd uit de collectie; anders false. Deze methode retourneert ook false als het item niet in de oorspronkelijke collectie wordt gevonden.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het element dat moet worden verwijderd. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Kopieer naar opgegeven array.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array om naar te kopiëren. |
| arrayIndex | int | Index om met kopiëren te beginnen. |