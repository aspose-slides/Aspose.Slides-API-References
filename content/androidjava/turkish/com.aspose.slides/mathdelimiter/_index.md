---
title: MathDelimiter
second_title: Aspose.Slides for Android için Java API Referansı
description: Açma ve kapama karakterlerinden (parantez, süslü parantez, köşeli parantez ve dikey çubuk gibi) oluşan ve içinde belirtilen bir karakterle ayrılmış bir veya daha fazla matematiksel öğe bulunan delimiter nesnesini tanımlar.
type: docs
url: /tr/com.aspose.slides/mathdelimiter/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Delimiter nesnesini belirler; açma ve kapama karakterlerinden (parantez, süslü parantez, köşeli parantez ve dikey çubuk gibi) oluşur ve içinde bir veya daha fazla matematiksel öğe bulunur; öğeler belirtilen bir karakterle ayrılır. Örnekler: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Belirtilen öğeyi tek temel bağımsız değişken olarak kullanarak MathDelimiter'ı başlatır |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArguments()](#getArguments--) | Ayraç karakterleriyle ayrılmış bir veya daha fazla matematiksel öğe |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character, başlangıç veya açma ayraç karakterini belirtir. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character, başlangıç veya açma ayraç karakterini belirtir. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character, bitiş veya kapama ayraç karakterini belirtir. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character, bitiş veya kapama ayraç karakterini belirtir. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter, SeparatorCharacter ve EndingCharacter'in büyümesini belirtir. True olduğunda, ayraçlar işlenenin yüksekliğine uyacak şekilde dikey olarak büyür. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter, SeparatorCharacter ve EndingCharacter'in büyümesini belirtir. True olduğunda, ayraçlar işlenenin yüksekliğine uyacak şekilde dikey olarak büyür. |
| [getDelimiterShape()](#getDelimiterShape--) | Ayraç nesnesindeki ayraçların şeklini belirtir. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Ayraç nesnesindeki ayraçların şeklini belirtir. |
| [delimit(char separatorCharacter)](#delimit-char-) | Belirtilen ayraç karakterini kullanarak bağımsız değişkenleri ayırır. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bir matematik öğesini parantez gibi belirtilen karakterlerle çerçeveleyerek kapsar. |
| [getChildren()](#getChildren--) | Alt öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |

### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Belirtilen öğeyi tek temel bağımsız değişken olarak kullanarak MathDelimiter'ı başlatır

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Ayraç uygulanan temel öğe. Null olabilir. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Ayraç karakterleriyle ayrılmış bir veya daha fazla matematiksel öğe

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Döndürür:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character, başlangıç veya açma ayraç karakterini belirtir. Matematiksel ayraçlar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Döndürür:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character, başlangıç veya açma ayraç karakterini belirtir. Matematiksel ayraçlar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. Varsayılan: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Döndürür:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. Varsayılan: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character, bitiş veya kapama ayraç karakterini belirtir. Matematiksel ayraçlar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Döndürür:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character, bitiş veya kapama ayraç karakterini belirtir. Matematiksel ayraçlar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

BeginningCharacter, SeparatorCharacter ve EndingCharacter'in büyümesini belirtir. True olduğunda, ayraçlar işlenenin yüksekliğine uyacak şekilde dikey olarak büyür. Varsayılan değer true'tır

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Döndürür:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

BeginningCharacter, SeparatorCharacter ve EndingCharacter'in büyümesini belirtir. True olduğunda, ayraçlar işlenenin yüksekliğine uyacak şekilde dikey olarak büyür. Varsayılan değer true'tır

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Ayraç nesnesindeki ayraçların şeklini belirtir. MathDelimiterShape.Centered olduğunda, ayraçlar matematiksel metnin ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine uyacak şekilde ayarlanabilir. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli tam olarak içeriklerine uyar şekilde değiştirilir.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Döndürür:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Ayraç nesnesindeki ayraçların şeklini belirtir. MathDelimiterShape.Centered olduğunda, ayraçlar matematiksel metnin ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine uyacak şekilde ayarlanabilir. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli tam olarak içeriklerine uyar şekilde değiştirilir.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Belirtilen ayraç karakterini kullanarak bağımsız değişkenleri ayırır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorCharacter | char | ayraç karakteri |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Bu nesne ayraç karakteri uygulandıktan sonra

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bir matematik öğesini parantez gibi belirtilen karakterlerle çerçeveleyerek kapsar

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ parantez) |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - beginningCharacter ve endingCharacter null ise, ilgili özellikler sadece değer alır ve yeni bir nesne oluşturulmaz (bu örnek döner). Aksi takdirde, [MathDelimiter](../../com.aspose.slides/mathdelimiter) örneği içinde çerçevelenmiş yeni Delimiter türünde bir matematik öğesi döner.

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps