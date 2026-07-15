---
title: ModernComment
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片中的註解。
type: docs
url: /zh-hant/com.aspose.slides/moderncomment/
---
**繼承:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**已實作的介面:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

表示投影片中的註解。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 方法

| Method | Description |
| --- | --- |
| [getShape()](#getShape--) | 傳回與註解相關聯的形狀。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | 取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的起始位置。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的起始位置。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | 取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的長度。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的長度。 |
| [getStatus()](#getStatus--) | 取得或設定註解的狀態。 |
| [setStatus(byte value)](#setStatus-byte-) | 取得或設定註解的狀態。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

傳回與註解相關聯的形狀。唯讀 [IShape](../../com.aspose.slides/ishape)。

**傳回:**  
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的起始位置。可讀寫 int。

**傳回:**  
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的起始位置。可讀寫 int。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的長度。可讀寫 int。

**傳回:**  
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

取得或設定如果註解與 AutoShape 關聯時，文字框中文字選取的長度。可讀寫 int。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

取得或設定註解的狀態。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**傳回:**  
byte

### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

取得或設定註解的狀態。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**  
com.aspose.slides.IDOMObject