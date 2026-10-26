---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /tr/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Pptx metninden HTML çıkarma seçenekleri.
## Metotlar

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Değer döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini belirler. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Değer döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini belirler. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Değer döndürür veya ayarlar, metin özellikleri için kalıtım derinliğini. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Değer döndürür veya ayarlar, metin özellikleri için kalıtım derinliğini. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Değer döndürür veya ayarlar, harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesi. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Değer döndürür veya ayarlar, harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesi. |
| [getEncodingName()](#getEncodingName--) | Değer döndürür veya ayarlar, html kodlama adını. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Değer döndürür veya ayarlar, html kodlama adını. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Değer döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Değer döndürür veya ayarlar, Clipboard başlıklarının eklenip eklenmeyeceğini belirler. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Değer döndürür veya ayarlar, metin özellikleri için kalıtım derinliğini. Okunur/Yazılabilir [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Döndürür:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Değer döndürür veya ayarlar, metin özellikleri için kalıtım derinliğini. Okunur/Yazılabilir [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Değer döndürür veya ayarlar, harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesi. Okunur/Yazılabilir [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Döndürür:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Değer döndürür veya ayarlar, harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesi. Okunur/Yazılabilir [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Değer döndürür veya ayarlar, html kodlama adını. Bu değer oluşturulan HTML dosyasına kaydedilecek, ancak dosyanın bu kodlamada kaydedileceğinden emin olmak çağıranın sorumluluğundadır. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Değer döndürür veya ayarlar, html kodlama adını. Bu değer oluşturulan HTML dosyasına kaydedilecek, ancak dosyanın bu kodlamada kaydedileceğinden emin olmak çağıranın sorumluluğundadır. Okunur/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |