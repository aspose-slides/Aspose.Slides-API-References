---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Referansı
description: Matematik aksan oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Matematik aksan oluşturmayı sağlar

--------------------

For COM uyumluluğu için
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksan uygulanacak matematik öğesi |

**Döndürür:**
[IMathAccent](../../com.aspose.slides/imathaccent) - yeni matematik aksanı
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Belirtilen bir matematik öğesine bir matematik aksanı oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksan uygulanacak matematik öğesi |
| accentCharacter | char | aksan karakteri |

**Döndürür:**
[IMathAccent](../../com.aspose.slides/imathaccent) - yeni matematik aksanı