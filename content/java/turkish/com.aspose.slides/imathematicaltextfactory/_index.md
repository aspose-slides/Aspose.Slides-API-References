---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: MathematicalText öğesi oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

MathematicalText öğesi oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Methods

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Boş matematik metin öğesi oluştur |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Belirtilen değerle matematik metin öğesi oluştur |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Belirtilen değerle boş matematik metin öğesi oluştur |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Belirtilen değer ve biçimlendirme özellikleriyle boş matematik metin öğesi oluştur |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Boş matematik metin öğesi oluştur

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Belirtilen değerle matematik metin öğesi oluştur

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | metin değeri olarak kullanılacak tek sembol |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Belirtilen değerle boş matematik metin öğesi oluştur

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Belirtilen değer ve biçimlendirme özellikleriyle boş matematik metin öğesi oluştur

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | metin biçim ayarları |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text