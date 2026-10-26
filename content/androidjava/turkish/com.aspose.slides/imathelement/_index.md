---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Referansı
description: Herhangi bir matematiksel öğenin temel arayüzü: kesir, matematiksel metin, fonksiyon, birden fazla öğe içeren ifade vb.
type: docs
url: /tr/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Herhangi bir matematiksel öğenin temel arayüzü: kesir, matematiksel metin, fonksiyon, birden fazla öğe içeren ifade vb.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getChildren()](#getChildren--) | Çocuk öğeleri al |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Bir matematiksel öğeyi birleştirir ve bir matematik bloğu oluşturur |
| [join(String mathText)](#join-java.lang.String-) | Bir matematiksel metni birleştirir ve bir matematik bloğu oluşturur |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur |
| [divide(String denominator)](#divide-java.lang.String-) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Belirtilen tipte bir kesir oluşturur, bu pay ve belirtilen payda ile |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Belirtilen tipte bir kesir oluşturur, bu pay ve belirtilen payda ile |
| [enclose()](#enclose--) | Bir matematik öğesini parantez içine alır |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bu öğeyi, parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeveleyerek kapatır |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [function(String functionArgument)](#function-java.lang.String-) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır ve ek bir argüman alır |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır ve ek bir argüman alır |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Alt simge oluşturur |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Alt simge oluşturur |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Üst simge oluşturur |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Üst simge oluşturur |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sağ tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Sağ tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sol tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Sol tarafta alt ve üst simge oluşturur |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [radical(String degree)](#radical-java.lang.String-) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Üst limit alır |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Üst limit alır |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Alt limit alır |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Alt limit alır |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-arit bir operatör oluşturur |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-arit bir operatör oluşturur |
| [toMathArray()](#toMathArray--) | Dikey bir diziye koyar |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | İntegra alır |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | İntegra alır |
| [integral(int integralType)](#integral-int-) | Sınırsız integra alır |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | İntegra alır |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | İntegra alır |
| [accent(char accentCharacter)](#accent-char-) | Bu öğenin üstünde bir aksan işareti ayarlar |
| [overbar()](#overbar--) | Bu öğenin üstüne bir çubuk koyar |
| [underbar()](#underbar--) | Bu öğenin altına bir çubuk koyar |
| [group()](#group--) | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplanma karakteriyle bir gruba yerleştirir |
| [toBorderBox()](#toBorderBox--) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [toBox()](#toBox--) | Bu öğeyi bir mantıksal kutuya (görünmez kutu) yerleştirir; bu kutu bir denklemin ya da diğer matematiksel metin örneklerinin bileşenlerini gruplayabilir. |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Çocuk öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

Bir matematiksel öğeyi birleştirir ve bir matematik bloğu oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Birleştirilecek öğe |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Bu örneği ve belirtilen argümanı içeren yeni bir IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

Bir matematiksel metni birleştirir ve bir matematik bloğu oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | Birleştirilecek matematiksel metin |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Bu örneği ve belirtilen argümanı içeren yeni bir IMathBlock
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

Bu payı ve belirtilen paydasıyla bir kesir oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Bu payı ve belirtilen paydasıyla bir kesir oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | java.lang.String | Payda |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

Belirtilen tipte bir kesir oluşturur, bu pay ve belirtilen payda ile

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |
| fractionType | int | Kesir tipi: Bar, NoBar, Skewed, Linear |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Belirtilen tipte bir kesir oluşturur, bu pay ve belirtilen payda ile

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | java.lang.String | Payda |
| fractionType | int | Kesir tipi: Bar, NoBar, Skewed, Linear |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Bir matematik öğesini parantez içine alır

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, parantez içeren matematik öğesi
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bu öğeyi, parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeveleyerek kapatır

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ köşeli parantez) |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, belirtilen karakterlerle çerçevelenmiş matematik öğesi
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyonun argümanı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionArgument | java.lang.String | Fonksiyonun argümanı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon adı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | java.lang.String | Fonksiyon adı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | int | Tek argümanlı yaygın bir fonksiyon tipi |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek argümanı alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returns the logarithm of 'x' to the base '5'
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | int | İki argümanlı yaygın bir fonksiyon tipi: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon tipine bağlı ek argüman |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek argümanı alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' sayısının '5' tabanındaki logaritmasını döndürür
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | int | İki argümanlı yaygın bir fonksiyon tipi: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Fonksiyon tipine bağlı ek argüman |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

Alt simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alt simge (sağda alt indeks) |

**Döndürür:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) tipinde yeni bir matematik öğesi
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

Alt simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (sağda alt indeks) |

**Döndürür:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) tipinde yeni bir matematik öğesi
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Üst simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Üst simge (sağda üst indeks) |

**Döndürür:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) tipinde yeni bir matematik öğesi
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Üst simge oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| superscript | java.lang.String | Üst simge (sağda üst indeks) |

**Döndürür:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) tipinde yeni bir matematik öğesi
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Sağ tarafta alt ve üst simge oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alt simge (sağda alt indeks) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Üst simge (sağda üst indeks) |

**Döndürür:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) tipinde yeni bir matematik öğesi
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Sağ tarafta alt ve üst simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (sağda alt indeks) |
| superscript | java.lang.String | Üst simge (sağda üst indeks) |

**Döndürür:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) tipinde yeni bir matematik öğesi
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```java
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Sol tarafta alt ve üst simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alt simge (solda alt indeks) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Üst simge (solda üst indeks) |

**Döndürür:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) tipinde yeni bir matematik öğesi
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Sol tarafta alt ve üst simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (solda alt indeks) |
| superscript | java.lang.String | Üst simge (solda üst indeks) |

**Döndürür:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) tipinde yeni bir matematik öğesi
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Kökün derecesi |

**Döndürür:**
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical) tipinde yeni bir örnek
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | java.lang.String | Kökün derecesi |

**Döndürür:**
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical) tipinde yeni bir örnek
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Üst limit alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) tipinde yeni bir örnek
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Üst limit alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) tipinde yeni bir örnek
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Alt limit alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) tipinde yeni bir örnek
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Alt limit alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) tipinde yeni bir örnek
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N-arit bir operatör oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | N-arit operatör tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Üst limit |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde yeni bir örnek
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N-arit bir operatör oluşturur

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | N-arit operatör tipi |
| lowerLimit | java.lang.String | Alt limit |
| upperLimit | java.lang.String | Üst limit |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde yeni bir örnek
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Dikey bir diziye koyar

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Döndürür:**
[IMathArray](../../com.aspose.slides/imatharray) - [IMathArray](../../com.aspose.slides/imatharray) tipinde yeni bir örnek
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

İntegra alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin alt limiti |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin üst limiti |
| limitLocations | int | limitlerin konumu |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde yeni bir örnek
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

İntegra alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin alt limiti |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin üst limiti |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde yeni bir örnek
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Sınırsız integra alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde yeni bir örnek
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

İntegra alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | java.lang.String | İntegralin alt limiti |
| upperLimit | java.lang.String | İntegralin üst limiti |
| limitLocations | int | limitlerin konumu |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde yeni bir örnek
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

İntegra alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | java.lang.String | İntegralin alt limiti |
| upperLimit | java.lang.String | İntegralin üst limiti |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde yeni bir örnek
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Bu öğenin üstünde bir aksan işareti ayarlar

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| accentCharacter | char | Aksan karakteri. Değer (U+0300-U+036F) veya (U+20D0-U+20EF) aralığında olmalıdır |

**Döndürür:**
[IMathAccent](../../com.aspose.slides/imathaccent) - [IMathAccent](../../com.aspose.slides/imathaccent) tipinde yeni bir örnek
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Bu öğenin üstüne bir çubuk koyar

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Döndürür:**
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar) tipinde yeni bir örnek
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Bu öğenin altına bir çubuk koyar

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Döndürür:**
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar) tipinde yeni bir örnek
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
```

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) tipinde yeni bir örnek
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Bu öğeyi, alt kıvrımlı parantez gibi bir gruplanma karakteriyle bir gruba yerleştirir

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| character | char | BOTTOM CURLY BRACKET (U+23DF) gibi bir gruplanma karakteri veya başka bir karakter |
| position | int | Gruplanma karakterinin konumu |
| verticalJustification | int | Gruplanma karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, Top değeri nesnenin üstünün temel çizgiye denk olduğunu gösterir; Bottom ayarlandığında, nesnenin altı temel çizgiye denk olur. |

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) tipinde yeni bir örnek
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Bu öğeyi bir kenarlık kutusuna yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
```

**Döndürür:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Bu öğenin içinde bulunduğu kenarlık kutusu
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Bu öğeyi bir kenarlık kutusuna yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hideTop | boolean | Üst kenarı gizle |
| hideBottom | boolean | Alt kenarı gizle |
| hideLeft | boolean | Sol kenarı gizle |
| hideRight | boolean | Sağ kenarı gizle |
| strikethroughHorizontal | boolean | Kenarlık kutusu yatay üzeri çizili |
| strikethroughVertical | boolean | Kenarlık kutusu dikey üzeri çizili |
| strikethroughBottomLeftToTopRight | boolean | Kenarlık kutusu alt-sol-üst-sağ üzeri çizili |
| strikethroughTopLeftToBottomRight | boolean | Kenarlık kutusu üst-sol-alt-sağ üzeri çizili |

**Döndürür:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Bu öğenin içinde bulunduğu kenarlık kutusu
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Bu öğeyi bir mantıksal kutuya (görünmez kutu) yerleştirir; bu kutu bir denklemin ya da diğer matematiksel metin örneklerinin bileşenlerini gruplayabilir. Kutulu bir nesne, örneğin, hizalama noktasıyla ya da olmadan bir operatör taklidi, satır sonu noktası ya da satır sonu kırılmalarına izin verilmemesi gibi amaçlarla kullanılabilir.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Döndürür:**
[IMathBox](../../com.aspose.slides/imathbox) - Bu öğenin içinde bulunduğu mantıksal kutu