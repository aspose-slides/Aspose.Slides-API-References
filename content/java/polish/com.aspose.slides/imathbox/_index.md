---
title: IMathBox
second_title: Aspose.Slides – dokumentacja API dla Javy
description: Określa logiczne opakowanie (pakowanie) elementu matematycznego.
type: docs
url: /pl/com.aspose.slides/imathbox/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Określa logiczne opakowanie (pakowanie) elementu matematycznego. Na przykład, obiekt opakowany może służyć jako emulator operatora z lub bez punktu wyrównania, jako punkt złamania linii lub być grupowany tak, aby nie dopuszczać do złamań linii wewnątrz. Na przykład, operator "==" powinien być opakowany, aby zapobiec złamaniom linii.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulator operatora. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulator operatora. |
| [getNoBreak()](#getNoBreak--) | Brak przerwy. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Brak przerwy. |
| [getDifferential()](#getDifferential--) | Różniczka. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Różniczka. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Gdy wartość jest prawdziwa, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Gdy wartość jest prawdziwa, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. |
| [getExplicitBreak()](#getExplicitBreak--) | Jawne złamanie określa, czy na początku obiektu Box występuje złamanie linii, tak aby linia zawijała się na początku obiektu Box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Jawne złamanie określa, czy na początku obiektu Box występuje złamanie linii, tak aby linia zawijała się na początku obiektu Box. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument bazowy

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

Emulator operatora. Gdy wartość jest prawdziwa, pudełko i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt złamania linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się w operator, taki jak '=='. Wartość domyślna: false

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

Emulator operatora. Gdy wartość jest prawdziwa, pudełko i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt złamania linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się w operator, taki jak '=='. Wartość domyślna: false

--------------------

> ```
> Example:
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

Brak przerwy. Ta właściwość określa właściwość "unbreakable" w obiekcie pudełka. Gdy wartość jest prawdziwa, w obrębie pudełka nie mogą wystąpić żadne złamania linii. Może to być ważne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, w pudełku mogą wystąpić przerwy. Domyślnie: true

--------------------

> ```
> Example:
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

Brak przerwy. Ta właściwość określa właściwość "unbreakable" w obiekcie pudełka. Gdy wartość jest prawdziwa, w obrębie pudełka nie mogą wystąpić żadne złamania linii. Może to być ważne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, w pudełku mogą wystąpić przerwy. Domyślnie: true

--------------------

> ```
> Example:
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

Różniczka. Gdy wartość jest prawdziwa, pudełko pełni funkcję różniczki (np., \\ud835\\udc51\\ud835\\udc65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false

--------------------

> ```
> Example:
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

Różniczka. Gdy wartość jest prawdziwa, pudełko pełni funkcję różniczki (np., \\ud835\\udc51\\ud835\\udc65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false

--------------------

> ```
> Example:
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

Gdy wartość jest prawdziwa, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false

--------------------

> ```
> Example:
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

Gdy wartość jest prawdziwa, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false

--------------------

> ```
> Example:
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

Jawne złamanie określa, czy na początku obiektu Box występuje złamanie linii, tak aby linia zawijała się na początku obiektu Box. Określa liczbę operatora w poprzedniej linii tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącej linii tekstu matematycznego. Możliwe wartości: 1..255 Domyślnie: 0 (brak jawnego złamania)

--------------------

> ```
> Example:
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

Jawne złamanie określa, czy na początku obiektu Box występuje złamanie linii, tak aby linia zawijała się na początku obiektu Box. Określa liczbę operatora w poprzedniej linii tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącej linii tekstu matematycznego. Możliwe wartości: 1..255 Domyślnie: 0 (brak jawnego złamania)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |