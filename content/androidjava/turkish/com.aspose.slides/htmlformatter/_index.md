---
title: HtmlFormatter
second_title: Aspose.Slides Android için Java API Referansı
description: HTML dosya şablonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/htmlformatter/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML dosya şablonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Basit bir belge görünümü için, birbiri altında sıralanan slaytlar dizisinden oluşan HTML biçimlendiriciyi oluşturur ve döndürür. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Basit bir slayt gösterisi HTML'si için, slaytları arka arkaya gösteren HTML biçimlendiriciyi oluşturur ve döndürür. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Özel geri çağırma tabanlı HTML oluşturma için HTML biçimlendiriciyi oluşturur ve döndürür. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Basit bir belge görünümü için, birbiri altında sıralanan slaytlar dizisinden oluşan HTML biçimlendiriciyi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| css | java.lang.String | Bu dosya için CSS belirler. |
| showSlideTitle | boolean | Slayt görüntüsünün üzerinde bir başlık varsa slayt başlığını ekler. |

**Dönüş Değeri:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) nesnesi.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Basit bir slayt gösterisi HTML'si için, slaytları arka arkaya gösteren HTML biçimlendiriciyi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| css | java.lang.String | Kullanılan CCS dosyasının URL'sini belirler. |
| showSlideTitle | boolean | Slayt görüntüsünün üzerinde bir başlık varsa slayt başlığını ekler. |

**Dönüş Değeri:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) nesnesi.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Özel geri çağırma tabanlı HTML oluşturma için HTML biçimlendiriciyi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML dosyası oluşturmayı kontrol eden geri çağırma arabirimi. |

**Dönüş Değeri:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) nesnesi.