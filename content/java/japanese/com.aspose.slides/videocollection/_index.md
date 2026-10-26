---
title: VideoCollection
second_title: Aspose.Slides for Java API リファレンス
description: Video オブジェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/videocollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェース:**  
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)  
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Video オブジェクトのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内のビデオファイルの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 別のプレゼンテーションからビデオファイルのコピーを追加します。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | ストリームからビデオを作成してプレゼンテーションに追加します。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | バイト配列からビデオを作成してプレゼンテーションに追加します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 指定されたインデックスから開始して、ビデオを指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |

### size() {#size--}
```
public final int size()
```

コレクション内のビデオファイルの数を返します。読み取り専用 int.

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IVideo](../../com.aspose.slides/ivideo).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo)

### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

別のプレゼンテーションからビデオファイルのコピーを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | ソースビデオ。 |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo) - 追加されたビデオ。

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

ストリームからビデオを作成してプレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ビデオファイルを追加するストリーム。 |
| loadingStreamBehavior | int | ストリームに適用される動作。 |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo) - 追加された [IVideo](../../com.aspose.slides/ivideo)。

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

バイト配列からビデオを作成してプレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| videoData | byte[] | ビデオバイト。 |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo) - 追加されたビデオ。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

指定されたインデックスから開始して、ビデオを指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 配列。 |
| index | int | インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期されているか（スレッドセーフ）を示す値を返します。読み取り専用 boolean.

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object.

**戻り値:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - コレクションを反復処理するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - コレクション全体の java.util.Iterator。