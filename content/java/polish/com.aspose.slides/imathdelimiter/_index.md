---
title: IMathDelimiter
second_title: Aspose.Slides dla Java - Dokumentacja API
description: Określa obiekt separatora składający się z znaków otwierających i zamykających, takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski, oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem.
type: docs
url: /pl/com.aspose.slides/imathdelimiter/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Określa obiekt separatora, składający się z znaków otwierających i zamykających (takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getArguments()](#getArguments--) | Jeden lub więcej elementów matematycznych oddzielonych znakami separatora |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character określa początkowy, czyli otwierający, znak separatora. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character określa początkowy, czyli otwierający, znak separatora. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie separatora. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie separatora. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character określa końcowy, czyli zamykający, znak separatora. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character określa końcowy, czyli zamykający, znak separatora. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości operandów. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości operandów. |
| [getDelimiterShape()](#getDelimiterShape--) | Określa kształt delimiterów w obiekcie separatora. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Określa kształt delimiterów w obiekcie separatora. |
| [delimit(char separatorCharacter)](#delimit-char-) | Oddziela argumenty przy użyciu określonego znaku separatora |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Jeden lub więcej elementów matematycznych oddzielonych znakami separatora

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
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character określa początkowy, czyli otwierający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, kwadratowe i klamry. Domyślna wartość: '('.

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
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character określa początkowy, czyli otwierający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, kwadratowe i klamry. Domyślna wartość: '('.

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
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie separatora. Domyślnie: '|'.

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
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie separatora. Domyślnie: '|'.

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
public abstract char getEndingCharacter()
```

Delimiter Ending Character określa końcowy, czyli zamykający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, kwadratowe i klamry. Domyślna wartość: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Zwraca:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character określa końcowy, czyli zamykający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, kwadratowe i klamry. Domyślna wartość: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości operandów. Domyślna wartość to true

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości operandów. Domyślna wartość to true

--------------------

> ```
> Example:
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
public abstract int getDelimiterShape()
```

Określa kształt delimiterów w obiekcie separatora. Gdy wartość to MathDelimiterShape.Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal mogą być dopasowane do całkowitej wysokości ich zawartości. Gdy wartość to MathDelimiterShape.Match, ich wysokość i kształt są zmieniane tak, aby dokładnie pasowały do zawartości.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Zwraca:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Określa kształt delimiterów w obiekcie separatora. Gdy wartość to MathDelimiterShape.Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal mogą być dopasowane do całkowitej wysokości ich zawartości. Gdy wartość to MathDelimiterShape.Match, ich wysokość i kształt są zmieniane tak, aby dokładnie pasowały do zawartości.

--------------------

> ```
> Example:
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
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Oddziela argumenty przy użyciu określonego znaku separatora

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char | znak separatora |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ten obiekt po zastosowaniu znaku separatora