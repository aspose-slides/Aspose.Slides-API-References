---
title: PresentationFactory
second_title: Aspose.Slides for Java API Referansı
description: COM arabirimi üzerinden sunum oluşturulmasına izin verir
type: docs
url: /tr/com.aspose.slides/presentationfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

COM arayüzü üzerinden sunum oluşturulmasına izin verir

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInstance()](#getInstance--) | Sunum fabrikası statik örneği. |
| [createPresentation()](#createPresentation--) | Yeni bir sunum oluşturur. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle yeni bir sunum oluşturur |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Dosyadan yeni PresentationInfo nesnesi oluşturur ve sunumu ona bağlar. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Akıttan yeni PresentationInfo nesnesi oluşturur ve sunumu ona bağlar. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Varolan bir sunumu diziden okur |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle diziden varolan bir sunumu okur |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Varolan bir sunumu akımdan okur |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle akımdan varolan bir sunumu okur |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Varolan bir sunumu dosyadan okur |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle akımdan varolan bir sunumu okur |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Slaytlardan ham metni alır |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Slaytlardan ham metni alır |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Slaytlardan ham metni alır |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Sunum fabrikası statik örneği. Salt okunur [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Döndürür:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Yeni bir sunum oluşturur.

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Yeni sunum
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Ek yükleme seçenekleriyle yeni bir sunum oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Yeni sunum
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Dosyadan yeni PresentationInfo nesnesi oluşturur ve sunumu ona bağlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Sunum dosyası. |

**Döndürür:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Sunuma bağlanan sunum bilgisi.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Akıttan yeni PresentationInfo nesnesi oluşturur ve sunumu ona bağlar. Belirtilen akıttaki sunum hakkında bilgi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Sunum akışı. |

**Döndürür:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Sunuma bağlanan sunum bilgisi.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


Varolan bir sunumu diziden okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Okunacak dizi |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Ek yükleme seçenekleriyle diziden varolan bir sunumu okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Okunacak dizi |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Varolan bir sunumu akımdan okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Okunacak giriş akışı |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Ek yükleme seçenekleriyle akımdan varolan bir sunumu okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Okunacak giriş akışı |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


Varolan bir sunumu dosyadan okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Dosya adı |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Ek yükleme seçenekleriyle dosyadan varolan bir sunumu okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Dosya adı |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Slaytlardan ham metni alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Giriş dosyası |
| mode | int | Çıkarma modu |

**Döndürür:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Ham slayt metnini temsil eden SlideText dizisini içeren PresentationText örneği
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Slaytlardan ham metni alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Giriş akışı |
| mode | int | Çıkarma modu |

**Döndürür:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Ham slayt metnini temsil eden SlideText dizisini içeren PresentationText örneği
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Slaytlardan ham metni alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Giriş akışı |
| mode | int | Çıkarma modu |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Ham slayt metnini temsil eden SlideText dizisini içeren PresentationText örneği