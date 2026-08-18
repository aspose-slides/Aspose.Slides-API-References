---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: Herhangi bir matematiksel elemanın temel arabirimi: kesir, matematiksel metin, fonksiyon, birden çok elemanlı ifade vb
type: docs
url: /tr/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Herhangi bir matematiksel elemanın temel arabirimi: kesir, matematiksel metin, fonksiyon, birden çok elemanlı ifade vb

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChildren()](#getChildren--) | Alt elemanları al |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Bir matematiksel öğeyi birleştirir ve bir matematik bloğu oluşturur |
| [join(String mathText)](#join-java.lang.String-) | Bir matematiksel metni birleştirir ve bir matematik bloğu oluşturur |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [divide(String denominator)](#divide-java.lang.String-) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [enclose()](#enclose--) | Bir matematik öğesini parantez içinde sarar |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bu öğeyi parantez gibi belirtilen karakterlerde veya başka karakterlerde çerçeveleyerek sarar |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [function(String functionArgument)](#function-java.lang.String-) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Alt simge oluşturur |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Alt simge oluşturur |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Üst simge oluşturur |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Üst simge oluşturur |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sağ tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Sağ tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sol tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Sol tarafta alt ve üst simge oluşturur |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirler. |
| [radical(String degree)](#radical-java.lang.String-) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirler. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Üst sınırı alır |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Üst sınırı alır |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Alt sınırı alır |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Alt sınırı alır |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-arlı bir operatör oluşturur |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-arlı bir operatör oluşturur |
| [toMathArray()](#toMathArray--) | Dikey bir dizi yerleştirir |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | İntegrali alır |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | İntegrali alır |
| [integral(int integralType)](#integral-int-) | Sınırsız integrali alır |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | İntegrali alır |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | İntegrali alır |
| [accent(char accentCharacter)](#accent-char-) | Üstünde bir karakter bulunan aksan işareti ayarlar |
| [overbar()](#overbar--) | Bu öğenin üstüne bir çubuk koyar |
| [underbar()](#underbar--) | Bu öğenin altına bir çubuk koyar |
| [group()](#group--) | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba koyar |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Bu öğeyi alt kıvrımlı parantez veya başka bir gruplama karakteri kullanarak bir gruba koyar |
| [toBorderBox()](#toBorderBox--) | Bu öğeyi bir kenarlık kutusuna koyar |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Bu öğeyi bir kenarlık kutusuna koyar |
| [toBox()](#toBox--) | Bu öğeyi bir görsel olmayan kutuya (mantıksal gruplama) koyar; bu, bir denklemin veya başka bir matematiksel metnin bileşenlerini gruplamak için kullanılır. |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Alt elemanları al

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

Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur

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

Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur

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

Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur

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
| fractionType | int | Kesir türü: Bar, NoBar, Skewed, Linear |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur

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
| fractionType | int | Kesir türü: Bar, NoBar, Skewed, Linear |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Bir matematik öğesini parantez içinde sarar

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

Bu öğeyi parantez gibi belirtilen karakterlerde veya başka karakterlerde çerçeveleyerek sarar

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
| beginningCharacter | char | Başlangıç karakteri (genellikle sol parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ parantez) |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, belirtilen karakterlerle çerçevelenmiş matematik öğesi

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır

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

Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır

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
| functionType | int | Tek argümanlı ortak fonksiyon tiplerinden biri |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' değerinin tabanı '5' olan logaritmasını döndürür
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | int | İki argümanlı ortak fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon tipine bağlı ek argüman |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' değerinin tabanı '5' olan logaritmasını döndürür
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | int | İki argümanlı ortak fonksiyon tiplerinden biri: Log, Lim, Min, Max |
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Sağda alt indeks (alt simge) |

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
| subscript | java.lang.String | Sağda alt indeks (alt simge) |

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Sağda üst indeks (üst simge) |

**Döndürür:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) tipinde yeni bir matematik öğesi

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Üst simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| superscript | java.lang.String | Sağda üst indeks (üst simge) |

**Döndürür:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) tipinde yeni bir matematik öğesi

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Sağ tarafta alt ve üst simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Sağda alt indeks (alt simge) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Sağda üst indeks (üst simge) |

**Döndürür:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) tipinde yeni bir matematik öğesi

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Sağ tarafta alt simge ve üst simge oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Dönüş:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


Sol tarafta alt simge ve üst simge oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**Dönüş:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


Sol tarafta alt simge ve üst simge oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**Dönüş:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
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
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**Dönüş:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```


Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**Dönüş:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```


Üst limiti alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Dönüş:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```


Üst limiti alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Dönüş:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```


Alt limiti alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Dönüş:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```


Alt limiti alır

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Dönüş:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


N-ary bir operatör oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**Dönüş:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


N-ary bir operatör oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**Dönüş:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```


Dikey bir dizi ekler

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Dönüş:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


İntegrali alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**Dönüş:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


İntegrali alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**Dönüş:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


Limitsiz integral alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |

**Dönüş:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


İntegrali alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**Dönüş:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


İntegrali alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**Dönüş:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```


Bu öğenin üstüne bir aksan işareti (üstteki karakter) ayarlar

--------------------

> ```
> Örnek:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**Dönüş:**
[IMathAccent](../../com.aspose.slides/imathaccent) - New instance of type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```


Bu öğenin üstüne bir çubuk ekler

--------------------

> ```
> Örnek:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Dönüş:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```


Bu öğenin altına bir çubuk ekler

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Dönüş:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```


Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Dönüş:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


Bu öğeyi alt süslü parantez gibi bir gruplama karakteri ya da başka bir karakter kullanarak bir gruba yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | int | Position of grouping character |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

**Dönüş:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
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
> ```


**Dönüş:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
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
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**Dönüş:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```


Bu öğeyi bir görsel olmayan kutuya (mantıksal gruplama) yerleştirir; bu kutu bir denklem ya da başka bir matematiksel metin örneğinin bileşenlerini gruplayabilir. Kutulu bir nesne, örneğin bir hizalama noktasıyla ya da olmadan bir operatör taklidi, bir satır sonu noktası olarak kullanılabilir ya da satır sonu izin verilmeyecek şekilde gruplanabilir.

--------------------

> ```
> Örnek:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Dönüş:**
[IMathBox](../../com.aspose.slides/imathbox) - Bu öğeyi içinde barındıran mantıksal kutu