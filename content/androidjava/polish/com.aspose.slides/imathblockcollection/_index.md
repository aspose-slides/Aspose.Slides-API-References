---
title: IMathBlockCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie do interfejsu API Java
description: Kolekcja bloków matematycznych IMathBlock
type: docs
url: /pl/com.aspose.slides/imathblockcollection/
---
**Wszystkie implementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Kolekcja bloków matematycznych (IMathBlock)

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Dodaje IMathBlock do końca kolekcji. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Wstawia IMathBlock do kolekcji w określonym indeksie. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod wskazanym indeksem w kolekcji. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Określa, czy kolekcja zawiera określoną wartość. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Określa indeks konkretnego IMathBlock w kolekcji. |
| [getCount()](#getCount--) | Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element pod wskazanym indeksem. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Zwraca element pod wskazanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Dodaje IMathBlock do końca kolekcji.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Blok matematyczny, który zostanie dodany na koniec kolekcji |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Wstawia IMathBlock do kolekcji w określonym indeksie.

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym ma zostać wstawiony element. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock do wstawienia. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Obiekt do usunięcia z kolekcji. |

**Zwraca:**
boolean - true, jeśli element został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Metoda także zwraca false, jeśli element nie został znaleziony w pierwotnej kolekcji.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element pod wskazanym indeksem w kolekcji.

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu, który ma zostać usunięty. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Określa, czy kolekcja zawiera określoną wartość.

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Obiekt, który ma zostać odnaleziony w kolekcji. |

**Zwraca:**
boolean - true, jeśli element został znaleziony w kolekcji; w przeciwnym razie false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Określa indeks konkretnego IMathBlock w kolekcji.

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Element, który ma zostać odnaleziony w kolekcji. |

**Zwraca:**
int - Indeks elementu, jeśli został znaleziony w kolekcji; w przeciwnym razie -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu int.

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Zwraca element pod wskazanym indeksem. Tylko do odczytu [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu, który ma zostać pobrany. |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - Blok tekstu matematycznego.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Zwraca element pod wskazanym indeksem. Tylko do odczytu [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu, który ma zostać ustawiony. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Blok tekstu matematycznego. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie elementy z kolekcji.

--------------------

> ```
> Przykład:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```