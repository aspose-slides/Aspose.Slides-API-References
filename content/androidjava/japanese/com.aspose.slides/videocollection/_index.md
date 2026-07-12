---
title: VideoCollection
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: Video オブジェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/videocollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Video オブジェクトのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内のビデオ ファイルの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 別のプレゼンテーションからビデオ ファイルのコピーを追加します。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | ストリームからビデオを作成してプレゼンテーションに追加します。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | バイト配列からビデオを作成してプレゼンテーションに追加します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 指定されたインデックスから始めて、ビデオを指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか (スレッドセーフ) を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
| [iterator()](#iterator--) | コレクションを列挙する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
### size() {#size--}
```
public final int size()
```


コレクション内のビデオ ファイルの数を返します。 読み取り専用 int.

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


指定されたインデックスの要素を取得します。 読み取り専用 [IVideo](../../com.aspose.slides/ivideo).

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


別のプレゼンテーションからビデオ ファイルのコピーを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | ソース ビデオ。 |

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
| stream | java.io.InputStream | ビデオ ファイルを追加するストリーム。 |
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
| videoData | byte[] | ビデオ バイト。 |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo) - 追加されたビデオ。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


指定されたインデックスから始めて、ビデオを指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 配列。 |
| index | int | インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期化されているか (スレッドセーフ) を示す値を返します。 読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期化ルートを返します。 読み取り専用 Object。

**戻り値:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


コレクションを列挙する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - コレクション全体の java.util.Iterator。