---
title: IModernComment
second_title: Aspose.Slides for Java API 參考文件
description: 表示投影片上的註解。
type: docs
url: /zh-hant/com.aspose.slides/imoderncomment/
---
**所有已實作的介面：**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
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

| Method | Description |
| --- | --- |
| [getShape()](#getShape--) | 返回與註解相關聯的 shape。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | 返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | 返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的長度。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的長度。 |
| [getStatus()](#getStatus--) | 返回或設定註解的 status。 |
| [setStatus(byte value)](#setStatus-byte-) | 返回或設定註解的 status。 |

### getShape() {#getShape--}
```
public abstract IShape getShape()
```

返回與註解相關聯的 shape。唯讀 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。可讀寫 int。

**返回：**
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。可讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的長度。可讀寫 int。

**返回：**
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

返回或設定如果註解與 AutoShape 相關聯時，文字框中文字選取的長度。可讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

返回或設定註解的 status。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**返回：**
byte

### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

返回或設定註解的 status。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |