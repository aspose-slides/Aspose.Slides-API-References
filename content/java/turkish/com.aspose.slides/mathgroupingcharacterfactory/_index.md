---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Referansı
description: Matematik gruplama karakteri oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathgroupingcharacterfactory/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Matematik gruplama karakteri oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Constructor | Description |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metotlar

| Method | Description |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Matematik gruplama karakteri oluşturur |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Matematik gruplama karakteri oluşturur |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Matematik gruplama karakteri oluşturur

**Parametreler:**
| Parameter | Type | Description |
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


Matematik gruplama karakteri oluşturur

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | gruplama karakteri uygulanacak matematik öğesi |

**Döndürür:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - yeni gruplama karakteri öğesi