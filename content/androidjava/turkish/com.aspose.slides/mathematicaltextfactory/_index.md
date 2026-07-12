---
title: MathematicalTextFactory
second_title: Aspose.Slides for Android için Java API Referansı
description: MathematicalText öğesi oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathematicaltextfactory/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Bir MathematicalText öğesi oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Boş MathematicalText öğesi oluşturur |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Belirtilen değer ile MathematicalText öğesi oluşturur |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Belirtilen değer ile boş MathematicalText öğesi oluşturur |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Belirtilen değer ve biçimlendirme özellikleri ile boş MathematicalText öğesi oluşturur |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

Boş MathematicalText öğesi oluşturur

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

Belirtilen değere sahip MathematicalText öğesi oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathSymbol | char | metin değeri olarak kullanılacak tek sembol |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

Belirtilen değer ile boş MathematicalText öğesi oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Belirtilen değer ve biçimlendirme özellikleri ile boş MathematicalText öğesi oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | metin biçim ayarları |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text