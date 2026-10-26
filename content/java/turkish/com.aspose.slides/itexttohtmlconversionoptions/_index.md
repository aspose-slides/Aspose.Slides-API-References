---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /tr/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Pptx metninden HTML çıkarmak için seçenekler.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Clipboard başlıklarının eklenip eklenmeyeceğini gösteren değeri alır veya ayarlar. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Clipboard başlıklarının eklenip eklenmeyeceğini gösteren değeri alır veya ayarlar. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Metin özellikleri için miras derinliğini alır veya ayarlar. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Metin özellikleri için miras derinliğini alır veya ayarlar. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini alır veya ayarlar. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini alır veya ayarlar. |
| [getEncodingName()](#getEncodingName--) | HTML kodlama adını alır veya ayarlar. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML kodlama adını alır veya ayarlar. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


Clipboard başlıklarının eklenip eklenmeyeceğini gösteren değeri alır veya ayarlar. Okunur/yazılır boolean.

**Returns:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


Clipboard başlıklarının eklenip eklenmeyeceğini gösteren değeri alır veya ayarlar. Okunur/yazılır boolean.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


Metin özellikleri için miras derinliğini alır veya ayarlar. Okunur/yazılır [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Returns:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


Metin özellikleri için miras derinliğini alır veya ayarlar. Okunur/yazılır [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


Harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini alır veya ayarlar. Okunur/yazılır [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returns:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


Harici nesnenin nasıl depolanacağını kontrol eden bir geri çağırma nesnesini alır veya ayarlar. Okunur/yazılır [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


HTML kodlama adını alır veya ayarlar. Bu değer oluşturulan HTML dosyasına kaydedilecektir, ancak dosyanın bu kodlamada kaydedilmesini sağlamak çağıranın sorumluluğundadır. Okunur/yazılır String.

**Returns:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


HTML kodlama adını alır veya ayarlar. Bu değer oluşturulan HTML dosyasına kaydedilecektir, ancak dosyanın bu kodlamada kaydedilmesini sağlamak çağıranın sorumluluğundadır. Okunur/yazılır String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |