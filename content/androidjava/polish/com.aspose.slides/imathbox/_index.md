---
title: IMathBox
second_title: Aspose.Slides dla Androida przy użyciu dokumentacji API Java
description: Określa logiczne opakowanie (pakowanie) elementu matematycznego.
type: docs
url: /pl/com.aspose.slides/imathbox/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Określa logiczne opakowanie (pakowanie) elementu matematycznego. Na przykład obiekt w ramce może służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt podziału wiersza lub być grupowany w taki sposób, aby nie zezwalał na podziały wierszy wewnątrz. Przykładowo operator "==" powinien być opakowany, aby zapobiec podziałom wiersza.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Podstawowy argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulator operatora. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulator operatora. |
| [getNoBreak()](#getNoBreak--) | Brak przerwy. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Brak przerwy. |
| [getDifferential()](#getDifferential--) | Różniczka. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Różniczka. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Gdy wartość jest prawdziwa, ten emulator operatora pełni rolę punktu wyrównania; oznacza to, że wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Gdy wartość jest prawdziwa, ten emulator operatora pełni rolę punktu wyrównania; oznacza to, że wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. |
| [getExplicitBreak()](#getExplicitBreak--) | Jawny podział określa, czy na początku obiektu Box występuje podział wiersza, tak że wiersz zawija się na początku obiektu. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Jawny podział określa, czy na początku obiektu Box występuje podział wiersza, tak że wiersz zawija się na początku obiektu. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Podstawowy argument

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)

### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Emulator operatora. Gdy wartość jest prawdziwa, pudełko i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt podziału wiersza i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się, tworząc operator, taki jak '=='. Domyślna wartość: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Zwraca:**
boolean

### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Emulator operatora. Gdy wartość jest prawdziwa, pudełko i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt podziału wiersza i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się, tworząc operator, taki jak '=='. Domyślna wartość: false

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Brak przerwy. Ta właściwość określa cechę „nieprzerywalny” na obiekcie pudełka. Gdy wartość jest prawdziwa, w obrębie pudełka nie mogą występować podziały wierszy. Może to być istotne dla emulatorów operatorów składających się z więcej niż jednego operatora binarnego. Gdy element nie jest określony, podziały mogą występować wewnątrz pudełka. Domyślnie: true

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Zwraca:**
boolean

### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Brak przerwy. Ta właściwość określa cechę „nieprzerywalny” na obiekcie pudełka. Gdy wartość jest prawdziwa, w obrębie pudełka nie mogą występować podziały wierszy. Może to być istotne dla emulatorów operatorów składających się z więcej niż jednego operatora binarnego. Gdy element nie jest określony, podziały mogą występować wewnątrz pudełka. Domyślnie: true

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Różniczka. Gdy wartość jest prawdziwa, pudełko działa jako różniczka (np. \\ud835\\udc51\\ud835\\udc65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false

--------------------

> ```
> Przykład:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Zwraca:**
boolean

### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Różniczka. Gdy wartość jest prawdziwa, pudełko działa jako różniczka (np. \\ud835\\udc51\\ud835\\udc65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false

--------------------

> ```
> Przykład:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Gdy wartość jest prawdziwa, ten emulator operatora pełni rolę punktu wyrównania; oznacza to, że wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Zwraca:**
boolean

### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Gdy wartość jest prawdziwa, ten emulator operatora pełni rolę punktu wyrównania; oznacza to, że wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Jawny podział określa, czy na początku obiektu Box występuje podział wiersza, tak że wiersz zawija się na początku obiektu. Określa numer operatora w poprzednim wierszu tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącego wiersza tekstu matematycznego. Możliwe wartości: 1..255. Domyślnie: 0 (brak jawnego podziału)

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Zwraca:**
byte

### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Jawny podział określa, czy na początku obiektu Box występuje podział wiersza, tak że wiersz zawija się na początku obiektu. Określa numer operatora w poprzednim wierszu tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącego wiersza tekstu matematycznego. Możliwe wartości: 1..255. Domyślnie: 0 (brak jawnego podziału)

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |