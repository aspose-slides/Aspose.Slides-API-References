---
title: ModernComment
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: スライド上のコメントを表します。
type: docs
url: /ja/com.aspose.slides/moderncomment/
---
**継承:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

スライド上のコメントを表します。

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

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShape()](#getShape--) | コメントに関連付けられたshapeを返します。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の開始位置を取得または設定します。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の開始位置を取得または設定します。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の長さを取得または設定します。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の長さを取得または設定します。 |
| [getStatus()](#getStatus--) | コメントのステータスを取得または設定します。 |
| [setStatus(byte value)](#setStatus-byte-) | コメントのステータスを取得または設定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

コメントに関連付けられたshapeを返します。 読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の開始位置を取得または設定します。 読み書き int。

**戻り値:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の開始位置を取得または設定します。 読み書き int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の長さを取得または設定します。 読み書き int。

**戻り値:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

AutoShapeに関連付けられたコメントのテキストフレーム内のテキスト選択の長さを取得または設定します。 読み書き int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

コメントのステータスを取得または設定します。 読み書き [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**戻り値:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

コメントのステータスを取得または設定します。 読み書き [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject