---
title: IModernComment
second_title: Aspose.Slides for Android via Java API 參考
description: 表示投影片上的註解。
type: docs
url: /zh-hant/com.aspose.slides/imoderncomment/
---
**已實作的所有介面：**
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
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getShape()](#getShape--) | 傳回與註解關聯的形狀。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | 傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | 傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的長度。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的長度。 |
| [getStatus()](#getStatus--) | 傳回或設定註解的狀態。 |
| [setStatus(byte value)](#setStatus-byte-) | 傳回或設定註解的狀態。 |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


傳回與註解關聯的形狀。唯讀 [IShape](../../com.aspose.slides/ishape)。

**回傳：**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。可讀寫 int。

**回傳：**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的起始位置。可讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的長度。可讀寫 int。

**回傳：**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


傳回或設定若註解與 AutoShape 相關聯時，文字框中文字選取的長度。可讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


傳回或設定註解的狀態。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**回傳：**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


傳回或設定註解的狀態。可讀寫 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |