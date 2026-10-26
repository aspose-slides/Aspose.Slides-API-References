---
title: MathArray
second_title: Aspose.Slides dla Java – Odniesienie API
description: Określa pionową tablicę równań lub dowolnych obiektów matematycznych
type: docs
url: /pl/com.aspose.slides/matharray/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Określa pionową tablicę równań lub dowolnych obiektów matematycznych

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Tworzy tablicę matematyczną i umieszcza w niej określony element |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Tworzy tablicę matematyczną i umieszcza w niej określone elementy |
## Metody

| Metoda | Opis |
| --- | --- |
| [getArguments()](#getArguments--) | Zestaw elementów tablicy |
| [getBaseJustification()](#getBaseJustification--) | Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maksymalna dystrybucja. Gdy wartość jest true, tablica jest rozmieszczona na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maksymalna dystrybucja. Gdy wartość jest true, tablica jest rozmieszczona na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.). |
| [getObjectDistribution()](#getObjectDistribution--) | Dystrybucja obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczona na maksymalną szerokość obiektu tablicy. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Dystrybucja obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczona na maksymalną szerokość obiektu tablicy. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typ pionowego odstępu między elementami tablicy. Domyślnie: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typ pionowego odstępu między elementami tablicy. Domyślnie: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Odstęp między wierszami tablicy. Używany tylko wtedy, gdy RowSpacingRule jest ustawiony na 3. Exact w tym przypadku jednostka miary to punkty lub Multiple w tym przypadku jednostka miary to pół-linii. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Odstęp między wierszami tablicy. Używany tylko wtedy, gdy RowSpacingRule jest ustawiony na 3. Exact w tym przypadku jednostka miary to punkty lub Multiple w tym przypadku jednostka miary to pół-linii. |
| [getChildren()](#getChildren--) | Pobiera elementy podrzędne |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


Tworzy tablicę matematyczną i umieszcza w niej określony element

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Element do umieszczenia w tablicy |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


Tworzy tablicę matematyczną i umieszcza w niej określone elementy

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementy do umieszczenia w tablicy |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Zestaw elementów tablicy

--------------------

> ```
> Example:
>  
>  IMMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Zwraca:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Domyślna wartość: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Zwraca:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Domyślna wartość: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```


Maksymalna dystrybucja. Gdy wartość jest true, tablica jest rozmieszczona na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Zwraca:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```


Maksymalna dystrybucja. Gdy wartość jest true, tablica jest rozmieszczona na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```


Dystrybucja obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczona na maksymalną szerokość obiektu tablicy.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Zwraca:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```


Dystrybucja obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczona na maksymalną szerokość obiektu tablicy.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```


Typ pionowego odstępu między elementami tablicy. Domyślnie: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Zwraca:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```


Typ pionowego odstępu między elementami tablicy. Domyślnie: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```


Odstęp między wierszami tablicy. Używany tylko wtedy, gdy RowSpacingRule jest ustawiony na 3. Exact w tym przypadku jednostka miary to punkty lub Multiple w tym przypadku jednostka miary to pół-linii. Domyślnie: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Zwraca:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```


Odstęp między wierszami tablicy. Używany tylko wtedy, gdy RowSpacingRule jest ustawiony na 3. Exact w tym przypadku jednostka miary to punkty lub Multiple w tym przypadku jednostka miary to pół-linii. Domyślnie: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobiera elementy podrzędne

**Zwraca:**
com.aspose.slides.IMathElement[]