---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Referansı
description: Pptx metninden HTML çıkarma seçenekleri.
type: docs
url: /tr/com.aspose.slides/texttohtmlconversionoptions/
---
**Kalıtım:**  
java.lang.Object

**Uygulanan Tüm Arayüzler:**  
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)  
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Pptx metninden HTML çıkarmak için seçenekler.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Panoya başlıkların eklenip eklenmeyeceğini belirten değeri alır veya ayarlar. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Panoya başlıkların eklenip eklenmeyeceğini belirten değeri alır veya ayarlar. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Metin özellikleri için kalıtım derinliğini alır veya ayarlar. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Metin özellikleri için kalıtım derinliğini alır veya ayarlar. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Dış nesnenin nasıl saklanacağını kontrol eden bir geriçağırım nesnesini alır veya ayarlar. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Dış nesnenin nasıl saklanacağını kontrol eden bir geriçağırım nesnesini alır veya ayarlar. |
| [getEncodingName()](#getEncodingName--) | HTML kodlama adını alır veya ayarlar. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML kodlama adını alır veya ayarlar. |

### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```

Panoya başlıkların eklenip eklenmeyeceğini belirten değeri alır veya ayarlar. Okunur/Yazılabilir boolean.

**Döndürür:**  
boolean

### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

Panoya başlıkların eklenip eklenmeyeceğini belirten değeri alır veya ayarlar. Okunur/Yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

Metin özellikleri için kalıtım derinliğini alır veya ayarlar. Okunur/Yazılabilir [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Döndürür:**  
int

### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

Metin özellikleri için kalıtım derinliğini alır veya ayarlar. Okunur/Yazılabilir [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

Dış nesnenin nasıl saklanacağını kontrol eden bir geriçağırım nesnesini alır veya ayarlar. Okunur/Yazılabilir [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Döndürür:**  
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)

### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

Dış nesnenin nasıl saklanacağını kontrol eden bir geriçağırım nesnesini alır veya ayarlar. Okunur/Yazılabilir [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

HTML kodlama adını alır veya ayarlar. Bu değer, oluşturulan HTML dosyasına kaydedilecektir, ancak dosyanın bu kodlamada kaydedilmesini sağlamak çağıranın sorumluluğundadır. Okunur/Yazılabilir String.

**Döndürür:**  
java.lang.String

### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

HTML kodlama adını alır veya ayarlar. Bu değer, oluşturulan HTML dosyasına kaydedilecektir, ancak dosyanın bu kodlamada kaydedilmesini sağlamak çağıranın sorumluluğundadır. Okunur/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |