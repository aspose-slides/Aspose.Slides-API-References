---
title: IMathematicalTextFactory
second_title: Aspose.Slides için Android üzerinden Java API Referansı
description: MathematicalText öğesi oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

MathematicalText öğesi oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Boş bir MathematicalText öğesi oluştur |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Belirtilen değerle bir MathematicalText öğesi oluştur |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Belirtilen değerle boş bir MathematicalText öğesi oluştur |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Belirtilen değer ve biçimlendirme özellikleriyle boş bir MathematicalText öğesi oluştur |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Boş bir MathematicalText öğesi oluştur

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Belirtilen değerle bir MathematicalText öğesi oluştur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathSymbol | char | metin değeri olarak kullanılacak tek sembol |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Belirtilen değerle boş bir MathematicalText öğesi oluştur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Belirtilen değer ve biçimlendirme özellikleriyle boş bir MathematicalText öğesi oluştur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | metin biçim ayarları |

**Döndürür:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - yeni Mathematical Text