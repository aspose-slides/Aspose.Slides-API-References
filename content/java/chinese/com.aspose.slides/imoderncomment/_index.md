---
title: IModernComment
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片上的注释。
type: docs
url: /zh/com.aspose.slides/imoderncomment/
---
**已实现的接口:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

表示幻灯片上的注释。

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

| 方法 | 描述 |
| --- | --- |
| [getShape()](#getShape--) | 返回与该注释关联的形状。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | 返回或设置与 AutoShape 关联的注释在文本框中选择的起始位置。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 返回或设置与 AutoShape 关联的注释在文本框中选择的起始位置。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | 返回或设置与 AutoShape 关联的注释在文本框中选择的长度。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 返回或设置与 AutoShape 关联的注释在文本框中选择的长度。 |
| [getStatus()](#getStatus--) | 返回或设置注释的状态。 |
| [setStatus(byte value)](#setStatus-byte-) | 返回或设置注释的状态。 |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

返回与该注释关联的形状。只读 [IShape](../../com.aspose.slides/ishape)。

**返回:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

返回或设置与 AutoShape 关联的注释在文本框中选择的起始位置。可读写 int。

**返回:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

返回或设置与 AutoShape 关联的注释在文本框中选择的起始位置。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

返回或设置与 AutoShape 关联的注释在文本框中选择的长度。可读写 int。

**返回:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

返回或设置与 AutoShape 关联的注释在文本框中选择的长度。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

返回或设置注释的状态。可读写 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**返回:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

返回或设置注释的状态。可读写 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |