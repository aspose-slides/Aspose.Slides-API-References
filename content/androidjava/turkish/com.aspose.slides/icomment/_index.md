---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Bir slayttaki yorumu temsil eder.
type: docs
url: /tr/com.aspose.slides/icomment/
---```
public interface IComment
```

Bir slayttaki yorumu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getText()](#getText--) | Bir slayt yorumunun düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir slayt yorumunun düz metnini alır veya ayarlar. |
| [getCreatedTime()](#getCreatedTime--) | Bir yorumun oluşturulma zamanını alır veya ayarlar. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Bir yorumun oluşturulma zamanını alır veya ayarlar. |
| [getSlide()](#getSlide--) | Bir yorumun üst slaydını alır veya ayarlar. |
| [getAuthor()](#getAuthor--) | Bir yorumun yazarını alır. |
| [getPosition()](#getPosition--) | Bir slayttaki yorumun konumunu alır veya ayarlar. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Bir slayttaki yorumun konumunu alır veya ayarlar. |
| [remove()](#remove--) | Yorumu ve tüm yanıtlarını üst koleksiyondan kaldırır. |
| [getParentComment()](#getParentComment--) | Üst yorumu alır veya ayarlar. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Üst yorumu alır veya ayarlar. |
### getText() {#getText--}
```
public abstract String getText()
```

Bir slayt yorumunun düz metnini alır veya ayarlar. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Bir slayt yorumunun düz metnini alır veya ayarlar. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Bir yorumun oluşturulma zamanını alır veya ayarlar. Bu özelliği java.util.Date(Long.MIN_VALUE) olarak ayarlamak, yorum zamanının ayarlanmadığını gösterir. Okunur/yazılır java.util.Date.

--------------------

Yorum zamanı isteğe bağlı bir parametredir.

**Döndürür:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Bir yorumun oluşturulma zamanını alır veya ayarlar. Bu özelliği java.util.Date(Long.MIN_VALUE) olarak ayarlamak, yorum zamanının ayarlanmadığını gösterir. Okunur/yazılır java.util.Date.

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

Bir yorumun üst slaydını alır veya ayarlar. Sadece okunabilir [ISlide](../../com.aspose.slides/islide).

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Bir yorumun yazarını alır. Sadece okunabilir [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Döndürür:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Bir slayttaki yorumun konumunu alır veya ayarlar. Okunur/yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Bir slayttaki yorumun konumunu alır veya ayarlar. Okunur/yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

Yorumu ve tüm yanıtlarını üst koleksiyondan kaldırır.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Üst yorumu alır veya ayarlar. Okunur/yazılır [IComment](../../com.aspose.slides/icomment).

**Döndürür:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Üst yorumu alır veya ayarlar. Okunur/yazılır [IComment](../../com.aspose.slides/icomment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |