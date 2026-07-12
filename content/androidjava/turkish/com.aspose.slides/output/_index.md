---
title: Output
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: IWebDocument için çıktı öğelerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/output/
---
**Kalıtım:**  
java.lang.Object  
```
public final class Output
```

IWebDocument için çıktı öğelerinin bir koleksiyonunu temsil eder.

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Bağlam nesnesi için bir çıktı öğesi ekler. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Görüntü için bir çıktı öğesi ekler. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Görüntü için bir çıktı öğesi ekler. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Video için bir çıktı öğesi ekler. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Belirtilen yazı tipi için bir çıktı dosyası öğesi oluşturur ve ekler. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Metin içeriği için bir çıktı öğesi ekler. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Kaynağı çıktı dosyasına bağlar. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Belirtilen kaynak için yolu döndürür. |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Bağlam nesnesi için bir çıktı öğesi ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Çıktı yolu. |
| templateKey | java.lang.String | Çıktıdan önce bağlam nesnesi dönüşümü için kullanılan şablonun anahtarı. |
| contextObject | TContextObject | Bağlam nesnesi. |

**Döndürür:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) bağlam nesnesi için nesne.

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Görüntü için bir çıktı öğesi ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Çıktı yolu. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Çıktılan görüntü. |

**Döndürür:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) görüntü için nesne.

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Görüntü için bir çıktı öğesi ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Çıktı yolu. |
| image | [IImage](../../com.aspose.slides/iimage) | Çıktılan görüntü. |

**Döndürür:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) görüntü için nesne.

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Video için bir çıktı öğesi ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Çıktı yolu. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Çıktılan video. |

**Döndürür:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) video için nesne.

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Belirtilen yazı tipi için bir çıktı dosyası öğesi oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Yazı tipi çıktısının kaydedileceği dosya yolu. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Çıktıya yazılacak yazı tipi verisi. |
| fontStyle | int | Yazı tipi stili (ör. Regular, Bold, Italic). |

**Döndürür:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Oluşturulan yazı tipi için bir [IOutputFile](../../com.aspose.slides/ioutputfile) örneği.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Metin içeriği için bir çıktı öğesi ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Çıktı yolu. |
| textContent | java.lang.String | Çıktılan içerik. |

**Döndürür:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) metin içeriği için nesne.

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Kaynağı çıktı dosyasına bağlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Çıktı dosyası. |
| obj | java.lang.Object | Kaynak nesnesi. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Belirtilen kaynak için yolu döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Kaynak nesnesi. |

**Döndürür:**
java.lang.String - Kaynak yolu.