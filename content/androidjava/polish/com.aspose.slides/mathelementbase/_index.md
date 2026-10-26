---
title: MathElementBase
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Klasa bazowa dla IMathElement zawierająca implementację niektórych metod wspólnych dla wszystkich dziedziczących klas. Przeznaczona wyłącznie do użytku wewnętrznego.
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

Klasa bazowa dla IMathElement z implementacją niektórych metod, które są wspólne dla wszystkich dziedziczących klas. Do użytku wewnętrznego. Dziedzicząca klasa musi być IMathElement.

## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Zwraca obiekt Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Łączy element matematyczny i tworzy blok matematyczny |
| [join(String mathText)](#join-java.lang.String-) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [divide(String denominator)](#divide-java.lang.String-) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [enclose()](#enclose--) | Otacza element matematyczny nawiasami |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako otoczenie |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [function(String functionArgument)](#function-java.lang.String-) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Używa określonej funkcji, używając tej instancji jako argumentu |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Używa określonej funkcji, używając tej instancji jako argumentu |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Używa określonej funkcji, używając tej instancji jako argumentu |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Używa określonej funkcji, używając tej instancji jako argumentu i określonego dodatkowego argumentu |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Używa określonej funkcji, używając tej instancji jako argumentu i określonego dodatkowego argumentu |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Tworzy indeks dolny |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Tworzy indeks dolny |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Tworzy indeks górny |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Tworzy indeks górny |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy indeks dolny i górny po prawej |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Tworzy indeks dolny i górny po prawej |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy indeks dolny i górny po lewej |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Tworzy indeks dolny i górny po lewej |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Określa pierwiastek matematyczny określonego stopnia z podanego argumentu. |
| [radical(String degree)](#radical-java.lang.String-) | Określa pierwiastek matematyczny określonego stopnia z podanego argumentu. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Ustawia górny limit |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Ustawia górny limit |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Ustawia dolny limit |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Ustawia dolny limit |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy operator n-arny |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Tworzy operator n-arny |
| [toMathArray()](#toMathArray--) | Umieszcza w pionowej tablicy |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Oblicza całkę |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Oblicza całkę |
| [integral(int integralType)](#integral-int-) | Oblicza całkę bez granic |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Oblicza całkę |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Oblicza całkę |
| [accent(char accentCharacter)](#accent-char-) | Ustawia znak akcentu (znak na górze tego elementu) |
| [overbar()](#overbar--) | Ustawia kreskę na górze tego elementu |
| [underbar()](#underbar--) | Ustawia kreskę na dole tego elementu |
| [group()](#group--) | Umieszcza ten element w grupie używając dolnego nawiasu klamrowego |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Umieszcza ten element w grupie używając znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [toBorderBox()](#toBorderBox--) | Umieszcza ten element w ramce granicznej |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Umieszcza ten element w ramce granicznej |
| [toBox()](#toBox--) | Umieszcza ten element w niewidzialnym pudełku (grupowaniu logicznym), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w ramce może (na przykład) służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalał na podziały linii wewnątrz. |
| [getChildren()](#getChildren--) | Pobierz elementy potomne |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. IDOMObject tylko do odczytu.

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

Tworzy ułamek z tym licznikiem i określonym mianownikiem

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

Tworzy ułamek z tym licznikiem i określonym mianownikiem

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

Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem

--------------------

> ```
> Przykład:
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

Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem

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

Otacza element matematyczny nawiasami

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) obejmujący nawiasy

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako otoczenie

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) obejmujący określone znaki jako otoczenie

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji

--------------------

> ```
> Przykład:
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
> Przykład:
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

Używa określonej funkcji, używając tej instancji jako argumentu

--------------------

> ```
> Przykład:
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

Używa określonej funkcji, używając tej instancji jako argumentu

--------------------

> ```
> Przykład:
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

Używa określonej funkcji, używając tej instancji jako argumentu

--------------------

> ```
> Przykład:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | int | Jeden z typów funkcji jednoparametrowych |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Używa określonej funkcji, używając tej instancji jako argumentu i określonego dodatkowego argumentu

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Zwraca logarytm z 'x' do podstawy '5'
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | int | Jeden z typów funkcji dwuparametrowych: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Dodatkowy argument w zależności od typu funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nowy element matematyczny typu [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Używa określonej funkcji, używając tej instancji jako argumentu i określonego dodatkowego argumentu

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Zwraca logarytm z 'x' do podstawy '5'
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | int | Jeden z typów funkcji dwuparametrowych: Log, Lim, Min, Max |
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
> Przykład:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks dolny (dolny indeks po prawej) |

**Zwraca:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nowy element matematyczny typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Tworzy indeks dolny

--------------------

> ```
> Przykład:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | java.lang.String | Indeks dolny (dolny indeks po prawej) |

**Zwraca:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nowy element matematyczny typu [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Tworzy indeks górny

--------------------

> ```
> Przykład:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks górny (górny indeks po prawej) |

**Zwraca:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nowy element matematyczny typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public



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
| superscript | java.lang.String | Indeks górny (górny indeks po prawej) |

**Zwraca:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nowy element matematyczny typu [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Tworzy indeks dolny i górny po prawej

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks dolny (dolny indeks po prawej) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks górny (górny indeks po prawej) |

**Zwraca:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nowy element matematyczny typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Tworzy indeks dolny i górny po prawej

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | java.lang.String | Indeks dolny (dolny indeks po prawej) |
| superscript | java.lang.String | Indeks górny (górny indeks po prawej) |

**Zwraca:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nowy element matematyczny typu [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Tworzy indeks dolny i górny po lewej

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks dolny (dolny indeks po lewej) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Indeks górny (górny indeks po lewej) |

**Zwraca:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nowy element matematyczny typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Tworzy indeks dolny i górny po lewej

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | java.lang.String | Indeks dolny (dolny indeks po lewej) |
| superscript | java.lang.String | Indeks górny (górny indeks po lewej) |

**Zwraca:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nowy element matematyczny typu [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Określa pierwiastek matematyczny określonego stopnia z podanego argumentu.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument pierwiastka |

**Zwraca:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nowa instancja typu [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Określa pierwiastek matematyczny określonego stopnia z podanego argumentu.

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| degree | java.lang.String | Argument pierwiastka |

**Zwraca:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nowa instancja typu [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Ustawia górny limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Ustawia górny limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Ustawia dolny limit

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Ustawia dolny limit

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nowa instancja typu [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Tworzy operator n-arny

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ operatora n-arnego |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górny limit |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Tworzy operator n-arny

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ operatora n-arnego |
| lowerLimit | java.lang.String | Dolny limit |
| upperLimit | java.lang.String | Górny limit |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Umieszcza w pionowej tablicy

--------------------

> ```
> Przykład:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Zwraca:**
[IMathArray](../../com.aspose.slides/imatharray) - Nowa instancja typu [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Oblicza całkę

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit całki |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górny limit całki |
| limitLocations | int | Położenie limitów |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Oblicza całkę

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolny limit całki |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górny limit całki |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Oblicza całkę bez granic

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | int | Typ całki |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Oblicza całkę

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | java.lang.String | Dolny limit całki |
| upperLimit | java.lang.String | Górny limit całki |
| limitLocations | int | Położenie limitów |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Oblicza całkę

--------------------

> ```
> Przykład:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | int | Typ całki |
| lowerLimit | java.lang.String | Dolny limit całki |
| upperLimit | java.lang.String | Górny limit całki |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nowa instancja typu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Ustawia znak akcentu (znak na górze tego elementu)

--------------------

> ```
> Przykład:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| accentCharacter | char | Znak akcentu. Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) |

**Zwraca:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nowa instancja typu [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Ustawia kreskę na górze tego elementu

--------------------

> ```
> Przykład:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Zwraca:**
[IMathBar](../../com.aspose.slides/imathbar) - Nowa instancja typu [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Ustawia kreskę na dole tego elementu

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Zwraca:**
[IMathBar](../../com.aspose.slides/imathbar) - Nowa instancja typu [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Umieszcza ten element w grupie używając dolnego nawiasu klamrowego

--------------------

> ```
public final IMathGroupingCharacter group()
```

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nowa instancja typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Umieszcza ten element w grupie używając znaku grupującego, takiego jak dolny nawias klamrowy lub inny

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| character | char | Znak grupujący, np. BOTTOM CURLY BRACKET (U+23DF) lub inny |
| position | int | Pozycja znaku grupującego |
| verticalJustification | int | Pionowe wyrównanie znaku grupującego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupujący jest nad obiektem, wartość Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy ustawiona jest na Bottom, dolna część obiektu znajduje się na linii bazowej. |

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nowa instancja typu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Umieszcza ten element w ramce granicznej

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```


**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Ramka graniczna z umieszczonym wewnątrz elementem

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Umieszcza ten element w ramce granicznej

--------------------

> ```
> Przykład:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hideTop | boolean | Ukryj górną krawędź |
| hideBottom | boolean | Ukryj dolną krawędź |
| hideLeft | boolean | Ukryj lewą krawędź |
| hideRight | boolean | Ukryj prawą krawędź |
| strikethroughHorizontal | boolean | Przekreślenie poziome ramki |
| strikethroughVertical | boolean | Przekreślenie pionowe ramki |
| strikethroughBottomLeftToTopRight | boolean | Przekreślenie od lewego dolnego do prawego górnego |
| strikethroughTopLeftToBottomRight | boolean | Przekreślenie od lewego górnego do prawego dolnego |

**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Ramka graniczna z umieszczonym wewnątrz elementem

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Umieszcza ten element w niewidzialnym pudełku (grupowaniu logicznym), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w ramce może (na przykład) służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalał na podziały linii wewnątrz.

--------------------

> ```
> Przykład:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Zwraca:**
[IMathBox](../../com.aspose.slides/imathbox) - Logiczna ramka z umieszczonym wewnątrz elementem

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Pobierz elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[] - Tablica [IMathElement](../../com.aspose.slides/imathelement)