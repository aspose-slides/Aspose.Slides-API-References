---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Java API 參考
description: 提供控制匯出文件中註解與備註版面外觀的選項。
type: docs
url: /zh-hant/com.aspose.slides/notescommentslayoutingoptions/
---
**繼承關係：**
java.lang.Object

**全部已實作的介面：**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

提供控制匯出文件中註解與備註版面外觀的選項。
## 建構式

| 建構式 | 說明 |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | 預設建構式。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | 取得或設定沒有作者的註解之可見性。 |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | 取得或設定沒有作者的註解之可見性。 |
| [getNotesPosition()](#getNotesPosition--) | 取得或設定頁面上備註的位置。 |
| [setNotesPosition(int value)](#setNotesPosition-int-) | 取得或設定頁面上備註的位置。 |
| [getCommentsPosition()](#getCommentsPosition--) | 取得或設定頁面上註解的位置。 |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | 取得或設定頁面上註解的位置。 |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | 取得或設定註解區域的顏色（僅在註解顯示於右側時套用）。 |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | 取得或設定註解區域的顏色（僅在註解顯示於右側時套用）。 |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | 取得或設定註解輸出區域的寬度（像素）（僅在註解顯示於右側時套用）。 |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | 取得或設定註解輸出區域的寬度（像素）（僅在註解顯示於右側時套用）。 |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

預設建構式。

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

取得或設定沒有作者的註解之可見性。若為 true 則會顯示註解。（僅在註解顯示時套用）

--------------------

預設值為 **false**。

**返回值：**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

取得或設定沒有作者的註解之可見性。若為 true 則會顯示註解。（僅在註解顯示時套用）

--------------------

預設值為 **false**。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

取得或設定頁面上備註的位置。

--------------------

預設為 **NotesPositions.None**。

**返回值：**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

取得或設定頁面上備註的位置。

--------------------

預設為 **NotesPositions.None**。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

取得或設定頁面上註解的位置。

--------------------

預設為 **CommentsPositions.None**。

**返回值：**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

取得或設定頁面上註解的位置。

--------------------

預設為 **CommentsPositions.None**。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

取得或設定註解區域的顏色（僅在註解顯示於右側時套用）。

--------------------

預設為 **Color.SkyBlue**。

**返回值：**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

取得或設定註解區域的顏色（僅在註解顯示於右側時套用）。

--------------------

預設為 **Color.SkyBlue**。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

取得或設定註解輸出區域的寬度（像素）（僅在註解顯示於右側時套用）。

--------------------

最小值與預設值皆為 **150**。

**返回值：**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

取得或設定註解輸出區域的寬度（像素）（僅在註解顯示於右側時套用）。

--------------------

最小值與預設值皆為 **150**。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |