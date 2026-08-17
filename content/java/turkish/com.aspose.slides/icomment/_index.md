---
title: IComment
second_title: Aspose.Slides for Java API Referansı
description: Bir slayt üzerindeki yorumu temsil eder.
type: docs
url: /tr/com.aspose.slides/icomment/
---```
public interface IComment
```

Bir slayt üzerindeki yorumu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getText()](#getText--) | Bir slayt yorumunun düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir slayt yorumunun düz metnini alır veya ayarlar. |
| [getCreatedTime()](#getCreatedTime--) | Bir yorumun oluşturulma zamanını alır veya ayarlar. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Bir yorumun oluşturulma zamanını alır veya ayarlar. |
| [getSlide()](#getSlide--) | Bir yorumun ana slaydını alır veya ayarlar. |
| [getAuthor()](#getAuthor--) | Bir yorumun yazarını alır. |
| [getPosition()](#getPosition--) | Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. |
| [remove()](#remove--) | Yorumu ve tüm yanıtlarını ana koleksiyondan kaldırır. |
| [getParentComment()](#getParentComment--) | Ana yorumu alır veya ayarlar. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Ana yorumu alır veya ayarlar. |
### getText() {#getText--}
```
public abstract String getText()
```

Bir slayt yorumunun düz metnini alır veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Bir slayt yorumunun düz metnini alır veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Bir yorumun oluşturulma zamanını alır veya ayarlar. Bu özelliği java.util.Date(Long.MIN_VALUE) olarak ayarlamak, yorum zamanının ayarlanmadığını belirtir. Okunur/Yazılır java.util.Date.

--------------------

Yorum zamanı isteğe bağlı bir parametredir.

**Döndürür:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Bir yorumun oluşturulma zamanını alır veya ayarlar. Bu özelliği java.util.Date(Long.MIN_VALUE) olarak ayarlamak, yorum zamanının ayarlanmadığını belirtir. Okunur/Yazılır java.util.Date.

--------------------

Yorum zamanı isteğe bağlı bir parametredir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Bir yorumun ana slaydını alır veya ayarlar. Salt okunur [ISlide](../../com.aspose.slides/islide).

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Bir yorumun yazarını alır. Salt okunur [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Döndürür:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. Okunur/Yazılır java.awt.geom.Point2D.Float.

**Döndürür:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. Okunur/Yazılır java.awt.geom.Point2D.Float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public abstract void remove()
```

Yorumu ve tüm yanıtlarını ana koleksiyondan kaldırır.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Ana yorumu alır veya ayarlar. Okunur/Yazılır [IComment](../../com.aspose.slides/icomment).

**Döndürür:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Ana yorumu alır veya ayarlar. Okunur/Yazılır [IComment](../../com.aspose.slides/icomment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |
