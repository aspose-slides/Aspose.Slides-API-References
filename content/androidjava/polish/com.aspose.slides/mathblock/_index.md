---
title: MathBlock
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Określa instancję tekstu matematycznego, który znajduje się w MathParagraph i zaczyna się od nowej linii.
type: docs
url: /pl/com.aspose.slides/mathblock/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Określa instancję tekstu matematycznego, który znajduje się w MathParagraph i zaczyna się od nowej linii. Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły są reprezentowane jako blok matematyczny.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathBlock()](#MathBlock--) | Inicjalizuje nową instancję klasy MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Tworzy nowy blok matematyczny i umieszcza w nim określony element. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Tworzy nowy blok matematyczny i umieszcza w nim określone elementy. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę elementów matematycznych podrzędnych faktycznie znajdujących się w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera lub ustawia IMathElement pod podanym indeksem. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Pobiera lub ustawia IMathElement pod podanym indeksem. |
| [isReadOnly()](#isReadOnly--) | Zwraca false, ponieważ kolekcja elementów podrzędnych może być modyfikowana. |
| [getChildren()](#getChildren--) | Pobiera elementy podrzędne |
| [getParent_Immediate()](#getParent-Immediate--) | Zwraca obiekt Parent\_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Dodaje element matematyczny na koniec kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Określa, czy kolekcja zawiera określoną wartość. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopiuje do określonej tablicy. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Javy dla całej kolekcji. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Określa indeks określonego elementu matematycznego w kolekcji. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Wstawia MathElement do kolekcji pod podanym indeksem. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod podanym indeksem w kolekcji. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Łączy element matematyczny z tym blokiem matematycznym |
| [join(String mathText)](#join-java.lang.String-) | Łączy tekst matematyczny z tym blokiem matematycznym |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Łączy inny blok matematyczny z tym |
| [delimit(char separatorCharacter)](#delimit-char-) | Oddziela elementy podrzędne znakiem separatora (bez nawiasów) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne znaki jako ramka |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne jako ramka i oddziela znakiem separatora |
| [toMathArray()](#toMathArray--) | Umieszcza elementy podrzędne w pionowej tablicy |
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
| Parametr | Typ | Opis |
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementy matematyczne do umieszczenia w bloku |

### getCount() {#getCount--}
```
public final int getCount()
```

Zwraca liczbę elementów matematycznych podrzędnych faktycznie znajdujących się w kolekcji. Tylko do odczytu int.

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

Pobiera lub ustawia IMathElement pod podanym indeksem.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu |
**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement) - Element matematyczny
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Pobiera lub ustawia IMathElement pod podanym indeksem.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Element matematyczny. |
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Zwraca false, ponieważ kolekcja elementów podrzędnych może być modyfikowana.

**Zwraca:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobiera elementy podrzędne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent\_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Dodaje element matematyczny na koniec kolekcji.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Element IMathElement, który ma zostać dodany na koniec kolekcji. |
### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie elementy z kolekcji.

--------------------

> ```
> Example:
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
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Obiekt do wyszukania w kolekcji. |
**Zwraca:**
boolean - prawda, jeśli element został znaleziony w kolekcji; w przeciwnym razie false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Kopiuje do określonej tablicy.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Tablica do skopiowania. |
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Obiekt do usunięcia z kolekcji. |
**Zwraca:**
boolean - prawda, jeśli element został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Ta metoda również zwraca false, jeśli element nie został znaleziony w oryginalnej kolekcji.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - IGenericEnumerator, który można użyć do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Zwraca iterator Javy dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.IEnumerator - java.util.Iterator dla całej kolekcji.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Określa indeks określonego elementu matematycznego w kolekcji.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Element do wyszukania w kolekcji. |
**Zwraca:**
int - Indeks elementu, jeśli został znaleziony w kolekcji; w przeciwnym razie -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Wstawia MathElement do kolekcji pod podanym indeksem.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym MathElement powinien zostać wstawiony. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement do wstawienia. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element pod podanym indeksem w kolekcji.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Łączy element matematyczny z tym blokiem matematycznym

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Parametry:**
| Parametr | Typ | Opis |
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
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | java.lang.String | Tekst matematyczny do połączenia |
**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - Nowy IMathBlock zawierający tę instancję i określony argument
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Łączy inny blok matematyczny z tym

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Łączony blok |
**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - ten blok matematyczny po połączeniu
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Oddziela elementy podrzędne znakiem separatora (bez nawiasów)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char | Znak separatora |
**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne znaki jako ramka

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char | Znak końcowy (zwykle prawy nawias) |
**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zawierający określone znaki jako ramkę
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne jako ramka i oddziela znakiem separatora

--------------------

> ```
> Przykład:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parametry:**
| Parametr | Typ | Opis |
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

Umieszcza elementy podrzędne w pionowej tablicy

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Docelowy strumień |