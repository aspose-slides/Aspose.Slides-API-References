---
title: MathematicalTextFactory
second_title: Aspose.Slides for Java API Referansı
description: MathematicalText öğesi oluşturulmasını sağlar
type: docs
url: /tr/com.aspose.slides/mathematicaltextfactory/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

MathematicalText öğesi oluşturulmasını sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Boş matematik metin öğesi oluşturur |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Belirtilen değerle matematik metin öğesi oluşturur |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Belirtilen değerle boş matematik metin öğesi oluşturur |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Belirtilen değer ve biçimlendirme özellikleriyle boş matematik metin öğesi oluşturur |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


Boş matematik metin öğesi oluşturur

**Dönüş:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


Belirtilen değerle matematik metin öğesi oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathSymbol | char | metin değeri olarak kullanılacak tek sembol |

**Dönüş:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


Belirtilen değerle boş matematik metin öğesi oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |

**Dönüş:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Belirtilen değer ve biçimlendirme özellikleriyle boş matematik metin öğesi oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | metin biçim ayarları |

**Dönüş:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text