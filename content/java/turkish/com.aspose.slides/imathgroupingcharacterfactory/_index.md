---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Math bir gruplandırma karakteri oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Math bir gruplandırma karakteri oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Bir matematik gruplandırma karakteri oluşturur |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Bir matematik gruplandırma karakteri oluşturur |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Bir matematik gruplandırma karakteri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | gruplandırma karakteri uygulanacak matematik öğesi |
| character | char | gruplandırma karakteri |
| position | int | gruplandırma karakterinin konumu |
| verticalJustification | int | dikey hizalama |

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - yeni gruplandırma karakteri öğesi
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Bir matematik gruplandırma karakteri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | gruplandırma karakteri uygulanacak matematik öğesi |

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - yeni gruplandırma karakteri öğesi