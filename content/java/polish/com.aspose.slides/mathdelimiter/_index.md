---
title: MathDelimiter
second_title: Aspose.Slides dla Java – odniesienie API
description: Określa obiekt delimiter składający się z znaków otwierających i zamykających, takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski, oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem.
type: docs
url: /pl/com.aspose.slides/mathdelimiter/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Określa obiekt delimiter, składający się z znaków otwierających i zamykających (takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inicjalizuje MathDelimiter określonym elementem jako pojedynczy argument bazowy |
## Metody

| Metoda | Opis |
| --- | --- |
| [getArguments()](#getArguments--) | Jedna lub więcej elementów matematycznych oddzielonych znakami delimiter |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character określa początkowy, czyli otwierający, znak delimitera. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character określa początkowy, czyli otwierający, znak delimitera. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character określa końcowy, czyli zamykający, znak delimitera. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character określa końcowy, czyli zamykający, znak delimitera. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. |
| [getDelimiterShape()](#getDelimiterShape--) | Określa kształt delimiterów w obiekcie delimiter. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Określa kształt delimiterów w obiekcie delimiter. |
| [delimit(char separatorCharacter)](#delimit-char-) | Oddziela argumenty przy użyciu określonego znaku delimitera |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Otacza element matematyczny wskazanymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [getChildren()](#getChildren--) | Pobiera elementy podrzędne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Inicjalizuje MathDelimiter określonym elementem jako pojedynczy argument bazowy

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Element bazowy, do którego stosuje się delimiter. Może być null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Jedna lub więcej elementów matematycznych oddzielonych znakami delimiter

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Zwraca:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character określa początkowy, czyli otwierający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Domyślnie: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Zwraca:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character określa początkowy, czyli otwierający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Domyślnie: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Zwraca:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character określa końcowy, czyli zamykający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Domyślnie: ')'.

--------------------

> ```
> Przykład:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Zwraca:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character określa końcowy, czyli zamykający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Domyślnie: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. Domyślna wartość to true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Zwraca:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. Domyślna wartość to true

--------------------

> ```
> Przykład:
>  
  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Określa kształt delimiterów w obiekcie delimiter. Gdy wartość jest MathDelimiterShape.Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal dopasowują się do całej wysokości ich zawartości. Gdy wartość jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane, aby dokładnie pasowały do ich zawartości.

--------------------

> ```
> Przykład:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Zwraca:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Określa kształt delimiterów w obiekcie delimiter. Gdy wartość jest MathDelimiterShape.Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal dopasowują się do całej wysokości ich zawartości. Gdy wartość jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane, aby dokładnie pasowały do ich zawartości.

--------------------

> ```
> Przykład:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Oddziela argumenty przy użyciu określonego znaku delimitera

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char | znak delimitera |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ten obiekt po zastosowaniu znaku delimitera
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka

--------------------

> ```
> Przykład:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char | Znak końcowy (zwykle prawy nawias) |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Jeśli beginningCharacter i endingCharacter są null, odpowiadające właściwości są przypisane wartości i nie jest tworzony nowy obiekt (zwraca tę instancję). W przeciwnym razie zwraca nowy element matematyczny typu Delimiter, który zawiera określone znaki jako ramkę i tę instancję [MathDelimiter](../../com.aspose.slides/mathdelimiter) w ramce wewnątrz.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobiera elementy podrzędne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps