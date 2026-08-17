---
title: Video
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションに埋め込まれた画像を表します。
type: docs
url: /ja/com.aspose.slides/video/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

プレゼンテーションに埋め込まれた画像を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContentType()](#getContentType--) | ビデオの MIME タイプを返します（\#getBinaryData.getBinaryData でエンコード）。 |
| [getBinaryData()](#getBinaryData--) | オーディオ データのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用の Stream を返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

ビデオの MIME タイプを返します（\#getBinaryData.getBinaryData でエンコード）。 読み取り専用 String。

**戻り値:**
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

オーディオ データのコピーを返します。 データ量が多い場合は、ビデオ データをメモリに不要に読み込むことや OutOfMemoryException を防ぐために、\#getStream.getStream メソッドの使用を検討してください。 読み取り専用 byte[]。

**戻り値:**
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

読み取り用の Stream を返します。 使用後は `using` を利用するか、ストリームを閉じてください。

**戻り値:**
java.io.InputStream - 読み取り用の Stream。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject