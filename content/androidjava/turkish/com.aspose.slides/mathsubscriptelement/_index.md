---
title: MathSubscriptElement
second_title: Aspose.Slides for Android için Java API Referansı
description: Alt simge nesnesini belirtir; bu nesne, bir temel ve aşağıya ve sağa yerleştirilmiş küçültülmüş bir alt simgeden oluşur.
type: docs
url: /tr/com.aspose.slides/mathsubscriptelement/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Alt simge nesnesini belirtir; bu nesne, bir taban ve aşağıya ve sağa yerleştirilmiş küçültülmüş bir alt simgeden oluşur.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Yapıcılar

| Constructor | Description |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSubscriptElement sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Method | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | Alt Simge |
| [getChildren()](#getChildren--) | Alt öğeleri al |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


MathSubscriptElement sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Alt Simge

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```


**Dönüş Değeri:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Alt öğeleri al

**Dönüş Değeri:**
com.aspose.slides.IMathElement[]