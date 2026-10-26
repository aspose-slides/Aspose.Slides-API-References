---
title: MathGroupingCharacter
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Genellikle öğeler arasındaki ilişkiyi vurgulamak için bir ifadeye üstünde veya altında bir gruplanma simgesi belirler
type: docs
url: /tr/com.aspose.slides/mathgroupingcharacter/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Belirli bir ifadeye üstünde veya altında bir gruplanma simgesi tanımlar, genellikle öğeler arasındaki ilişkiyi vurgulamak için

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | MathGroupingCharacter sınıfının yeni bir örneğini, varsayılan gruplanma karakteri U+23DF (BOTTOM CURLY BRACKET) ile başlatır |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | MathGroupingCharacter sınıfının yeni bir örneğini başlatır |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getCharacter()](#getCharacter--) | Gruplama Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Gruplama Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Gruplama karakterinin konumu. |
| [setPosition(int value)](#setPosition-int-) | Gruplama karakterinin konumu. |
| [getVerticalJustification()](#getVerticalJustification--) | Grup karakterinin düşey hizalaması. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Grup karakterinin düşey hizalaması. |
| [getChildren()](#getChildren--) | Alt elemanları al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


MathGroupingCharacter sınıfının yeni bir örneğini, varsayılan gruplanma karakteri U+23DF (BOTTOM CURLY BRACKET) ile başlatır

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Çubuğun uygulandığı temel öğe |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


MathGroupingCharacter sınıfının yeni bir örneğini başlatır

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Çubuğun uygulandığı temel öğe |
| character | char | Gruplama Karakteri |
| position | int | Gruplama karakterinin konumu |
| verticalJustification | int | Grup karakterinin düşey hizalaması |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Gruplama Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alt Parantez
> ```

**Döndürür:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Gruplama Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alt Parantez
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Gruplama karakterinin konumu. Varsayılan: Alt

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Gruplama karakterinin konumu. Varsayılan: Alt

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


Grup karakterinin düşey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, Top değeri nesnenin üst kısmının temel çizgi üzerinde olduğunu gösterir; VerticalJustification Bottom olarak ayarlandığında nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom, Position=Bottom için Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Döndürür:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


Grup karakterinin düşey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, Top değeri nesnenin üst kısmının temel çizgi üzerinde olduğunu gösterir; VerticalJustification Bottom olarak ayarlandığında nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom, Position=Bottom için Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Alt elemanları al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps