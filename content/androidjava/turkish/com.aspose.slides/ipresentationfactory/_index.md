---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Referansı
description: COM arabirimi aracılığıyla sunum oluşturulmasına izin verir
type: docs
url: /tr/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

COM arabirimi aracılığıyla sunum oluşturulmasına izin verir
## Yöntemler

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Yeni bir sunum oluşturur. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Ek yük seçenekleriyle yeni bir sunum oluşturur. |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Belirtilen dosyada bulunan sunum hakkında bilgi alır. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Belirtilen akışta bulunan sunum hakkında bilgi alır. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Varolan bir sunumu diziden okur. |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Ek yük seçenekleriyle diziden varolan bir sunumu okur. |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Varolan bir sunumu akıştan okur. |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Ek yük seçenekleriyle akıştan varolan bir sunumu okur. |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Varolan bir sunumu dosyadan okur. |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Ek yük seçenekleriyle akıştan varolan bir sunumu okur. |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Slaytlardan ham metni alır. |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Slaytlardan ham metni alır. |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Slaytlardan ham metni alır. |

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

Ek yük seçenekleriyle yeni bir sunum oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yük seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Yeni sunum

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

Belirtilen dosyada bulunan sunum hakkında bilgi alır.

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

Belirtilen akışta bulunan sunum hakkında bilgi alır.

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

Varolan bir sunumu diziden okur.

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

Ek yük seçenekleriyle diziden varolan bir sunumu okur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Okunacak dizi |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yük seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Akıştan varolan bir sunumu okur.

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

Ek yük seçenekleriyle akıştan varolan bir sunumu okur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Okunacak giriş akışı |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yük seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Dosyadan varolan bir sunumu okur.

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

Ek yük seçenekleriyle dosyadan varolan bir sunumu okur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Dosya adı |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yük seçenekleri |

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation) - Okunan sunum

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Slaytlardan ham metni alır.

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

Slaytlardan ham metni alır.

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

Slaytlardan ham metni alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Giriş akışı |
| mode | int | Çıkarma modu |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Yük seçenekleri |

**Döndürür:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Ham slayt metnini temsil eden SlideText dizisini içeren PresentationText örneği