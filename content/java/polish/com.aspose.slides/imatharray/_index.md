---
title: IMathArray
second_title: Aspose.Slides dla Java – referencja API
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
>  ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getArguments()](#getArguments--) | Zestaw elementów tablicy |
| [getBaseJustification()](#getBaseJustification--) | Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maksymalny rozkład. Gdy wartość jest true, tablica jest rozmieszczana na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maksymalny rozkład. Gdy wartość jest true, tablica jest rozmieszczana na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.). |
| [getObjectDistribution()](#getObjectDistribution--) | Rozkład obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczana na maksymalną szerokość obiektu tablicy. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Rozkład obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczana na maksymalną szerokość obiektu tablicy. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typ pionowego odstępu między elementami tablicy |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typ pionowego odstępu między elementami tablicy |
| [getRowSpacing()](#getRowSpacing--) | Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule ma wartość 3. W tym przypadku jednostką miary są punkty lub przy ustawieniu Multiple pół-linii. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule ma wartość 3. W tym przypadku jednostką miary są punkty lub przy ustawieniu Multiple pół-linii. |
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
>  ```

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

Maksymalny rozkład. Gdy wartość jest true, tablica jest rozmieszczana na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
>  ```

**Zwraca:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maksymalny rozkład. Gdy wartość jest true, tablica jest rozmieszczana na maksymalną szerokość elementu zawierającego (strona, kolumna, komórka itp.).

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

Rozkład obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczana na maksymalną szerokość obiektu tablicy.

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

Rozkład obiektu. Gdy wartość jest true, zawartość tablicy jest rozmieszczana na maksymalną szerokość obiektu tablicy.

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

Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule ma wartość 3. W tym przypadku jednostką miary są punkty lub przy ustawieniu Multiple pół-linii. Domyślnie: 0

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

Odstęp między wierszami tablicy. Używany tylko gdy RowSpacingRule ma wartość 3. W tym przypadku jednostką miary są punkty lub przy ustawieniu Multiple pół-linii. Domyślnie: 0

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