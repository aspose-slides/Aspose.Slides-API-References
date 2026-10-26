---
title: IMathDelimiter
second_title: Aspose.Slides for Java API Referansı
description: Parantez, küme parantezi, köşeli parantez ve dikey çubuk gibi açma ve kapama karakterlerinden oluşan ve içinde bir veya daha fazla matematiksel öğe bulunan sınırlayıcı nesneyi, belirtilen bir karakterle ayırarak tanımlar.
type: docs
url: /tr/com.aspose.slides/imathdelimiter/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Sınırlayıcı nesneyi belirtir; açma ve kapama karakterlerinden (parantez, küme parantezi, köşeli parantez ve dikey çubuk gibi) oluşur ve içinde bir veya daha fazla matematiksel öğe bulunur, belirtilen bir karakterle ayrılır. Örnekler: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
>  ```

## Yöntemler

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Bir veya daha fazla matematiksel öğe, sınırlayıcı karakterlerle ayrılmış |
| [getBeginningCharacter()](#getBeginningCharacter--) | Sınırlayıcı Başlangıç Karakteri, başlangıç ya da açma sınırlayıcı karakterini belirtir. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Sınırlayıcı Başlangıç Karakteri, başlangıç ya da açma sınırlayıcı karakterini belirtir. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Sınırlayıcı Ayırıcı Karakter, sınırlayıcı nesnedeki argümanları ayıran karakteri belirtir. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Sınırlayıcı Ayırıcı Karakter, sınırlayıcı nesnedeki argümanları ayıran karakteri belirtir. |
| [getEndingCharacter()](#getEndingCharacter--) | Sınırlayıcı Bitiş Karakteri, bitiş ya da kapama sınırlayıcı karakterini belirtir. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Sınırlayıcı Bitiş Karakteri, bitiş ya da kapama sınırlayıcı karakterini belirtir. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BaşlangıçKarakteri, AyırıcıKarakter ve BitişKarakterinin büyümesini belirtir. true olduğunda, sınırlayıcılar, işleç yüksekliğine uyması için dikey olarak büyür. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BaşlangıçKarakteri, AyırıcıKarakter ve BitişKarakterinin büyümesini belirtir. true olduğunda, sınırlayıcılar, işleç yüksekliğine uyması için dikey olarak büyür. |
| [getDelimiterShape()](#getDelimiterShape--) | Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirtir. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirtir. |
| [delimit(char separatorCharacter)](#delimit-char-) | Belirtilen sınırlayıcı karakteri kullanarak argümanları sınırlar |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Bir veya daha fazla matematiksel öğe, sınırlayıcı karakterlerle ayrılmış

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
public abstract char getBeginningCharacter()
```

Sınırlayıcı Başlangıç Karakteri, başlangıç ya da açma sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve küme parantezi gibi kapsayıcı karakterlerdir. Varsayılan değer: '('.

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
public abstract void setBeginningCharacter(char value)
```

Sınırlayıcı Başlangıç Karakteri, başlangıç ya da açma sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve küme parantezi gibi kapsayıcı karakterlerdir. Varsayılan değer: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Sınırlayıcı Ayırıcı Karakter, sınırlayıcı nesnedeki argümanları ayıran karakteri belirtir. Varsayılan: '|'.

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
public abstract void setSeparatorCharacter(char value)
```

Sınırlayıcı Ayırıcı Karakter, sınırlayıcı nesnedeki argümanları ayıran karakteri belirtir. Varsayılan: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Sınırlayıcı Bitiş Karakteri, bitiş ya da kapama sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve küme parantezi gibi kapsayıcı karakterlerdir. Varsayılan değer: ')'.

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
public abstract void setEndingCharacter(char value)
```

Sınırlayıcı Bitiş Karakteri, bitiş ya da kapama sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve küme parantezi gibi kapsayıcı karakterlerdir. Varsayılan değer: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

BaşlangıçKarakteri, AyırıcıKarakter ve BitişKarakterinin büyümesini belirtir. true olduğunda, sınırlayıcılar, işlemci yüksekliğine uyması için dikey olarak büyür. Varsayılan değer true

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

BaşlangıçKarakteri, AyırıcıKarakter ve BitişKarakterinin büyümesini belirtir. true olduğunda, sınırlayıcılar, işlemci yüksekliğine uyması için dikey olarak büyür. Varsayılan değer true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirtir. MathDelimiterShape.Centered olduğunda, sınırlayıcılar matematik metninin ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde ayarlanır. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli içeriklerine tam olarak uyması için değiştirilir.

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
public abstract void setDelimiterShape(int value)
```

Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirtir. MathDelimiterShape.Centered olduğunda, sınırlayıcılar matematik metninin ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde ayarlanır. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli içeriklerine tam olarak uyması için değiştirilir.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Belirtilen sınırlayıcı karakteri kullanarak argümanları sınırlar

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | sınırlayıcı karakter |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Bu nesne sınırlayıcı karakteri uygulandıktan sonra

