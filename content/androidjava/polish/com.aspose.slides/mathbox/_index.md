---
title: MathBox
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Określa logiczne opakowanie (pakowanie) elementu matematycznego.
type: docs
url: /pl/com.aspose.slides/mathbox/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Określa logiczne opakowanie (pakowanie) elementu matematycznego. Na przykład obiekt opakowany może służyć jako emulator operatora z punktem wyrównania lub bez niego, służyć jako punkt łamania linii lub być grupowany w taki sposób, aby nie zezwalać na łamanie linii wewnątrz. Na przykład operator „==” powinien być opakowany, aby zapobiec łamaniu linii.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Inicjalizuje MathBox przy użyciu podanego elementu jako argumentu |
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument podstawowy |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulator operatora. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulator operatora. |
| [getNoBreak()](#getNoBreak--) | Brak łamania. Ta własność określa właściwość "unbreakable" w obiekcie pudełka. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Brak łamania. Ta własność określa właściwość "unbreakable" w obiekcie pudełka. |
| [getDifferential()](#getDifferential--) | Różnicowy. Gdy prawda, pudełko zachowuje się jako różniczka (np. \\ud835\\udc51\\ud835\\udc65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Różnicowy. Gdy prawda, pudełko zachowuje się jako różniczka (np. \\ud835\\udc51\\ud835\\udc65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Gdy prawda, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Gdy prawda, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. |
| [getExplicitBreak()](#getExplicitBreak--) | Jawne łamanie określa, czy na początku obiektu Box występuje podział linii, tak, że linia łamie się na początku obiektu. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Jawne łamanie określa, czy na początku obiektu Box występuje podział linii, tak, że linia łamie się na początku obiektu. |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaku kontrolnego |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Inicjalizuje MathBox przy użyciu podanego elementu jako argumentu

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Podstawowy element, do którego stosowane jest pudełko. Może być null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument podstawowy

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Emulator operatora. Gdy prawda, pudełko i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to, że znak może służyć jako punkt podziału linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się w operator, np. '=='. Domyślna wartość: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Zwraca:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Emulator operatora. Gdy prawda, pudełko i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to, że znak może służyć jako punkt podziału linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się w operator, np. '=='. Domyślna wartość: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Brak łamania. Ta własność określa właściwość "unbreakable" w obiekcie pudełka. Gdy prawda, nie mogą wystąpić podziały linii wewnątrz pudełka. Może to być ważne dla emulatorów operatorów składających się z więcej niż jednego operatora binarnego. Gdy element nie jest określony, podziały mogą wystąpić wewnątrz pudełka. Domyślnie: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Zwraca:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Brak łamania. Ta własność określa właściwość "unbreakable" w obiekcie pudełka. Gdy prawda, nie mogą wystąpić podziały linii wewnątrz pudełka. Może to być ważne dla emulatorów operatorów składających się z więcej niż jednego operatora binarnego. Gdy element nie jest określony, podziały mogą wystąpić wewnątrz pudełka. Domyślnie: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Różnicowy. Gdy prawda, pudełko zachowuje się jako różniczka (np. \\ud835\\udc51\\ud835\\udc65 w całce) i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false

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
public final void setDifferential(boolean value)
```

Różnicowy. Gdy prawda, pudełko zachowuje się jako różniczka (np. \\ud835\\udc51\\ud835\\udc65 w całce) i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false

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
public final boolean getAlignmentPoint()
```

Gdy prawda, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false

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
public final void setAlignmentPoint(boolean value)
```

Gdy prawda, ten emulator operatora służy jako punkt wyrównania; to znaczy, wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false

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
public final byte getExplicitBreak()
```

Jawne łamanie określa, czy na początku obiektu Box występuje podział linii, tak, że linia łamie się na początku obiektu. Określa numer operatora w poprzedniej linii tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącej linii tekstu matematycznego. Możliwe wartości: 1..255 Domyślnie: 0 (brak jawnego łamania)

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
public final void setExplicitBreak(byte value)
```

Jawne łamanie określa, czy na początku obiektu Box występuje podział linii, tak, że linia łamie się na początku obiektu. Określa numer operatora w poprzedniej linii tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącej linii tekstu matematycznego. Możliwe wartości: 1..255 Domyślnie: 0 (brak jawnego łamania)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Właściwości znaku kontrolnego

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps