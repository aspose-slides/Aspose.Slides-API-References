---
title: IModernComment
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: スライド上のコメントを表します。
type: docs
url: /ja/com.aspose.slides/imoderncomment/
---
**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
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
| [getShape()](#getShape--) | コメントに関連付けられたシェイプを返します。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の開始位置を取得または設定します。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の開始位置を取得または設定します。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の長さを取得または設定します。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の長さを取得または設定します。 |
| [getStatus()](#getStatus--) | コメントのステータスを取得または設定します。 |
| [setStatus(byte value)](#setStatus-byte-) | コメントのステータスを取得または設定します。 |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

コメントに関連付けられたシェイプを返します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の開始位置を取得または設定します。読み書き可能 int。

**戻り値:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の開始位置を取得または設定します。読み書き可能 int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の長さを取得または設定します。読み書き可能 int。

**戻り値:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の長さを取得または設定します。読み書き可能 int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

コメントのステータスを取得または設定します。読み書き可能 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**戻り値:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

コメントのステータスを取得または設定します。読み書き可能 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |