---
title: MathBlockFactory
second_title: Aspose.Slides for Android Java API Referansı
description: Matematik bloğu oluşturulmasına izin verir
type: docs
url: /tr/com.aspose.slides/mathblockfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Matematik bloğu oluşturulmasına izin verir

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Matematik bloğu oluştur |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Matematik bloğu oluştur ve öğeyi içinde yerleştir |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Matematik bloğu oluştur ve öğeleri içinde yerleştir |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Matematik bloğu oluştur

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Matematik bloğu oluştur ve öğeyi içinde yerleştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Bir matematik öğesi |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Matematik bloğu oluştur ve öğeleri içinde yerleştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematik öğeleri |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block