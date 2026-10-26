---
title: MathGroupingCharacter
second_title: Aspose.Slides için Java API Referansı
description: Bir ifadenin üstünde veya altında bir gruplama sembolü belirler, genellikle öğeler arasındaki ilişkiyi vurgulamak için
type: docs
url: /tr/com.aspose.slides/mathgroupingcharacter/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Bir ifadenin üstünde veya altında bir gruplama sembolünü belirler, genellikle öğeler arasındaki ilişkiyi vurgulamak için

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | MathGroupingCharacter sınıfının yeni bir örneğini varsayılan grup karakteri U+23DF (BOTTOM CURLY BRACKET) ile başlatır |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | MathGroupingCharacter sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getCharacter()](#getCharacter--) | Grup Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grup Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Grup karakterinin konumu. |
| [setPosition(int value)](#setPosition-int-) | Grup karakterinin konumu. |
| [getVerticalJustification()](#getVerticalJustification--) | Grup karakterinin dikey hizalaması. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Grup karakterinin dikey hizalaması. |
| [getChildren()](#getChildren--) | Çocuk öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

MathGroupingCharacter sınıfının yeni bir örneğini varsayılan grup karakteri U+23DF (BOTTOM CURLY BRACKET) ile başlatır

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

MathGroupingCharacter sınıfının yeni bir örneğini başlatır.

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
| character | char | Grup Karakteri |
| position | int | Grup karakterinin konumu |
| verticalJustification | int | Grup karakterinin dikey hizalaması |

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

Grup Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET)

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

Grup Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET)

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

Grup karakterinin konumu. Varsayılan: Bottom

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

Grup karakterinin konumu. Varsayılan: Bottom

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

VerticalJustification grup karakterinin dikey hizalamasıdır. Nesnenin taban çizgisine göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, VerticalJustification değerinin Top olması nesnenin üstünün taban çizgisine denk geldiğini gösterir; VerticalJustification değeri Bottom olarak ayarlandığında nesnenin altı taban çizgisine denk gelir. Varsayılan: Position=Top için Bottom ve Position=Bottom için Top

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

VerticalJustification grup karakterinin dikey hizalamasıdır. Nesnenin taban çizgisine göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, VerticalJustification değerinin Top olması nesnenin üstünün taban çizgisine denk geldiğini gösterir; VerticalJustification değeri Bottom olarak ayarlandığında nesnenin altı taban çizgisine denk gelir. Varsayılan: Position=Top için Bottom ve Position=Bottom için Top

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

Çocuk öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps