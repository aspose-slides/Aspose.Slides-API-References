---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Java API 参考
description: 提供用于控制导出文档中备注和注释布局外观的选项。
type: docs
url: /zh/com.aspose.slides/notescommentslayoutingoptions/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

提供用于控制导出文档中备注和注释布局外观的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | 默认构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | 获取或设置没有作者的注释的可见性。 |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | 获取或设置没有作者的注释的可见性。 |
| [getNotesPosition()](#getNotesPosition--) | 获取或设置页面上备注的位置。 |
| [setNotesPosition(int value)](#setNotesPosition-int-) | 获取或设置页面上备注的位置。 |
| [getCommentsPosition()](#getCommentsPosition--) | 获取或设置页面上注释的位置。 |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | 获取或设置页面上注释的位置。 |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | 获取或设置注释区域的颜色（仅在注释显示在右侧时适用）。 |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | 获取或设置注释区域的颜色（仅在注释显示在右侧时适用）。 |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | 获取或设置注释输出区域的宽度（像素）（仅在注释显示在右侧时适用）。 |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | 获取或设置注释输出区域的宽度（像素）（仅在注释显示在右侧时适用）。 |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

默认构造函数。

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

获取或设置没有作者的注释的可见性。如果为 true，则显示注释。（仅在显示注释时适用）

--------------------

默认值为 **false**。

**返回值：**
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

获取或设置没有作者的注释的可见性。如果为 true，则显示注释。（仅在显示注释时适用）

--------------------

默认值为 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

获取或设置页面上备注的位置。

--------------------

默认值为 **NotesPositions.None**。

**返回值：**
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

获取或设置页面上备注的位置。

--------------------

默认值为 **NotesPositions.None**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

获取或设置页面上注释的位置。

--------------------

默认值为 **CommentsPositions.None**。

**返回值：**
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

获取或设置页面上注释的位置。

--------------------

默认值为 **CommentsPositions.None**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

获取或设置注释区域的颜色（仅在注释显示在右侧时适用）。

--------------------

默认值为 **Color.SkyBlue**。

**返回值：**
java.awt.Color

### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

获取或设置注释区域的颜色（仅在注释显示在右侧时适用）。

--------------------

默认值为 **Color.SkyBlue**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

获取或设置注释输出区域的宽度（像素）（仅在注释显示在右侧时适用）。

--------------------

最小值和默认值为 **150**。

**返回值：**
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

获取或设置注释输出区域的宽度（像素）（仅在注释显示在右侧时适用）。

--------------------

最小值和默认值为 **150**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |