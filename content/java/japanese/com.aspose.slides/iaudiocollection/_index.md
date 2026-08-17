---
title: IAudioCollection
second_title: Aspose.Slides for Java API リファレンス
description: 埋め込みオーディオ ファイルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/iaudiocollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

埋め込みオーディオ ファイルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 別のプレゼンテーションからオーディオ ファイルのコピーを追加します。 |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | ストリームからプレゼンテーションにオーディオを作成して追加します。 |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | ストリームからプレゼンテーションにオーディオを作成して追加します。 |
| [addAudio(byte[] audioData)](#addAudio-byte---) | バイト配列からプレゼンテーションにオーディオを作成して追加します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IAudio](../../com.aspose.slides/iaudio)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

別のプレゼンテーションからオーディオ ファイルのコピーを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | ソース オーディオ。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

ストリームからプレゼンテーションにオーディオを作成して追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | オーディオを追加するストリーム。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

ストリームからプレゼンテーションにオーディオを作成して追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ビデオ オーディオを追加するストリーム。 |
| loadingStreamBehavior | int | ストリームに適用される [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior)。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

バイト配列からプレゼンテーションにオーディオを作成して追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| audioData | byte[] | オーディオ バイト。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。