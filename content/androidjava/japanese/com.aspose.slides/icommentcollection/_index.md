---
title: ICommentCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: 1人の作者のコメントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/icommentcollection/
---
**実装されているインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

1人の作者のコメントのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | コレクションの末尾に新しいコメントを追加します。 |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | コレクションの末尾に新しいモダンコメントを追加します。 |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 指定されたインデックスに新しいコメントをコレクションへ挿入します。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 指定されたインデックスに新しいモダンコメントをコレクションへ挿入します。 |
| [toArray()](#toArray--) | すべてのコメントを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべてのコメントを含む配列を作成して返します。 |
| [removeAt(int index)](#removeAt-int-) | コレクション内の指定されたインデックスの要素を削除します。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | コレクション内の指定されたコメントの最初の出現を削除します。 |
| [clear()](#clear--) | コレクションからすべてのコメントを削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IComment](../../com.aspose.slides/icomment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

コレクションの末尾に新しいコメントを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しいコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいコメントを追加するプレゼンテーション内のスライド。 |
| position | android.graphics.PointF | 新しいコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | コメント作成時刻。 |

**戻り値:**
[IComment](../../com.aspose.slides/icomment) - 追加されたコメント。
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

コレクションの末尾に新しいモダンコメントを追加します。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しいモダンコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいモダンコメントを追加するプレゼンテーション内のスライド。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 新しいモダンコメントが関連付けられるスライド上のシェイプ。 |
| position | android.graphics.PointF | 新しいモダンコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | モダンコメント作成時刻。 |

**戻り値:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 追加されたモダンコメント。
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

指定されたインデックスに新しいコメントをコレクションへ挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コメントを挿入すべきコレクション内の要素のインデックス。 |
| text | java.lang.String | 新しいコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいコメントを追加するプレゼンテーション内のスライド。 |
| position | android.graphics.PointF | 新しいコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | コメント作成時刻。 |

**戻り値:**
[IComment](../../com.aspose.slides/icomment) - 挿入されたコメント。
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

指定されたインデックスに新しいモダンコメントをコレクションへ挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | モダンコメントを挿入すべきコレクション内の要素のインデックス。 |
| text | java.lang.String | 新しいモダンコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいモダンコメントを追加するプレゼンテーション内のスライド。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 新しいモダンコメントが関連付けられるスライド上のシェイプ。 |
| position | android.graphics.PointF | 新しいモダンコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | モダンコメント作成時刻。 |

**戻り値:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 挿入されたモダンコメント。
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

すべてのコメントを含む配列を作成し、返します。

**戻り値:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) の配列。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

指定された範囲のすべてのコメントを含む配列を作成し、返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 返す最初のコメントのインデックス。 |
| count | int | 返すコメントの数。 |

**戻り値:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) の配列。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクション内の指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

コレクション内の指定されたコメントの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | コレクションから削除するコメント。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのコメントを削除します。