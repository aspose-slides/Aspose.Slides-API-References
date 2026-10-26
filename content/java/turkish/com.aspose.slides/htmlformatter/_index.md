---
title: HtmlFormatter
second_title: Aspose.Slides for Java API Referansı
description: HTML dosya şablonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/htmlformatter/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML dosya şablonunu temsil eder.
## Metotlar

| Yöntem | Açıklama |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Basit bir belge görünümü için HTML biçimlendiriciyi oluşturur ve geri döndürür; bu görünüm, birbiri altına sıralanan slayt dizilerinden oluşur. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Basit bir slayt gösterisi HTML'si için HTML biçimlendiriciyi oluşturur ve geri döndürür; slaytlar ardışık olarak gösterilir. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Özel geri çağırma tabanlı HTML oluşturma için HTML biçimlendiriciyi oluşturur ve geri döndürür. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Basit bir belge görünümü için HTML biçimlendiriciyi oluşturur ve geri döndürür; bu görünüm, birbiri altına sıralanan slayt dizilerinden oluşur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| css | java.lang.String | Bu dosya için CSS'yi belirtir. |
| showSlideTitle | boolean | Slayt görüntüsü üzerinde bir başlık varsa başlığı ekler. |

**Dönüş Değeri:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) nesnesi.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Basit bir slayt gösterisi HTML'si için HTML biçimlendiriciyi oluşturur ve geri döndürür; slaytlar ardışık olarak gösterilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| css | java.lang.String | Kullanılan CSS dosyasının URL'sini belirtir. |
| showSlideTitle | boolean | Slayt görüntüsü üzerinde bir başlık varsa başlığı ekler. |

**Dönüş Değeri:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) nesnesi.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Özel geri çağırma tabanlı HTML oluşturma için HTML biçimlendiriciyi oluşturur ve geri döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML dosyası oluşturmayı kontrol eden geri çağırma arayüzü. |

**Dönüş Değeri:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) nesnesi.