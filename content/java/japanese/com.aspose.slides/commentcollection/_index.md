---
title: CommentCollection
second_title: Aspose.Slides for Java API リファレンス
description: 1人の作者のコメントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/commentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

1人の作者のコメントコレクションを表します。  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | コレクションの末尾に新しいコメントを追加します。 |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | コレクションの末尾に新しいモダンコメントを追加します。 |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 指定されたインデックスに新しいコメントをコレクションに挿入します。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 指定されたインデックスに新しいモダンコメントをコレクションに挿入します。 |
| [toArray()](#toArray--) | すべてのコメントを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべてのコメントを含む配列を作成して返します。 |
| [removeAt(int index)](#removeAt-int-) | コレクション内の指定されたインデックスの要素を削除します。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | コレクション内の指定されたコメントの最初の出現を削除します。 |
| [clear()](#clear--) | コレクションからすべてのコメントを削除します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | インデックスでコレクション内のコメントを検索します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
### size() {#size--}
```
public final int size()
```


コレクションに実際に含まれる要素数を取得します。 読み取り専用  int .

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```


指定されたインデックスの要素を取得します。 読み取り専用 [Comment](../../com.aspose.slides/comment).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


コレクションの末尾に新しいコメントを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しいコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいコメントを追加するプレゼンテーション内のスライド。 |
| position | java.awt.geom.Point2D.Float | 新しいコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | コメントの作成時刻。 |

**戻り値:**
[IComment](../../com.aspose.slides/icomment) - 追加されたコメント。
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


コレクションの末尾に新しいモダンコメントを追加します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しいモダンコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいモダンコメントを追加するプレゼンテーション内のスライド。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 新しいモダンコメントが関連付けられるスライド上のシェイプ。 |
| position | java.awt.geom.Point2D.Float | 新しいモダンコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | モダンコメントの作成時刻。 |

**戻り値:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 追加されたモダンコメント。
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


指定されたインデックスに新しいコメントをコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コメントを挿入すべきコレクション内の要素インデックス。 |
| text | java.lang.String | 新しいコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいコメントを追加するプレゼンテーション内のスライド。 |
| position | java.awt.geom.Point2D.Float | 新しいコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | コメントの作成時刻。 |

**戻り値:**
[IComment](../../com.aspose.slides/icomment) - 挿入されたコメント。
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


指定されたインデックスに新しいモダンコメントをコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | モダンコメントを挿入すべきコレクション内の要素インデックス。 |
| text | java.lang.String | 新しいモダンコメントのプレーンテキスト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 新しいモダンコメントを追加するプレゼンテーション内のスライド。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 新しいモダンコメントが関連付けられるスライド上のシェイプ。 |
| position | java.awt.geom.Point2D.Float | 新しいモダンコメントを追加するスライド上の位置。 |
| creationTime | java.util.Date | モダンコメントの作成時刻。 |

**戻り値:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 挿入されたモダンコメント。
### toArray() {#toArray--}
```
public final IComment[] toArray()
```


すべてのコメントを含む配列を作成して返します。

**戻り値:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) の配列。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```


指定された範囲のすべてのコメントを含む配列を作成して返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 返す最初のコメントのインデックス。 |
| count | int | 返すコメントの数。 |

**戻り値:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) の配列。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


コレクション内の指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```


コレクション内の指定されたコメントの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | コレクションから削除するコメント。 |
### clear() {#clear--}
```
public final void clear()
```


コレクションからすべてのコメントを削除します。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```


コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - コレクション全体の java.util.Iterator。
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```


インデックスでコレクション内のコメントを検索します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| idx | int | 検索するコメントのユニークインデックス  int 。 |

**戻り値:**
[IComment](../../com.aspose.slides/icomment) - 見つかったコメントまたは null [IComment](../../com.aspose.slides/icomment)。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目的配列。 |
| index | int | 目的配列の開始インデックス。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 読み取り専用  boolean .

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期ルートを返します。 読み取り専用  Object .

**戻り値:**
java.lang.Object