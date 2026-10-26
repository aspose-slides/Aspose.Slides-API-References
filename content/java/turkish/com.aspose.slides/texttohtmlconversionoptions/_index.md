---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides Java API Referansı
description: Pptx metninden HTML çıkarmak için seçenekler.
type: docs
url: /tr/com.aspose.slides/texttohtmlconversionoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
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
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Değeri döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini gösterir. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Değeri döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini gösterir. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Metin özellikleri için kalıtım derinliğini döndürür veya ayarlar. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Metin özellikleri için kalıtım derinliğini döndürür veya ayarlar. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Dış nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini döndürür veya ayarlar. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Dış nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini döndürür veya ayarlar. |
| [getEncodingName()](#getEncodingName--) | HTML kodlama adını döndürür veya ayarlar. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML kodlama adını döndürür veya ayarlar. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Değeri döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini gösterir. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Değeri döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini gösterir. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Metin özellikleri için kalıtım derinliğini döndürür veya ayarlar. Okunabilir/yazılabilir [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Döndürür:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Metin özellikleri için kalıtım derinliğini döndürür veya ayarlar. Okunabilir/yazılabilir [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Dış nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini döndürür veya ayarlar. Okunabilir/yazılabilir [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Döndürür:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Dış nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini döndürür veya ayarlar. Okunabilir/yazılabilir [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


HTML kodlama adını döndürür veya ayarlar. Bu değer, oluşturulan HTML dosyasına kaydedilecektir, ancak dosyanın bu kodlamada kaydedileceğinden emin olmak çağıranın sorumluluğundadır. Okunabilir/yazılabilir String.

**Döndürür:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


HTML kodlama adını döndürür veya ayarlar. Bu değer, oluşturulan HTML dosyasına kaydedilecektir, ancak dosyanın bu kodlamada kaydedileceğinden emin olmak çağıranın sorumluluğundadır. Okunabilir/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |