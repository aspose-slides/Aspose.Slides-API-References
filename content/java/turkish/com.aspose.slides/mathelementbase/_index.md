---
title: MathElementBase
second_title: Aspose.Slides for Java API Referansı
description: Tüm türetilen sınıflar için ortak olan bazı metotların uygulanmasıyla IMathElement'in temel sınıfı. Sadece dahili kullanım için.
type: docs
url: /tr/com.aspose.slides/mathelementbase/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Tüm kalıtım sınıfları için ortak olan bazı yöntemlerin uygulanmasıyla IMathElement için temel sınıf. Yalnızca dahili kullanım içindir. Kalıtılan sınıf IMathElement olmalıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Parent\_Immediate nesnesini döndürür. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Matematiksel bir öğeyi birleştirir ve bir matematik bloğu oluşturur |
| [join(String mathText)](#join-java.lang.String-) | Matematiksel bir metni birleştirir ve bir matematik bloğu oluşturur |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Bu pay ve belirtilen paydasıyla bir kesir oluşturur |
| [divide(String denominator)](#divide-java.lang.String-) | Bu pay ve belirtilen paydasıyla bir kesir oluşturur |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Bu pay ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Bu pay ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur |
| [enclose()](#enclose--) | Bir matematik öğesini parantez içine alır |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bir matematik öğesini parantez gibi belirtilen karakterler ya da başka karakterler ile çerçeve içinde sarar |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [function(String functionArgument)](#function-java.lang.String-) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve belirtilen ek argümanı alır |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve belirtilen ek argümanı alır |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Alt simge oluşturur |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Alt simge oluşturur |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Üst simge oluşturur |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Üst simge oluşturur |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sağ tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Sağ tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sol tarafta alt ve üst simge oluşturur |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Sol tarafta alt ve üst simge oluşturur |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Belirtilen argümandan verilen dereceden matematiksel kökü belirtir. |
| [radical(String degree)](#radical-java.lang.String-) | Belirtilen argümandan verilen dereceden matematiksel kökü belirtir. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Üst sınırı alır |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Üst sınırı alır |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Alt sınırı alır |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Alt sınırı alır |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-ary bir operatör oluşturur |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-ary bir operatör oluşturur |
| [toMathArray()](#toMathArray--) | Dikey bir diziye koyar |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | İntegrali alır |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | İntegrali alır |
| [integral(int integralType)](#integral-int-) | Sınırsız integral alır |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | İntegrali alır |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | İntegrali alır |
| [accent(char accentCharacter)](#accent-char-) | Bir aksan işareti ayarlar (bu öğenin üstüne bir karakter) |
| [overbar()](#overbar--) | Bu öğenin üstüne bir çubuk ekler |
| [underbar()](#underbar--) | Bu öğenin altına bir çubuk ekler |
| [group()](#group--) | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplama karakteriyle bir gruba yerleştirir |
| [toBorderBox()](#toBorderBox--) | Bu öğeyi bir kenar kutusuna yerleştirir |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Bu öğeyi bir kenar kutusuna yerleştirir |
| [toBox()](#toBox--) | Bu öğeyi, bir denklemin ya da başka bir matematik metninin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. |
| [getChildren()](#getChildren--) | Alt öğeleri al |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent\_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Matematiksel bir öğeyi birleştirir ve bir matematik bloğu oluşturur

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
public IMathBlock join(String mathText)
```

Matematiksel bir metni birleştirir ve bir matematik bloğu oluşturur

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
public final IMathFraction divide(IMathElement denominator)
```

Bu pay ve belirtilen paydasıyla bir kesir oluşturur

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
public final IMathFraction divide(String denominator)
```

Bu pay ve belirtilen paydasıyla bir kesir oluşturur

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
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Bu pay ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur

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
public final IMathFraction divide(String denominator, int fractionType)
```

Bu pay ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur

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
public final IMathDelimiter enclose()
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
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bir matematik öğesini parantez gibi belirtilen karakterler ya da başka karakterler ile çerçeve içinde sarar

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, belirtilen karakterlerle çerçeve oluşturulmuş matematik öğesi

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
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
public final IMathFunction function(String functionArgument)
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
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
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
public final IMathFunction asArgumentOfFunction(String functionName)
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
public final IMathFunction asArgumentOfFunction(int functionType)
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
| functionType | int | Tek argümanlı ortak fonksiyon tiplerinden biri |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) tipinde yeni bir matematik öğesi

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve belirtilen ek argümanı alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' sayısının '5' tabanına göre logaritması döndürülür
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
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve belirtilen ek argümanı alır

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' sayısının '5' tabanına göre logaritması döndürülür
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
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Alt simge oluşturur

--------------------

> ```
> Örnek:
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
public final IMathSubscriptElement setSubscript(String subscript)
```

Alt simge oluşturur

--------------------

> ```
public final IMathSubscriptElement setSubscript(String subscript)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (sağda alt indeks) |

**Döndürür:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) tipinde yeni bir matematik öğesi

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Üst simge oluşturur

--------------------

> ```
> Örnek:
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
public final IMathSuperscriptElement setSuperscript(String superscript)
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
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
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
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Sağ tarafta alt ve üst simge oluşturur
> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (sağda alt indeks) |
| superscript | java.lang.String | Üst simge (sağda üst indeks) |

**Dönüş Değeri:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Yeni matematik öğesi, tipi [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Sol tarafta alt ve üst simge oluşturur

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alt simge (solda alt indeks) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Üst simge (solda üst indeks) |

**Dönüş Değeri:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Yeni matematik öğesi, tipi [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Sol tarafta alt ve üst simge oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (solda alt indeks) |
| superscript | java.lang.String | Üst simge (solda üst indeks) |

**Dönüş Değeri:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Yeni matematik öğesi, tipi [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Verilen derecenin belirtilen argümandan matematiksel kökünü belirtir.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Radical argümanı |

**Dönüş Değeri:**
[IMathRadical](../../com.aspose.slides/imathradical) - Yeni [IMathRadical](../../com.aspose.slides/imathradical) tipinde örnek
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Verilen derecenin belirtilen argümandan matematiksel kökünü belirtir.

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
| degree | java.lang.String | Radical argümanı |

**Dönüş Değeri:**
[IMathRadical](../../com.aspose.slides/imathradical) - Yeni [IMathRadical](../../com.aspose.slides/imathradical) tipinde örnek
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Üst sınırı alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Dönüş Değeri:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Üst sınırı alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Dönüş Değeri:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Alt sınırı alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Dönüş Değeri:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Alt sınırı alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Dönüş Değeri:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | N-ary operatör tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt sınır |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Üst sınır |

**Dönüş Değeri:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N-ary bir operatör oluşturur

--------------------

> ```
> Örnek:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | N-ary operatör tipi |
| lowerLimit | java.lang.String | Alt sınır |
| upperLimit | java.lang.String | Üst sınır |

**Dönüş Değeri:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Dikey bir diziye yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Dönüş Değeri:**
[IMathArray](../../com.aspose.slides/imatharray) - Yeni [IMathArray](../../com.aspose.slides/imatharray) tipinde örnek
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

İntegrali alır

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
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin alt sınırı |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin üst sınırı |
| limitLocations | int | Sınır konumları |

**Dönüş Değeri:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin alt sınırı |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin üst sınırı |

**Dönüş Değeri:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Sınırsız limit olmadan integrali alır

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |

**Dönüş Değeri:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

İntegrali alır

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
| lowerLimit | java.lang.String | İntegralin alt sınırı |
| upperLimit | java.lang.String | İntegralin üst sınırı |
| limitLocations | int | Sınır konumları |

**Dönüş Değeri:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

İntegrali alır

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
| lowerLimit | java.lang.String | İntegralin alt sınırı |
| upperLimit | java.lang.String | İntegralin üst sınırı |

**Dönüş Değeri:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Bu öğenin üstüne bir aksan işareti (üst karakter) ekler

--------------------

> ```
> Örnek:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| accentCharacter | char | Aksan karakteri. Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır |

**Dönüş Değeri:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Yeni [IMathAccent](../../com.aspose.slides/imathaccent) tipinde örnek
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Bu öğenin üstüne bir çubuk ekler

--------------------

> ```
public final IMathBar overbar()
```

**Dönüş Değeri:**
[IMathBar](../../com.aspose.slides/imathbar) - Yeni [IMathBar](../../com.aspose.slides/imathbar) tipinde örnek
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Bu öğenin altına bir çubuk ekler

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Dönüş Değeri:**
[IMathBar](../../com.aspose.slides/imathbar) - Yeni [IMathBar](../../com.aspose.slides/imathbar) tipinde örnek
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Dönüş Değeri:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Yeni [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) tipinde örnek
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Alt süslü parantez gibi bir grup karakteri ya da başka bir karakter kullanarak bu öğeyi bir gruba yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| character | char | BOTTOM CURLY BRACKET (U+23DF) gibi bir grup karakteri ya da başka bir karakter |
| position | int | Grup karakterinin konumu |
| verticalJustification | int | Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirtir. Örneğin, grup karakteri nesnenin üstünde olduğunda, VerticalJustification=Top, nesnenin üst kısmının temel çizgide olduğunu gösterir; VerticalJustification=Bottom ise nesnenin alt kısmı temel çizgide olur |

**Dönüş Değeri:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Yeni [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) tipinde örnek
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Bu öğeyi bir border-box içine yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Dönüş Değeri:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Bu öğe içinde bulunan bir border-box
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Bu öğeyi bir border-box içine yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hideTop | boolean | Üst Kenarı Gizle |
| hideBottom | boolean | Alt Kenarı Gizle |
| hideLeft | boolean | Sol Kenarı Gizle |
| hideRight | boolean | Sağ Kenarı Gizle |
| strikethroughHorizontal | boolean | Yatay Border Box Üzerinden Çizgi |
| strikethroughVertical | boolean | Dikey Border Box Üzerinden Çizgi |
| strikethroughBottomLeftToTopRight | boolean | Alt-Sol-Üst-Sağ Çizgi |
| strikethroughTopLeftToBottomRight | boolean | Üst-Sol-Alt-Sağ Çizgi |

**Dönüş Değeri:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Bu öğe içinde bulunan bir border-box
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Bu öğeyi, bir denklemin ya da başka bir matematik metni parçasının bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Bir kutuya alınmış nesne, örneğin hizalama noktasıyla ya da olmadan bir operatör emülatörü olarak, bir satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir.

--------------------

> ```
> Örnek:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Dönüş Değeri:**
[IMathBox](../../com.aspose.slides/imathbox) - Bu öğe içinde bulunan mantıksal bir kutu
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Alt öğeleri al

**Dönüş Değeri:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) dizisi