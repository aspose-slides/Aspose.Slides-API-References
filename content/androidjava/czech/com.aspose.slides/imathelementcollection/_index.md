---
title: IMathElementCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje kolekci matematických prvků MathElement.
type: docs
url: /cs/com.aspose.slides/imathelementcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Reprezentuje kolekci matematických prvků (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getCount()](#getCount--) | Získá počet prvků skutečně obsažených v kolekci. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Přidá matematický prvek na konec kolekce. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Určuje index konkrétního matematického prvku v kolekci. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Vloží matematický prvek do kolekce na určeném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Určuje, zda kolekce obsahuje konkrétní hodnotu. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na určeném indexu v kolekci. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Zkopíruje do určeného pole. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


Získá prvek na zadaném indexu. Pouze pro čtení [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index položky (číslo od nuly), který se má získat. |

**Návratová hodnota:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Návratová hodnota:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


Přidá matematický prvek na konec kolekce.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement, který se má přidat na konec kolekce. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


Určuje index konkrétního matematického prvku v kolekci.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Prvek, který se má v kolekci vyhledat. |

**Návratová hodnota:**
int - Index položky, pokud je v kolekci nalezena; jinak -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


Vloží matematický prvek do kolekce na určeném indexu.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index (číslo od nuly), na který má být IMathElement vložen. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement, který se má vložit. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny prvky z kolekce.

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


Určuje, zda kolekce obsahuje konkrétní hodnotu.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objekt, který se má v kolekci vyhledat. |

**Návratová hodnota:**
boolean - true, pokud je položka v kolekci nalezena; jinak false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


Odstraní první výskyt konkrétního objektu z kolekce.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objekt, který se má z kolekce odstranit. |

**Návratová hodnota:**
boolean - true, pokud byl prvek úspěšně odstraněn z kolekce; jinak false. Tato metoda také vrací false, pokud prvek není v původní kolekci nalezen.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní prvek na určeném indexu v kolekci.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index (číslo od nuly) prvku, který se má odstranit. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


Zkopíruje do určeného pole.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Pole, do nějž se má kopírovat. |
| arrayIndex | int | Index, od kterého se má kopírování zahájit. |