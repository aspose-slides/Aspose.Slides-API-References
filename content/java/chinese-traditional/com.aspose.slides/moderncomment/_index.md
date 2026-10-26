---
title: ModernComment
second_title: Aspose.Slides for Java API 參考
description: 表示投影片上的註解。
type: docs
url: /zh-hant/com.aspose.slides/moderncomment/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**所有已實作的介面：**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

表示投影片上的註解。

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
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShape()](#getShape--) | 傳回與註解相關聯的 shape。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | 取得或設定文字選取在文字框中的起始位置（若註解與 AutoShape 相關聯）。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 取得或設定文字選取在文字框中的起始位置（若註解與 AutoShape 相關聯）。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | 取得或設定文字選取在文字框中的長度（若註解與 AutoShape 相關聯）。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 取得或設定文字選取在文字框中的長度（若註解與 AutoShape 相關聯）。 |
| [getStatus()](#getStatus--) | 取得或設定註解的狀態。 |
| [setStatus(byte value)](#setStatus-byte-) | 取得或設定註解的狀態。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

傳回與註解相關聯的 shape。唯讀 [IShape](../../com.aspose.slides/ishape)。

**回傳：**
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

取得或設定文字選取在文字框中的起始位置（若註解與 AutoShape 相關聯）。可讀寫 int。

**回傳：**
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

取得或設定文字選取在文字框中的起始位置（若註解與 AutoShape 相關聯）。可讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

取得或設定文字選取在文字框中的長度（若註解與 AutoShape 相關聯）。可讀寫 int。

**回傳：**
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

取得或設定文字選取在文字框中的長度（若註解與 AutoShape 相關聯）。可讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

取得或設定註解的狀態。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**回傳：**
byte

### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

取得或設定註解的狀態。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳：**
com.aspose.slides.IDOMObject