---
title: MathAccentFactory
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir matematik aksanı oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathaccentfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Bir matematik aksanı oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle bir matematik aksanı oluşturur |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Belirtilen bir matematik öğesine bir aksan karakteriyle matematik aksanı oluşturur |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle bir matematik aksanı oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksan uygulanacak matematik öğesi |

**Dönüş Değeri:**
[IMathAccent](../../com.aspose.slides/imathaccent) - yeni matematik aksanı
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Belirtilen bir matematik öğesine bir aksan karakteriyle matematik aksanı oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksan uygulanacak matematik öğesi |
| accentCharacter | char | aksan karakteri |

**Dönüş Değeri:**
[IMathAccent](../../com.aspose.slides/imathaccent) - yeni matematik aksanı