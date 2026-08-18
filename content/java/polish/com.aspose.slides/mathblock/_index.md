---
title: MathBlock
second_title: Aspose.Slides dla Java - odniesienie API
description: Określa instancję tekstu matematycznego, który znajduje się w MathParagraph i rozpoczyna się od nowej linii.
type: docs
url: /pl/com.aspose.slides/mathblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Określa instancję tekstu matematycznego, który znajduje się w MathParagraph i zaczyna się od nowej linii. Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły są reprezentowane przez blok matematyczny.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Constructors

| Konstruktor | Opis |
| --- | --- |
| [MathBlock()](#MathBlock--) | Inicjalizuje nową instancję klasy MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Tworzy nowy blok matematyczny i umieszcza w nim określony element. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Tworzy nowy blok matematyczny i umieszcza w nim określone elementy. |
## Methods

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Pobiera liczbę elementów matematycznych dziecka faktycznie zawartych w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera lub ustawia IMathElement pod określonym indeksem. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Pobiera lub ustawia IMathElement pod określonym indeksem. |
| [isReadOnly()](#isReadOnly--) | Zwraca false, ponieważ kolekcja elementów dziecka może być modyfikowana. |
| [getChildren()](#getChildren--) | Pobiera elementy dziecka |
| [getParent_Immediate()](#getParent-Immediate--) | Zwraca obiekt Parent\_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Dodaje element matematyczny na koniec kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Określa, czy kolekcja zawiera określoną wartość. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopiuje do określonej tablicy. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje przez kolekcję. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Określa indeks określonego elementu matematycznego w kolekcji. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Wstawia MathElement do kolekcji pod określonym indeksem. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem w kolekcji. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Łączy element matematyczny z tym blokiem matematycznym |
| [join(String mathText)](#join-java.lang.String-) | Łączy tekst matematyczny z tym blokiem matematycznym |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Łączy inny blok matematyczny z tym |
| [delimit(char separatorCharacter)](#delimit-char-) | Ogranicza elementy dziecka znakiem separatora (bez nawiasów) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Otacza elementy dziecka tego bloku określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Otacza elementy dziecka tego bloku określonymi znakami, takimi jak nawiasy lub innymi jako ramka i ogranicza znakiem separatora |
| [toMathArray()](#toMathArray--) | Umieszcza elementy dziecka w pionowej tablicy |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Zapisuje zawartość tego [MathBlock](../../com.aspose.slides/mathblock) jako MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Inicjalizuje nową instancję klasy MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```


### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

Tworzy nowy blok matematyczny i umieszcza w nim określony element.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Element matematyczny do umieszczenia w bloku |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Tworzy nowy blok matematyczny i umieszcza w nim określone elementy.

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementy matematyczne do umieszczenia w bloku |

### getCount() {#getCount--}
```
public final int getCount()
```

Pobiera liczbę elementów matematycznych dziecka faktycznie zawartych w kolekcji. **Tylko do odczytu** int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```


**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Pobiera lub ustawia IMathElement pod określonym indeksem.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| index | int | Indeks zero-bazowy elementu |

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement) - Element matematyczny.

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Pobiera lub ustawia IMathElement pod określonym indeksem.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| index | int | Indeks zero-bazowy elementu |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Element matematyczny. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Zwraca false, ponieważ kolekcja elementów dziecka może być modyfikowana.

**Zwraca:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobiera elementy dziecka

**Zwraca:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent\_Immediate. **Tylko do odczytu** IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Dodaje element matematyczny na koniec kolekcji.

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement do dodania na koniec kolekcji. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie elementy z kolekcji.

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Określa, czy kolekcja zawiera określoną wartość.

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Obiekt do znalezienia w kolekcji. |

**Zwraca:**
boolean - true, jeśli element został znaleziony w kolekcji; w przeciwnym razie false.

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Kopiuje do określonej tablicy.

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Tablica, do której kopiować. |
| arrayIndex | int | Indeks, od którego rozpocząć kopiowanie. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Obiekt do usunięcia z kolekcji. |

**Zwraca:**
boolean - true, jeśli element został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Metoda również zwraca false, jeśli element nie został odnaleziony w oryginalnej kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Zwraca enumerator, który iteruje przez kolekcję.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - IGenericEnumerator, który może być użyty do iteracji przez kolekcję.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.IEnumerator - java.util.Iterator dla całej kolekcji.

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Określa indeks określonego elementu matematycznego w kolekcji.

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Element do odnalezienia w kolekcji. |

**Zwraca:**
int - Indeks elementu, jeśli został znaleziony w kolekcji; w przeciwnym razie -1.

### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Wstawia MathElement do kolekcji pod określonym indeksem.

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| index | int | Indeks zero-bazowy, pod którym należy wstawić MathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement do wstawienia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element pod określonym indeksem w kolekcji.

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| index | int | Indeks zero-bazowy elementu do usunięcia. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Łączy element matematyczny z tym blokiem matematycznym

--------------------

> ```
> Przykład:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Element do połączenia |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - Bieżąca instancja IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Łączy tekst matematyczny z tym blokiem matematycznym

--------------------

> ```
> Przykład:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| mathText | java.lang.String | Tekst matematyczny do połączenia |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - Nowy IMathBlock zawierający tę instancję i podany argument

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Łączy inny blok matematyczny z tym

--------------------

> ```
> Przykład:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Blok do połączenia |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ten blok matematyczny po połączeniu

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Ogranicza elementy dziecka znakiem separatora (bez nawiasów)

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| separatorCharacter | char | Znak separatora |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter)

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Otacza elementy dziecka tego bloku określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka

--------------------

> ```
> Przykład:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| beginningCharacter | char | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char | Znak końcowy (zwykle prawy nawias) |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zawierający określone znaki jako ramkę

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Otacza elementy dziecka tego bloku określonymi znakami, takimi jak nawiasy lub innymi jako ramka i ogranicza znakiem separatora

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| beginningCharacter | char | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char | Znak końcowy (zwykle prawy nawias) |
| separatorCharacter | char | Znak separatora |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zawierający określone znaki jako ramkę i separator

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Umieszcza elementy dziecka w pionowej tablicy

--------------------

> ```
> Przykład:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Zwraca:**
[IMathArray](../../com.aspose.slides/imatharray) - Nowa instancja typu [IMathArray](../../com.aspose.slides/imatharray)

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Zapisuje zawartość tego [MathBlock](../../com.aspose.slides/mathblock) jako MathML

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |