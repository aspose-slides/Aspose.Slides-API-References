---
title: IMathGroupingCharacter
second_title: Aspose.Slides for Android için Java API Referansı
description: Genellikle öğeler arasındaki ilişkiyi vurgulamak için bir ifadenin üstünde veya altında bir gruplama simgesi belirler
type: docs
url: /tr/com.aspose.slides/imathgroupingcharacter/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Bir ifade üzerinde ya da altında bir gruplama simgesi belirler, genellikle öğeler arasındaki ilişkiyi vurgulamak için kullanılır

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getCharacter()](#getCharacter--) | Gruplama Karakteri Varsayılan değeri: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Gruplama Karakteri Varsayılan değeri: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Gruplama karakterinin konumu. |
| [setPosition(int value)](#setPosition-int-) | Gruplama karakterinin konumu. |
| [getVerticalJustification()](#getVerticalJustification--) | Grup karakterinin dikey hizalaması. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Grup karakterinin dikey hizalaması. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```


Gruplama Karakteri Varsayılan değeri: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract void setCharacter(char value)
```


Gruplama Karakteri Varsayılan değeri: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alt Parantez
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Gruplama karakterinin konumu. Varsayılan: Bottom

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
public abstract void setPosition(int value)
```


Gruplama karakterinin konumu. Varsayılan: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, VerticalJustification değerinin Top olması, nesnenin üst kısmının temel çizgiye denk geldiği anlamına gelir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom, Position=Bottom için Top

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
public abstract void setVerticalJustification(int value)
```


Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, VerticalJustification değerinin Top olması, nesnenin üst kısmının temel çizgiye denk geldiği anlamına gelir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom, Position=Bottom için Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |