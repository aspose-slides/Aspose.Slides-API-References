---
title: IMathElementCollection
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje kolekcję elementów matematycznych MathElement.
type: docs
url: /pl/com.aspose.slides/imathelementcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Reprezentuje kolekcję elementów matematycznych (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [getCount()](#getCount--) | Pobiera liczbę elementów faktycznie zawartych w kolekcji. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Dodaje element matematyczny na koniec kolekcji. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Określa indeks określonego elementu matematycznego w kolekcji. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Wstawia element matematyczny do kolekcji w podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Określa, czy kolekcja zawiera określoną wartość. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie w kolekcji. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopiuj do określonej tablicy. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


Pobiera element o podanym indeksie. Tylko do odczytu [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
>  ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do pobrania |

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Pobiera liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Zwraca:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


Dodaje element matematyczny na koniec kolekcji.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Element IMathElement, który ma zostać dodany na koniec kolekcji. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


Określa indeks określonego elementu matematycznego w kolekcji.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Element, który ma zostać odnaleziony w kolekcji. |

**Zwraca:**
int - Indeks elementu, jeśli zostanie znaleziony w kolekcji; w przeciwnym razie -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


Wstawia element matematyczny do kolekcji w podanym indeksie.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym należy wstawić IMathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Element IMathElement do wstawienia. |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie elementy z kolekcji.

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


Określa, czy kolekcja zawiera określoną wartość.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Obiekt, który ma zostać odnaleziony w kolekcji. |

**Zwraca:**
boolean - prawda, jeśli element zostanie znaleziony w kolekcji; w przeciwnym razie fałsz.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Obiekt, który ma zostać usunięty z kolekcji. |

**Zwraca:**
boolean - prawda, jeśli element został pomyślnie usunięty z kolekcji; w przeciwnym razie fałsz. Ta metoda również zwraca fałsz, jeśli element nie został znaleziony w oryginalnej kolekcji.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa element o podanym indeksie w kolekcji.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


Kopiuj do określonej tablicy.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Tablica, do której kopiować. |
| arrayIndex | int | Indeks, od którego rozpocząć kopiowanie. |