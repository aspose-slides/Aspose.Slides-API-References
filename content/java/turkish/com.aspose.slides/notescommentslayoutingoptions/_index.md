---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Java API Referansı
description: Dışa aktarılan belgedeki notların ve yorumların düzen görünümünü kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/notescommentslayoutingoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

İhrac edilen belgede notların ve yorumların düzen görünümünü kontrol eden seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Varsayılan yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Yazarı olmayan yorumların görünürlüğünü alır ve ayarlar. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Yazarı olmayan yorumların görünürlüğünü alır ve ayarlar. |
| [getNotesPosition()](#getNotesPosition--) | Sayfadaki notların konumunu alır ve ayarlar. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Sayfadaki notların konumunu alır ve ayarlar. |
| [getCommentsPosition()](#getCommentsPosition--) | Sayfadaki yorumların konumunu alır ve ayarlar. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Sayfadaki yorumların konumunu alır ve ayarlar. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Yorum alanının rengini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Yorum alanının rengini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Yorum çıktısı alanının piksel cinsinden genişliğini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Yorum çıktısı alanının piksel cinsinden genişliğini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Varsayılan yapıcı.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Yazarı olmayan yorumların görünürlüğünü alır ve ayarlar. True ise yorumlar görüntülenir. (Yorumlar gösterildiğinde uygulanır).

--------------------

Varsayılan değer **false**.

**Döndürür:**  
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Yazarı olmayan yorumların görünürlüğünü alır ve ayarlar. True ise yorumlar görüntülenir. (Yorumlar gösterildiğinde uygulanır).

--------------------

Varsayılan değer **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Sayfadaki notların konumunu alır ve ayarlar.

--------------------

Varsayılan **NotesPositions.None**.

**Döndürür:**  
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Sayfadaki notların konumunu alır ve ayarlar.

--------------------

Varsayılan **NotesPositions.None**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Sayfadaki yorumların konumunu alır ve ayarlar.

--------------------

Varsayılan **CommentsPositions.None**.

**Döndürür:**  
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Sayfadaki yorumların konumunu alır ve ayarlar.

--------------------

Varsayılan **CommentsPositions.None**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

Yorum alanının rengini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır).

--------------------

Varsayılan **Color.SkyBlue**.

**Döndürür:**  
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

Yorum alanının rengini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır).

--------------------

Varsayılan **Color.SkyBlue**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Color |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Yorum çıktısı alanının piksel cinsinden genişliğini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır).

--------------------

Minimum ve varsayılan değer **150**.

**Döndürür:**  
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Yorum çıktısı alanının piksel cinsinden genişliğini alır ve ayarlar (Yorumlar sağda gösterildiğinde uygulanır).

--------------------

Minimum ve varsayılan değer **150**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |