---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Android via Java API 參考文件
description: 提供控制匯出文件中註記與評論版面外觀的選項。
type: docs
url: /zh-hant/com.aspose.slides/notescommentslayoutingoptions/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)  
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

提供控制匯出文件中註記與評論版面外觀的選項。  
## Constructors

| Constructor | Description |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | 預設建構函式。 |
## Methods

| Method | Description |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | 取得或設定沒有作者的評論之可見性。 |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | 取得或設定沒有作者的評論之可見性。 |
| [getNotesPosition()](#getNotesPosition--) | 取得或設定頁面上註記的位置。 |
| [setNotesPosition(int value)](#setNotesPosition-int-) | 取得或設定頁面上註記的位置。 |
| [getCommentsPosition()](#getCommentsPosition--) | 取得或設定頁面上評論的位置。 |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | 取得或設定頁面上評論的位置。 |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | 取得或設定評論區域的顏色（僅在評論顯示於右側時套用）。 |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | 取得或設定評論區域的顏色（僅在評論顯示於右側時套用）。 |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | 取得或設定評論輸出區域的寬度（單位為像素，僅在評論顯示於右側時套用）。 |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | 取得或設定評論輸出區域的寬度（單位為像素，僅在評論顯示於右側時套用）。 |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

預設建構函式。

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

取得或設定沒有作者的評論之可見性。如果為 true，則會顯示評論。（僅在顯示評論時套用）

--------------------

預設值為 **false**。

**Returns:**  
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

取得或設定沒有作者的評論之可見性。如果為 true，則會顯示評論。（僅在顯示評論時套用）

--------------------

預設值為 **false**。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

取得或設定頁面上註記的位置。

--------------------

預設為 **NotesPositions.None**。

**Returns:**  
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

取得或設定頁面上註記的位置。

--------------------

預設為 **NotesPositions.None**。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

取得或設定頁面上評論的位置。

--------------------

預設為 **CommentsPositions.None**。

**Returns:**  
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

取得或設定頁面上評論的位置。

--------------------

預設為 **CommentsPositions.None**。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

取得或設定評論區域的顏色（僅在評論顯示於右側時套用）。

--------------------

預設為 **SkyBlue**。

**Returns:**  
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

取得或設定評論區域的顏色（僅在評論顯示於右側時套用）。

--------------------

預設為 **SkyBlue**。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

取得或設定評論輸出區域的寬度（單位為像素，僅在評論顯示於右側時套用）。

--------------------

最小值與預設值皆為 **150**。

**Returns:**  
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

取得或設定評論輸出區域的寬度（單位為像素，僅在評論顯示於右側時套用）。

--------------------

最小值與預設值皆為 **150**。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |