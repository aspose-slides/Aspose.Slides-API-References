---
title: IAudioCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 埋め込みオーディオファイルのコレクションを表します。
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
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | ストリームからオーディオを作成し、プレゼンテーションに追加します。 |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | ストリームからオーディオを作成し、プレゼンテーションに追加します。 |
| [addAudio(byte[] audioData)](#addAudio-byte---) | バイト配列からオーディオを作成し、プレゼンテーションに追加します。 |
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
| audio | [IAudio](../../com.aspose.slides/iaudio) | ソースオーディオ。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

ストリームからオーディオを作成し、プレゼンテーションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | オーディオを追加するためのストリーム。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

ストリームからオーディオを作成し、プレゼンテーションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ビデオオーディオを追加するためのストリーム。 |
| loadingStreamBehavior | int | ストリームに適用される[LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior)。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

バイト配列からオーディオを作成し、プレゼンテーションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| audioData | byte[] | オーディオバイト。 |

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio) - 追加されたオーディオ。