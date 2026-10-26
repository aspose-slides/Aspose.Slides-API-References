---
title: MathElementBase
second_title: Odwołanie API Aspose.Slides dla Javy
description: Klasa bazowa dla IMathElement zawierająca implementację niektórych metod wspólnych dla wszystkich klas dziedziczących. Do użytku wewnętrznego.
type: docs
url: /pl/com.aspose.slides/mathelementbase/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Klasa bazowa dla IMathElement zawierająca implementację niektórych metod wspólnych dla wszystkich klas dziedziczących. Do użytku wewnętrznego. Klasa dziedzicząca musi być IMathElement.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Zwraca obiekt Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Łączy element matematyczny i tworzy blok matematyczny |
| [join(String mathText)](#join-java.lang.String-) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Tworzy ułamek z tym licznikem i określonym mianownikiem |
| [divide(String denominator)](#divide-java.lang.String-) | Tworzy ułamek z tym licznikem i określonym mianownikiem |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Tworzy ułamek określonego typu z tym licznikem i określonym mianownikiem |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Tworzy ułamek określonego typu z tym licznikem i określonym mianownikiem |
| [enclose()](#enclose--) | Umieszcza element matematyczny w nawiasach |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Umieszcza element matematyczny w określonych znakach, takich jak nawiasy lub inne znaki jako ramka |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [function(String functionArgument)](#function-java.lang.String-) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Tworzy indeks dolny |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Tworzy indeks dolny |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Tworzy indeks górny |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Tworzy indeks górny |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy indeks dolny i górny po prawej stronie |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Tworzy indeks dolny i górny po prawej stronie |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy indeks dolny i górny po lewej stronie |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Tworzy indeks dolny i górny po lewej stronie |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Określa pierwiastek matematyczny stopnia podanego z określonego argumentu. |
| [radical(String degree)](#radical-java.lang.String-) | Określa pierwiastek matematyczny stopnia podanego z określonego argumentu. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Przyjmuje górny limit |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Przyjmuje górny limit |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Przyjmuje dolny limit |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Przyjmuje dolny limit |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy operator N-arny |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Tworzy operator N-arny |
| [toMathArray()](#toMathArray--) | Umieszcza w pionowej tablicy |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Przyjmuje całkę |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Przyjmuje całkę |
| [integral(int integralType)](#integral-int-) | Przyjmuje całkę bez limitów |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Przyjmuje całkę |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Przyjmuje całkę |
| [accent(char accentCharacter)](#accent-char-) | Ustawia znak akcentu (znak na górze tego elementu) |
| [overbar()](#overbar--) | Ustawia kreskę nad tym elementem |
| [underbar()](#underbar--) | Ustawia kreskę pod tym elementem |
| [group()](#group--) | Umieszcza ten element w grupie używając dolnego nawiasu klamrowego |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Umieszcza ten element w grupie używając znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [toBorderBox()](#toBorderBox--) | Umieszcza ten element w ramce |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Umieszcza ten element w ramce |
| [toBox()](#toBox--) | Umieszcza ten element w niewidzialnym pudełku (grupowanie logiczne), które służy do grupowania komponentów równania lub innego fragmentu tekstu matematycznego. |
| [getChildren()](#getChildren--) | Pobiera elementy podrzędne |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Łączy element matematyczny i tworzy blok matematyczny

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
[IMathBlock](../../com.aspose.slides/imathblock) - Nowy IMathBlock zawierający tę instancję i określony argument

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Łączy tekst matematyczny i tworzy blok matematyczny

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

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Tworzy ułamek z tym licznikem i określonym mianownikiem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mianownik |

**Zwraca:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nowy ułamek

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Tworzy ułamek z tym licznikem i określonym mianownikiem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | java.lang.String | Mianownik |

**Zwraca:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nowy ułamek

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Tworzy ułamek określonego typu z tym licznikem i określonym mianownikiem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mianownik |
| fractionType | int | Typ ułamka: Bar, NoBar, Skewed, Linear |

**Zwraca:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nowy ułamek

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Tworzy ułamek określonego typu z tym licznikem i określonym mianownikiem

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | java.lang.String | Mianownik |
| fractionType | int | Typ ułamka: Bar, NoBar, Skewed, Linear |

**Zwraca:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nowy ułamek

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Umieszcza element matematyczny w nawiasach

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zawierający nawiasy

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Umieszcza element matematyczny w określonych znakach, takich jak nawiasy lub inne znaki jako ramka

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char | Znak końcowy (zwykle prawy nawias) |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zawierający określone znaki jako ramkę

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionArgument | java.lang.String | Argument funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nazwa funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | java.lang.String | Nazwa funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | int | Jedny z typowych typów funkcji jednego argumentu |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Zwraca logarytm 'x' o podstawie '5'
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | int | Jedny z typowych typów funkcji jednego argumentu |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Dodatkowy argument w zależności od typu funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Zwraca logarytm 'x' o podstawie '5'
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | int | Jedny z typowych typów funkcji jednego argumentu |
| additionalArgument | java.lang.String | Dodatkowy argument w zależności od typu funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Tworzy indeks dolny

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks dolny (dolny indeks po prawej stronie) |

**Zwraca:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nowy element matematyczny typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Tworzy indeks dolny

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | java.lang.String | Indeks dolny (dolny indeks po prawej stronie) |

**Zwraca:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nowy element matematyczny typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Tworzy indeks górny

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks górny (górny indeks po prawej stronie) |

**Zwraca:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nowy element matematyczny typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Tworzy indeks górny

--------------------

> ```
> Przykład:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| superscript | java.lang.String | Indeks górny (górny indeks po prawej stronie) |

**Zwraca:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nowy element matematyczny typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMat hElement subscript, IMathElement superscript)
```

Tworzy indeks dolny i górny po prawej stronie

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks dolny (dolny indeks po prawej stronie) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks górny (górny indeks po prawej stronie) |

**Zwraca:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nowy element matematyczny typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Tworzy indeks dolny i górny po prawej stronie
> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indeks dolny (dolny indeks po prawej) |
| superscript | java.lang.String | Indeks górny (górny indeks po prawej) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nowy element matematyczny typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Tworzy indeks dolny i górny po lewej

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks dolny (dolny indeks po lewej) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks górny (górny indeks po lewej) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nowy element matematyczny typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Tworzy indeks dolny i górny po lewej

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indeks dolny (dolny indeks po lewej) |
| superscript | java.lang.String | Indeks górny (górny indeks po lewej) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nowy element matematyczny typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument pierwiastka |
 
**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nowa instancja typu [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument pierwiastka |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nowa instancja typu [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Ustawia górny limit

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Ustawia górny limit

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Ustawia dolny limit

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Ustawia dolny limit

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Tworzy operator N-arny

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Typ operatora N-arny |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górny limit |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Tworzy operator N-arny

---

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Typ operatora N-arny |
| lowerLimit | java.lang.String | Dolny limit |
| upperLimit | java.lang.String | Górny limit |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Umieszcza w pionowej tablicy

---

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - Nowa instancja typu [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Oblicza całkę

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit całki |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górny limit całki |
| limitLocations | int | Lokalizacja limitów |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Oblicza całkę

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit całki |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górny limit całki |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Oblicza całkę bez limitów

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ całki |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Oblicza całkę

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | java.lang.String | Dolny limit całki |
| upperLimit | java.lang.String | Górny limit całki |
| limitLocations | int | Lokalizacja limitów |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Oblicza całkę

---

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | java.lang.String | Dolny limit całki |
| upperLimit | java.lang.String | Górny limit całki |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Ustawia znak akcentu (znak nad tym elementem)

---

> ```
> Przykład:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Znak akcentu. Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nowa instancja typu [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Ustawia kreskę nad tym elementem

---

> ```
public final IMathBar overbar()
```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Nowa instancja typu [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Ustawia kreskę pod tym elementem

---

> ```
> Przykład:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Nowa instancja typu [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego

---

> ```
> Przykład:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nowa instancja typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny

---

> ```
> Przykład:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Znak grupujący, taki jak DOLNY NAWIAS KLAMROWY (U+23DF) lub inny |
| position | int | Pozycja znaku grupującego |
| verticalJustification | int | Wyrównanie pionowe znaku grupującego. Określa wyrównanie obiektu względem linii podstawowej. Na przykład, gdy znak grupujący znajduje się nad obiektem, wyrównanie pionowe Top oznacza, że górna krawędź obiektu znajduje się na linii podstawowej; gdy wyrównanie pionowe ustawione jest na Bottom, dolna krawędź obiektu znajduje się na linii podstawowej |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nowa instancja typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Umieszcza ten element w ramce

---

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Ramka z tym elementem umieszczonym wewnątrz
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Umieszcza ten element w ramce

---

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Ukryj górną krawędź |
| hideBottom | boolean | Ukryj dolną krawędź |
| hideLeft | boolean | Ukryj lewą krawędź |
| hideRight | boolean | Ukryj prawą krawędź |
| strikethroughHorizontal | boolean | Przekreślenie poziome ramki |
| strikethroughVertical | boolean | Przekreślenie pionowe ramki |
| strikethroughBottomLeftToTopRight | boolean | Przekreślenie od dolnego lewego do górnego prawego |
| strikethroughTopLeftToBottomRight | boolean | Przekreślenie od górnego lewego do dolnego prawego |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Ramka z tym elementem umieszczonym wewnątrz
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Umieszcza ten element w nie-wizualnym pudełku (grupowaniu logicznym), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w ramce może (na przykład) służyć jako emulator operatora z lub bez punktu wyrównania, służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalać na podziały linii wewnątrz.

---

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - Logiczne pudełko z tym elementem umieszczonym wewnątrz
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Pobiera elementy podrzędne

**Returns:**
com.aspose.slides.IMathElement[] - Tablica [IMathElement](../../com.aspose.slides/imathelement)