---
title: AudioCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 埋め込みオーディオ ファイルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/audiocollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているインターフェイス:**  
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)  
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

埋め込みオーディオ ファイルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内のオーディオ ファイルの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 別のプレゼンテーションからオーディオ ファイルのコピーを追加します。 |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | ストリームからプレゼンテーションにオーディオを作成して追加します。 |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | ストリームからプレゼンテーションにオーディオを作成して追加します。 |
| [addAudio(byte[] audioData)](#addAudio-byte---) | バイト配列からプレゼンテーションにオーディオを作成して追加します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 指定されたインデックスから開始して、指定された配列にオーディオをコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
### size() {#size--}
```
public final int size()
```

コレクション内のオーディオ ファイルの数を返します。読み取り専用 int.

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IAudio](../../com.aspose.slides/iaudio)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

別のプレゼンテーションからオーディオ ファイルのコピーを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | ソースオーディオ。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

ストリームからプレゼンテーションにオーディオを作成して追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | オーディオを追加するストリーム。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

ストリームからプレゼンテーションにオーディオを作成して追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | オーディオを追加するストリーム。 |
| loadingStreamBehavior | int | ストリームに適用される動作。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

バイト配列からプレゼンテーションにオーディオを作成して追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| audioData | byte[] | オーディオ バイト。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

指定されたインデックスから開始して、指定された配列にオーディオをコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 配列。 |
| index | int | インデックス。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - コレクションを反復処理するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

コレクション全体の Java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - コレクション全体の java.util.Iterator。