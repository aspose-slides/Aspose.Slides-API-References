---
title: ModernComment
second_title: Aspose.Slides for Android Java API Referansı
description: Bir slayttaki yorumu temsil eder.
type: docs
url: /tr/com.aspose.slides/moderncomment/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Bir slayttaki yorumu temsil eder.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getShape()](#getShape--) | Yoruma ilişkili bir şekli döndürür. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin başlangıç konumunu alır veya ayarlar. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin başlangıç konumunu alır veya ayarlar. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin uzunluğunu alır veya ayarlar. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin uzunluğunu alır veya ayarlar. |
| [getStatus()](#getStatus--) | Yoruma ait durumu alır veya ayarlar. |
| [setStatus(byte value)](#setStatus-byte-) | Yoruma ait durumu alır veya ayarlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Yoruma ilişkili bir şekli döndürür. Salt okunur [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin başlangıç konumunu alır veya ayarlar. Okunabilir/yazılabilir int.

**Döndürür:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin başlangıç konumunu alır veya ayarlar. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin uzunluğunu alır veya ayarlar. Okunabilir/yazılabilir int.

**Döndürür:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesinde metin seçiminin uzunluğunu alır veya ayarlar. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Yoruma ait durumu alır veya ayarlar. Okunabilir/yazılabilir [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Döndürür:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Yoruma ait durumu alır veya ayarlar. Okunabilir/yazılabilir [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject