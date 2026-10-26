---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Android için Java API Referansı
description: Dışa aktarılan belgede notların ve yorumların yerleşim görünümünü kontrol eden seçenekler sağlar.
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

Dışa aktarılan belgede notların ve yorumların yerleşim görünümünü kontrol eden seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Varsayılan yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Yazar olmayan yorumların görünürlüğünü alır veya ayarlar. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Yazar olmayan yorumların görünürlüğünü alır veya ayarlar. |
| [getNotesPosition()](#getNotesPosition--) | Sayfadaki notların konumunu alır veya ayarlar. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Sayfadaki notların konumunu alır veya ayarlar. |
| [getCommentsPosition()](#getCommentsPosition--) | Sayfadaki yorumların konumunu alır veya ayarlar. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Sayfadaki yorumların konumunu alır veya ayarlar. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Yorum alanının rengini alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Yorum alanının rengini alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Yorum çıkış alanının genişliğini piksel olarak alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Yorum çıkış alanının genişliğini piksel olarak alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Varsayılan yapıcı.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Yazar olmayan yorumların görünürlüğünü alır veya ayarlar. Değer true ise yorumlar görüntülenir. (Yorumlar görüntülendiğinde uygulanır).

--------------------

Varsayılan değer **false**dır.

**Döndürür:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Yazar olmayan yorumların görünürlüğünü alır veya ayarlar. Değer true ise yorumlar görüntülenir. (Yorumlar görüntülendiğinde uygulanır).

--------------------

Varsayılan değer **false**dır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Sayfadaki notların konumunu alır veya ayarlar.

--------------------

Varsayılan **NotesPositions.None** değeridir.

**Döndürür:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Sayfadaki notların konumunu alır veya ayarlar.

--------------------

Varsayılan **NotesPositions.None** değeridir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Sayfadaki yorumların konumunu alır veya ayarlar.

--------------------

Varsayılan **CommentsPositions.None** değeridir.

**Döndürür:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Sayfadaki yorumların konumunu alır veya ayarlar.

--------------------

Varsayılan **CommentsPositions.None** değeridir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


Yorum alanının rengini alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır).

--------------------

Varsayılan **SkyBlue**.

**Döndürür:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


Yorum alanının rengini alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır).

--------------------

Varsayılan **SkyBlue**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Yorum çıkış alanının genişliğini piksel olarak alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır).

--------------------

Minimum ve varsayılan değer **150**'dir.

**Döndürür:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Yorum çıkış alanının genişliğini piksel olarak alır veya ayarlar (Yorumlar sağda görüntülendiğinde uygulanır).

--------------------

Minimum ve varsayılan değer **150**'dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |