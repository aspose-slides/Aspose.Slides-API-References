---
title: MathDelimiter
second_title: Aspose.Slides için Java API Referansı
description: Açma ve kapama karakterlerinden (parantez, süslü parantez, köşeli parantez ve dikey çubuk gibi) oluşan ve içinde bir veya daha fazla matematiksel öğe bulunan, belirtilen bir karakterle ayrılmış sınırlayıcı nesneyi tanımlar.
type: docs
url: /tr/com.aspose.slides/mathdelimiter/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Açma ve kapama karakterlerinden (parantez, süslü parantez, köşeli parantez ve dikey çubuk gibi) oluşan ve içinde bir veya daha fazla matematiksel öğe bulunan, belirtilen bir karakterle ayrılmış sınırlayıcı nesneyi tanımlar. Örnekler: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initializes MathDelimiter with the specified element as single base argument |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getArguments()](#getArguments--) | One or more mathematical elements separated by delimiter characters |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specifies the ending, or closing, delimiter character. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specifies the ending, or closing, delimiter character. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [getDelimiterShape()](#getDelimiterShape--) | Specifies the shape of delimiters in the delimiter object. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specifies the shape of delimiters in the delimiter object. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimits arguments using the specified delimiter character |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


Belirtilen öğeyi tek bir temel argüman olarak kullanarak MathDelimiter'ı başlatır

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Sınırlayıcının uygulandığı temel öğe. Null olabilir. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Bir veya daha fazla matematiksel öğe, sınırlayıcı karakterlerle ayrılmış

--------------------

> ```
> Example:
>  
>  IMMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Döndürür:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```


Sınırlayıcı Başlangıç Karakteri, başlangıç ya da açma sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayan karakterlerdir. Varsayılan: '('.

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


Sınırlayıcı Başlangıç Karakteri, başlangıç ya da açma sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayan karakterlerdir. Varsayılan: '('.

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
public final void setSeparatorCharacter(char value)
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```


Sınırlayıcı Bitiş Karakteri, bitiş ya da kapama sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayan karakterlerdir. Varsayılan: ')'.

--------------------

> ```
> Örnek:
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


Sınırlayıcı Bitiş Karakteri, bitiş ya da kapama sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayan karakterlerdir. Varsayılan: ')'.

--------------------

> ```
> Örnek:
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


Başlangıç Karakteri, Ayırıcı Karakter ve Bitiş Karakterinin büyümesini belirtir. true olduğunda, sınırlayıcılar operatör yüksekliğine uymak için dikey olarak büyür. Varsayılan değer true'tur

--------------------

> ```
> Örnek:
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


Başlangıç Karakteri, Ayırıcı Karakter ve Bitiş Karakterinin büyümesini belirtir. true olduğunda, sınırlayıcılar operatör yüksekliğine uymak için dikey olarak büyür. Varsayılan değer true'tur

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


Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirler. MathDelimiterShape.Centered olduğunda, sınırlayıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine uyacak şekilde ayarlanır. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli içeriklerine tam olarak uyması için değiştirilir.

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


Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirler. MathDelimiterShape.Centered olduğunda, sınırlayıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine uyacak şekilde ayarlanır. MathDelimiterShape.Match olduğunda, yüksekliği ve şekli içeriklerine tam olarak uyması için değiştirilir.

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


Belirtilen sınırlayıcı karakteri kullanarak argümanları sınırlandırır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorCharacter | char | sınırlayıcı karakter |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Bu nesne sınırlayıcı karakter uygulandıktan sonra

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Bir matematik öğesini parantez gibi belirtilen karakterlerle ya da başka karakterlerle çerçeveleyerek çevreler

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - beginningCharacter ve endingCharacter null ise, ilgili özellikler sadece değer alır ve yeni bir nesne oluşturulmaz (bu örnek döndürülür). Aksi takdirde, belirtilen karakterleri çerçeveleyen ve bu [MathDelimiter](../../com.aspose.slides/mathdelimiter) örneği içinde çerçevelenmiş Delimiter tipinde yeni bir matematik öğesi döndürür.

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