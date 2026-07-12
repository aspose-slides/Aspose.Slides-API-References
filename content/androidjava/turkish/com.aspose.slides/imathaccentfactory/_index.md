---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Matematik aksanı oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Matematik aksanı oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle bir matematik aksanı oluşturur |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Belirtilen bir matematik öğesine bir matematik aksanı oluşturur |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle bir matematik aksanı oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksanı uygulanacak matematik öğesi |

**Dönüş:**
[IMathAccent](../../com.aspose.slides/imathaccent) - yeni bir matematik aksanı
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Belirtilen bir matematik öğesine bir matematik aksanı oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksanı uygulanacak matematik öğesi |
| accentCharacter | char | aksan karakteri |

**Dönüş:**
[IMathAccent](../../com.aspose.slides/imathaccent) - yeni bir matematik aksanı