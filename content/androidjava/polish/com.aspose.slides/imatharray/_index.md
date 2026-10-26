---
title: IMathArray
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Określa pionową tablicę równań lub dowolnych obiektów matematycznych
type: docs
url: /pl/com.aspose.slides/imatharray/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Określa pionową tablicę równań lub dowolnych obiektów matematycznych

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getArguments()](#getArguments--) | Zestaw elementów tablicy |
| [getBaseJustification()](#getBaseJustification--) | Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution Gdy true, tablica jest rozmieszczana do maksymalnej szerokości elementu zawierającego (strona, kolumna, komórka itp.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution Gdy true, tablica jest rozmieszczana do maksymalnej szerokości elementu zawierającego (strona, kolumna, komórka itp.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution Gdy true, zawartość tablicy jest rozmieszczana do maksymalnej szerokości obiektu tablicy. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution Gdy true, zawartość tablicy jest rozmieszczana do maksymalnej szerokości obiektu tablicy. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typ pionowego odstępu między elementami tablicy |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typ pionowego odstępu między elementami tablicy |
| [getRowSpacing()](#getRowSpacing--) | Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule jest ustawiony na 3. W tym przypadku jednostką jest punkt lub przy Multiple jednostką jest półlina. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule jest ustawiony na 3. W tym przypadku jednostką jest punkt lub przy Multiple jednostką jest półlina. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Zestaw elementów tablicy

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Zwraca:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
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
public abstract void setBaseJustification(int value)
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
public abstract boolean getMaximumDistribution()
```

Maximum Distribution Gdy true, tablica jest rozmieszczana do maksymalnej szerokości elementu zawierającego (strona, kolumna, komórka itp.).

--------------------

> ```
> Przykład:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Zwraca:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maximum Distribution Gdy true, tablica jest rozmieszczana do maksymalnej szerokości elementu zawierającego (strona, kolumna, komórka itp.).

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
public abstract boolean getObjectDistribution()
```

Object Distribution Gdy true, zawartość tablicy jest rozmieszczana do maksymalnej szerokości obiektu tablicy.

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
public abstract void setObjectDistribution(boolean value)
```

Object Distribution Gdy true, zawartość tablicy jest rozmieszczana do maksymalnej szerokości obiektu tablicy.

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
public abstract int getRowSpacingRule()
```

Typ pionowego odstępu między elementami tablicy

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
public abstract void setRowSpacingRule(int value)
```

Typ pionowego odstępu między elementami tablicy

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
public abstract long getRowSpacing()
```

Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule jest ustawiony na 3. W tym przypadku jednostką jest punkt lub przy Multiple jednostką jest półlina. Domyślnie: 0

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
public abstract void setRowSpacing(long value)
```

Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule jest ustawiony na 3. W tym przypadku jednostką jest punkt lub przy Multiple jednostką jest półlina. Domyślnie: 0

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