---
title: ModernComment
second_title: Aspose.Slides for Java API リファレンス
description: スライド上のコメントを表します。
type: docs
url: /ja/com.aspose.slides/moderncomment/
---
**継承:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**実装されたすべてのインターフェイス:**
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
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
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
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | コメントが AutoSpace に関連付けられている場合、テキストフレーム内のテキスト選択の長さを取得または設定します。 |
| [getStatus()](#getStatus--) | コメントのステータスを取得または設定します。 |
| [setStatus(byte value)](#setStatus-byte-) | コメントのステータスを取得または設定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

コメントに関連付けられたシェイプを返します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の開始位置を取得または設定します。読み取り/書き込み int。

**戻り値:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の開始位置を取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の長さを取得または設定します。読み取り/書き込み int。

**戻り値:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

コメントが AutoShape に関連付けられている場合、テキストフレーム内のテキスト選択の長さを取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

コメントのステータスを取得または設定します。読み取り/書き込み [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**戻り値:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

コメントのステータスを取得または設定します。読み取り/書き込み [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject