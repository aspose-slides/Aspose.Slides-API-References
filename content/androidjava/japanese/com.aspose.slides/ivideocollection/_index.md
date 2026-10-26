---
title: IVideoCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Video オブジェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ivideocollection/
---
**実装されたすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Video オブジェクトのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 別のプレゼンテーションからビデオ ファイルのコピーを追加します。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | ストリームからプレゼンテーションにビデオを作成して追加します。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | バイト配列からプレゼンテーションにビデオを作成して追加します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


指定されたインデックスの要素を取得します。 読み取り専用 [IVideo](../../com.aspose.slides/ivideo)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


別のプレゼンテーションからビデオ ファイルのコピーを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | ソース ビデオ。 |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo) - 追加されたビデオ。
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


ストリームからプレゼンテーションにビデオを作成して追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ビデオ ファイルを追加するストリーム。 |
| loadingStreamBehavior | int | ストリームに適用される挙動。 |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo) - 追加された [IVideo](../../com.aspose.slides/ivideo)。
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


バイト配列からプレゼンテーションにビデオを作成して追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| videoData | byte[] | ビデオ バイト列。 |

**戻り値:**
[IVideo](../../com.aspose.slides/ivideo) - 追加されたビデオ。