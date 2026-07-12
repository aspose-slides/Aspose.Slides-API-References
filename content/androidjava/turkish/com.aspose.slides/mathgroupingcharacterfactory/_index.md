---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Referansı
description: Matematik gruplama karakteri oluşturulmasını sağlar
type: docs
url: /tr/com.aspose.slides/mathgroupingcharacterfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Bir matematik gruplama karakteri oluşturulmasını sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Constructor | Açıklama |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Bir matematik gruplama karakteri oluşturur |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Bir matematik gruplama karakteri oluşturur |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Bir matematik gruplama karakteri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | gruplama karakteri uygulanacak matematik öğesi |
| character | char | gruplama karakteri |
| position | int | gruplama karakterinin konumu |
| verticalJustification | int | dikey hizalama |

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - yeni gruplama karakteri öğesi
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Bir matematik gruplama karakteri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | gruplama karakteri uygulanacak matematik öğesi |

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - yeni gruplama karakteri öğesi