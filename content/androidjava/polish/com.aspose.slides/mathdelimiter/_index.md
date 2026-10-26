---
title: MathDelimiter
second_title: Aspose.Slides dla Androida poprzez dokumentację API Java
description: Określa obiekt separatora składający się z znaków otwierających i zamykających, takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski, oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem.
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

Określa obiekt separatora, składający się z znaków otwierających i zamykających (takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getArguments()](#getArguments--) | Jeden lub więcej elementów matematycznych oddzielonych znakami separatora |
| [getBeginningCharacter()](#getBeginningCharacter--) | Znak początkowy separatora określa początkowy, czyli otwierający, znak separatora. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Znak początkowy separatora określa początkowy, czyli otwierający, znak separatora. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Znak separatora określa znak, który oddziela argumenty w obiekcie separatora. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Znak separatora określa znak, który oddziela argumenty w obiekcie separatora. |
| [getEndingCharacter()](#getEndingCharacter--) | Znak końcowy separatora określa końcowy, czyli zamykający, znak separatora. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Znak końcowy separatora określa końcowy, czyli zamykający, znak separatora. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Określa rozrost znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości swojego operandu. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Określa rozrost znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości swojego operandu. |
| [getDelimiterShape()](#getDelimiterShape--) | Określa kształt delimiterów w obiekcie separatora. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Określa kształt delimiterów w obiekcie separatora. |
| [delimit(char separatorCharacter)](#delimit-char-) | Oddziela argumenty przy użyciu określonego znaku separatora |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaku kontrolnego |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Podstawowy element, do którego stosuje się separator. Może być null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final char getBeginningCharacter()
```

Znak początkowy separatora określa początkowy, czyli otwierający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, nawiasy kwadratowe i klamry. Domyślna: '('.

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

Znak początkowy separatora określa początkowy, czyli otwierający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, nawiasy kwadratowe i klamry. Domyślna: '('.

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

Znak separatora określa znak, który oddziela argumenty w obiekcie separatora. Domyślna: '|'.

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

Znak separatora określa znak, który oddziela argumenty w obiekcie separatora. Domyślna: '|'.

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

Znak końcowy separatora określa końcowy, czyli zamykający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, nawiasy kwadratowe i klamry. Domyślna: ')'.

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
public final void setEndingCharacter(char value)
```

Znak końcowy separatora określa końcowy, czyli zamykający, znak separatora. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy, nawiasy kwadratowe i klamry. Domyślna: ')'.

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

Określa rozrost znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości swojego operandu. Domyślna wartość to true

--------------------

> ```
> Przykład:
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

Określa rozrost znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości swojego operandu. Domyślna wartość to true

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

Określa kształt delimiterów w obiekcie separatora. Gdy jest MathDelimiterShape.Centered, delimitery są wyśrodkowane względem osi matematycznej tekstu i wciąż mogą być dopasowane do całej wysokości ich zawartości. Gdy jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane tak, aby dokładnie pasowały do zawartości.

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
public final void setDelimiterShape(int value)
```

Określa kształt delimiterów w obiekcie separatora. Gdy jest MathDelimiterShape.Centered, delimitery są wyśrodkowane względem osi matematycznej tekstu i wciąż mogą być dopasowane do całej wysokości ich zawartości. Gdy jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane tak, aby dokładnie pasowały do zawartości.

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
public final IMathDelimiter delimit(char separatorCharacter)
```

Oddziela argumenty przy użyciu określonego znaku separatora

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char | znak separatora |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ten obiekt po zastosowaniu znaku separatora
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka

--------------------

> ```
> Example:
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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Jeśli beginningCharacter i endingCharacter są null, odpowiednie właściwości są przypisywane tylko wartościom i nie tworzony jest nowy obiekt (zwraca tę instancję). W przeciwnym razie zwraca nowy element matematyczny typu Delimiter, który zawiera określone znaki jako ramkę oraz tę instancję [MathDelimiter](../../com.aspose.slides/mathdelimiter) ujętą wewnątrz.
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