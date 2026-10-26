---
title: IPresentationFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create presentation via COM interface
type: docs
url: /tr/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

COM arabirimi aracılığıyla sunum oluşturmayı sağlar.
## Yöntemler

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Yeni bir sunum oluşturur. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle yeni bir sunum oluşturur. |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Belirtilen dosyadaki sunum hakkında bilgi alır. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Belirtilen akıştaki sunum hakkında bilgi alır. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Mevcut bir sunumu dizi üzerinden okur |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle mevcut bir sunumu dizi üzerinden okur |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Mevcut bir sunumu akış üzerinden okur |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle mevcut bir sunumu akış üzerinden okur |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Mevcut bir sunumu dosyadan okur |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Ek yükleme seçenekleriyle mevcut bir sunumu akış üzerinden okur |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Kaydıraklardaki ham metni alır |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Kaydıraklardaki ham metni alır |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Kaydıraklardaki ham metni alır |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Yeni bir sunum oluşturur.

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Yeni sunum
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
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
public abstract IPresentationInfo getPresentationInfo(String file)
```

Belirtilen dosyadaki sunum hakkında bilgi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Sunum dosyası. |

**Döndürür:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Sunum bilgisi
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Belirtilen akıştaki sunum hakkında bilgi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Sunum akışı. |

**Döndürür:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Sunum bilgisi.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Mevcut bir sunumu dizi üzerinden okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Okunacak dizi |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Ek yükleme seçenekleriyle mevcut bir sunumu dizi üzerinden okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Okunacak dizi |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Mevcut bir sunumu akış üzerinden okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Okunacak giriş akışı |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Ek yükleme seçenekleriyle mevcut bir sunumu akış üzerinden okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Okunacak giriş akışı |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Mevcut bir sunumu dosyadan okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Dosya adı |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Ek yükleme seçenekleriyle mevcut bir sunumu dosyadan okur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Dosya adı |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Kaydıraklardaki ham metni alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Giriş dosyası |
| mode | int | Çıkarma modu |

**Döndürür:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Ham slayt metnini temsil eden SlideText dizisini içeren PresentationText örneği
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Kaydıraklardaki ham metni alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Giriş akışı |
| mode | int | Çıkarma modu |

**Döndürür:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Ham slayt metnini temsil eden SlideText dizisini içeren PresentationText örneği
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Kaydıraklardaki ham metni alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Giriş akışı |
| mode | int | Çıkarma modu |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yükleme seçenekleri |

**Döndürür:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Ham slayt metnini temsil eden SlideText dizisini içeren PresentationText örneği