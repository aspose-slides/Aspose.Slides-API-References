---
title: IMathDelimiter
second_title: Aspose.Slides for Android için Java API Referansı
description: Açma ve kapama karakterlerinden oluşan, parantez, süslü parantez, köşeli parantez ve dikey çubuk gibi karakterleri ve içinde belirtilen bir karakterle ayrılmış bir veya daha fazla matematiksel öğeyi içeren ayırıcı nesnesini belirler.
type: docs
url: /tr/com.aspose.slides/imathdelimiter/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Ayırıcı nesnesini belirtir; açma ve kapama karakterlerinden (parantezler, süslü parantezler, köşeli parantezler ve dikey çubuklar gibi) oluşur ve içinde bir veya daha fazla matematiksel öğe, belirtilen bir karakterle ayrılmış olarak bulunur. Örnekler: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArguments()](#getArguments--) | Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character, başlangıç ya da açma ayırıcı karakterini belirtir. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character, başlangıç ya da açma ayırıcı karakterini belirtir. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character, ayırıcı nesnedeki argümanları ayıran karakteri belirtir. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character, ayırıcı nesnedeki argümanları ayıran karakteri belirtir. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character, bitiş ya da kapama ayırıcı karakterini belirtir. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character, bitiş ya da kapama ayırıcı karakterini belirtir. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter, SeparatorCharacter, EndingCharacter büyümesini belirtir. True olduğunda, ayırıcılar operantının yüksekliğine göre dikey olarak büyür. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter, SeparatorCharacter, EndingCharacter büyümesini belirtir. True olduğunda, ayırıcılar operantının yüksekliğine göre dikey olarak büyür. |
| [getDelimiterShape()](#getDelimiterShape--) | Ayırıcı nesnedeki ayırıcıların şeklini belirtir. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Ayırıcı nesnedeki ayırıcıların şeklini belirtir. |
| [delimit(char separatorCharacter)](#delimit-char-) | Argümanları belirtilen ayırıcı karakterle sınırlar. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe

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

Delimiter Beginning Character, başlangıç ya da açma ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayıcı karakterlerdir. Varsayılan değer: '('.

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

Delimiter Beginning Character, başlangıç ya da açma ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayıcı karakterlerdir. Varsayılan değer: '('.

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
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character, ayırıcı nesnedeki argümanları ayıran karakteri belirtir. Varsayılan: '|'.

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

Delimiter Separator Character, ayırıcı nesnedeki argümanları ayıran karakteri belirtir. Varsayılan: '|'.

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
public abstract char getEndingCharacter()
```

Delimiter Ending Character, bitiş ya da kapama ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayıcı karakterlerdir. Varsayılan değer: ')'.

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

Delimiter Ending Character, bitiş ya da kapama ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayıcı karakterlerdir. Varsayılan değer: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

BeginningCharacter, SeparatorCharacter, EndingCharacter büyümesini belirtir. True olduğunda, ayırıcılar operantının yüksekliğine göre dikey olarak büyür. Varsayılan değer true'tir

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

BeginningCharacter, SeparatorCharacter, EndingCharacter büyümesini belirtir. True olduğunda, ayırıcılar operantının yüksekliğine göre dikey olarak büyür. Varsayılan değer true'tir

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
public abstract int getDelimiterShape()
```

Ayırıcı nesnedeki ayırıcıların şeklini belirtir. MathDelimiterShape.Centered olduğunda, ayırıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde stillendirilebilir. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli içerikleriyle tam olarak eşleşecek şekilde değiştirilir.

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

Ayırıcı nesnedeki ayırıcıların şeklini belirtir. MathDelimiterShape.Centered olduğunda, ayırıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde stillendirilebilir. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli içerikleriyle tam olarak eşleşecek şekilde değiştirilir.

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Argümanları belirtilen ayırıcı karakterle sınırlar

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorCharacter | char | ayırıcı karakter |
**Döndürür:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ayırıcı karakteri uyguladıktan sonraki bu nesne