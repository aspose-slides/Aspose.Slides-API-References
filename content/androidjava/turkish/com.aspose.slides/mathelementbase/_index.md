---
title: MathElementBase
second_title: Aspose.Slides for Android Java API Referansı
description: Tüm kalıtılan sınıflar için ortak olan bazı yöntemlerin uygulanmasıyla IMathElement için temel sınıf. Yalnızca dahili kullanım için.
type: docs
url: /tr/com.aspose.slides/mathelementbase/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Tüm kalıtılan sınıflar için ortak olan bazı yöntemlerin uygulanmasıyla IMathElement için temel sınıf. Yalnızca dahili kullanım için. Kalıtılan sınıf IMathElement olmalıdır.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate nesnesini döndürür. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur. |
| [join(String mathText)](#join-java.lang.String-) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur. |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [divide(String denominator)](#divide-java.lang.String-) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [enclose()](#enclose--) | Bir matematik öğesini parantez içine alır. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bir matematik öğesini parantez gibi belirtilen karakterlerle çerçeve içine alır. |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [function(String functionArgument)](#function-java.lang.String-) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Alt simge oluşturur. |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Alt simge oluşturur. |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Üst simge oluşturur. |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Üst simge oluşturur. |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sağ tarafta alt ve üst simge oluşturur. |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Sağ tarafta alt ve üst simge oluşturur. |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Sol tarafta alt ve üst simge oluşturur. |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Sol tarafta alt ve üst simge oluşturur. |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Belirtilen argümandan verilen dereceye göre matematiksel kökü belirler. |
| [radical(String degree)](#radical-java.lang.String-) | Belirtilen argümandan verilen dereceye göre matematiksel kökü belirler. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Üst limiti alır. |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Üst limiti alır. |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Alt limiti alır. |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Alt limiti alır. |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-ary operatör oluşturur. |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-ary operatör oluşturur. |
| [toMathArray()](#toMathArray--) | Dikey bir dizi yerleştirir. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | İntegrali alır. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | İntegrali alır. |
| [integral(int integralType)](#integral-int-) | Sınırlama olmadan integrali alır. |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | İntegrali alır. |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | İntegrali alır. |
| [accent(char accentCharacter)](#accent-char-) | Bu öğenin üstüne bir aksan işareti (karakter) ekler. |
| [overbar()](#overbar--) | Bu öğenin üstüne bir çubuk ekler. |
| [underbar()](#underbar--) | Bu öğenin altına bir çubuk ekler. |
| [group()](#group--) | Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir. |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Bu öğeyi alt süslü parantez gibi bir gruplama karakteri kullanarak bir gruba yerleştirir. |
| [toBorderBox()](#toBorderBox--) | Bu öğeyi kenarlık kutusuna yerleştirir. |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Bu öğeyi kenarlık kutusuna yerleştirir. |
| [toBox()](#toBox--) | Bu öğeyi, bir denklem ya da diğer matematik metin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. |
| [getChildren()](#getChildren--) | Alt öğeleri al. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur.

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Birleştirilecek öğe |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Bu örneği ve belirtilen argümanı içeren yeni bir IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | Birleştirilecek matematik metni |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Bu örneği ve belirtilen argümanı içeren yeni bir IMathBlock
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Bu pay ve belirtilen payda ile bir kesir oluşturur.

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Bu pay ve belirtilen payda ile bir kesir oluşturur.

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| denominator | java.lang.String | Payda |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur.

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |
| fractionType | int | Kesir tipi: Bar, NoBar, Skewed, Linear |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur.

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| denominator | java.lang.String | Payda |
| fractionType | int | Kesir tipi: Bar, NoBar, Skewed, Linear |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni kesir
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Bir matematik öğesini parantez içine alır.

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

Bir matematik öğesini parantez gibi belirtilen karakterlerle çerçeve içine alır.

--------------------

> ```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ köşeli parantez) |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, belirtilen karakterlerle çerçeve içine alınmış matematik öğesi
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyonun argümanı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Yeni [IMathFunction](../../com.aspose.slides/imathfunction) tipinde matematik öğesi
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionArgument | java.lang.String | Fonksiyonun argümanı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Yeni [IMathFunction](../../com.aspose.slides/imathfunction) tipinde matematik öğesi
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon adı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Yeni [IMathFunction](../../com.aspose.slides/imathfunction) tipinde matematik öğesi
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionName | java.lang.String | Fonksiyon adı |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Yeni [IMathFunction](../../com.aspose.slides/imathfunction) tipinde matematik öğesi
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionType | int | Tek argüman alan yaygın fonksiyon tiplerinden biri |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Yeni [IMathFunction](../../com.aspose.slides/imathfunction) tipinde matematik öğesi
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır.

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // ‘x’ sayısının '5' tabanına göre logaritmasını döndürür
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionType | int | İki argümanlı yaygın fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon tipine bağlı ek argüman |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Yeni [IMathFunction](../../com.aspose.slides/imathfunction) tipinde matematik öğesi
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır.

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // ‘x’ sayısının '5' tabanına göre logaritmasını döndürür
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionType | int | İki argümanlı yaygın fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Fonksiyon tipine bağlı ek argüman |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Yeni [IMathFunction](../../com.aspose.slides/imathfunction) tipinde matematik öğesi
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Alt simge oluşturur.

--------------------

> ```
> Örnek:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alt simge (sağda alt indis) |

**Döndürür:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Yeni [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) tipinde matematik öğesi
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Alt simge oluşturur.

--------------------

> ```
> Örnek:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (sağda alt indis) |

**Döndürür:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Yeni [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) tipinde matematik öğesi
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Üst simge oluşturur.

--------------------

> ```
> Örnek:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Üst simge (sağda üst indis) |

**Döndürür:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Yeni [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) tipinde matematik öğesi
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Üst simge oluşturur.

--------------------

> ```
> Örnek:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| superscript | java.lang.String | Üst simge (sağda üst indis) |

**Döndürür:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Yeni [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) tipinde matematik öğesi
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Sağ tarafta alt ve üst simge oluşturur.

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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alt simge (sağda alt indis) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Üst simge (sağda üst indis) |

**Döndürür:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Yeni [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) tipinde matematik öğesi
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Sağ tarafta alt ve üst simge oluşturur.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (sağda alt indis) |
| superscript | java.lang.String | Üst simge (sağda üst indis) |

**Döndürür:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Yeni [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) tipinde matematik öğesi
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Sol tarafta alt ve üst simge oluşturur.

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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Alt simge (solda alt indis) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Üst simge (solda üst indis) |

**Döndürür:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Yeni [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) tipinde matematik öğesi
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Sol tarafta alt ve üst simge oluşturur.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| subscript | java.lang.String | Alt simge (solda alt indis) |
| superscript | java.lang.String | Üst simge (solda üst indis) |

**Döndürür:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Yeni [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) tipinde matematik öğesi
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Belirtilen argümandan verilen dereceye göre matematiksel kökü belirler.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Kökün argümanı |

**Döndürür:**
[IMathRadical](../../com.aspose.slides/imathradical) - Yeni [IMathRadical](../../com.aspose.slides/imathradical) tipinde örnek
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Belirtilen argümandan verilen dereceye göre matematiksel kökü belirler.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| degree | java.lang.String | Kökün argümanı |

**Döndürür:**
[IMathRadical](../../com.aspose.slides/imathradical) - Yeni [IMathRadical](../../com.aspose.slides/imathradical) tipinde örnek
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Üst limiti alır.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Üst limiti alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Alt limiti alır.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Alt limiti alır.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Yeni [IMathLimit](../../com.aspose.slides/imathlimit) tipinde örnek
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N-ary operatör oluşturur.

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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| type | int | N-ary operatör tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Üst limit |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N-ary operatör oluşturur.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| type | int | N-ary operatör tipi |
| lowerLimit | java.lang.String | Alt limit |
| upperLimit | java.lang.String | Üst limit |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Dikey bir dizi yerleştirir.

--------------------

> ```
> Örnek:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Döndürür:**
[IMathArray](../../com.aspose.slides/imatharray) - Yeni [IMathArray](../../com.aspose.slides/imatharray) tipinde örnek
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

İntegrali alır.

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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin alt limiti |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin üst limiti |
| limitLocations | int | Limitlerin konumu |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

İntegrali alır.

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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin alt limiti |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | İntegralin üst limiti |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Sınırlama olmadan integrali alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

İntegrali alır.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | java.lang.String | İntegralin alt limiti |
| upperLimit | java.lang.String | İntegralin üst limiti |
| limitLocations | int | Limitlerin konumu |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

İntegrali alır.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| integralType | int | İntegral tipi |
| lowerLimit | java.lang.String | İntegralin alt limiti |
| upperLimit | java.lang.String | İntegralin üst limiti |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Yeni [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) tipinde örnek
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Bu öğenin üstüne bir aksan işareti (karakter) ekler.

--------------------

> ```
> Örnek:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| accentCharacter | char | Aksan karakteri. Değer (U+0300–U+036F) veya (U+20D0–U+20EF) aralığında olmalıdır. |

**Döndürür:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Yeni [IMathAccent](../../com.aspose.slides/imathaccent) tipinde örnek
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Bu öğenin üstüne bir çubuk ekler.

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Döndürür:**
[IMathBar](../../com.aspose.slides/imathbar) - Yeni [IMathBar](../../com.aspose.slides/imathbar) tipinde örnek
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Bu öğenin altına bir çubuk ekler.

--------------------

> ```
> Örnek:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Döndürür:**
[IMathBar](../../com.aspose.slides/imathbar) - Yeni [IMathBar](../../com.aspose.slides/imathbar) tipinde örnek
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir.

--------------------

> ```
> Örnek:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Yeni [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) tipinde örnek
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Bu öğeyi alt süslü parantez gibi bir gruplama karakteri kullanarak bir gruba yerleştirir.

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| character | char | BOTTOM CURLY BRACKET (U+23DF) veya başka bir karakter gibi gruplama karakteri |
| position | int | Gruplama karakterinin konumu |
| verticalJustification | int | Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirler. Örneğin, grup karakteri nesnenin üstündeyse, Top ayarı nesnenin üstünün temel çizgiye denk olduğunu gösterir; Bottom ayarı altının temel çizgiye denk olduğunu gösterir. |

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Yeni [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) tipinde örnek
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Bu öğeyi kenarlık kutusuna yerleştirir.

--------------------

> ```
> Örnek:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Döndürür:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Bu öğeyi içinde barındıran kenarlık kutusu
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Bu öğeyi kenarlık kutusuna yerleştirir.

--------------------

> ```
> Örnek:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| hideTop | boolean | Üst Kenarı Gizle |
| hideBottom | boolean | Alt Kenarı Gizle |
| hideLeft | boolean | Sol Kenarı Gizle |
| hideRight | boolean | Sağ Kenarı Gizle |
| strikethroughHorizontal | boolean | Yatay Çizgi Çekme |
| strikethroughVertical | boolean | Dikey Çizgi Çekme |
| strikethroughBottomLeftToTopRight | boolean | Sol Alt Köşeden Sağ Üste Çizgi Çekme |
| strikethroughTopLeftToBottomRight | boolean | Sol Üst Köşeden Sağ Alta Çizgi Çekme |

**Döndürür:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Bu öğeyi içinde barındıran kenarlık kutusu
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Bu öğeyi, bir denklem ya da diğer matematik metin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne, örneğin, hizalama noktasıyla ya da olmadan bir operatör taklidi olarak, satır sonu noktası olarak veya satır içi kesintilere izin vermeyecek şekilde gruplandırılabilir.

--------------------

> ```
> Örnek:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
```

**Döndürür:**
[IMathBox](../../com.aspose.slides/imathbox) - Bu öğeyi içinde barındıran mantıksal kutu
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Alt öğeleri al.

**Döndürür:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) dizisi