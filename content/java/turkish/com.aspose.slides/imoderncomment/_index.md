---
title: IModernComment
second_title: Aspose.Slides for Java API Referansı
description: Bir slayttaki yorumu temsil eder.
type: docs
url: /tr/com.aspose.slides/imoderncomment/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Bir slayt üzerindeki yorumu temsil eder.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShape()](#getShape--) | Yoruma bağlı bir şekil döndürür. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin başlangıç konumunu döndürür veya ayarlar. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin başlangıç konumunu döndürür veya ayarlar. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin uzunluğunu döndürür veya ayarlar. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin uzunluğunu döndürür veya ayarlar. |
| [getStatus()](#getStatus--) | Yorumuun durumunu döndürür veya ayarlar. |
| [setStatus(byte value)](#setStatus-byte-) | Yorumuun durumunu döndürür veya ayarlar. |

### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Yoruma bağlı bir şekil döndürür. Sadece okuma [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin başlangıç konumunu döndürür veya ayarlar. Okuma/Yazma int.

**Döndürür:**
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin başlangıç konumunu döndürür veya ayarlar. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin uzunluğunu döndürür veya ayarlar. Okuma/Yazma int.

**Döndürür:**
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Yorum AutoShape ile ilişkiliyse, metin çerçevesindeki metin seçiminin uzunluğunu döndürür veya ayarlar. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Yorumuun durumunu döndürür veya ayarlar. Okuma/Yazma [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Döndürür:**
byte

### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Yorumuun durumunu döndürür veya ayarlar. Okuma/Yazma [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |