---
title: Video
second_title: Java API リファレンスによる Android 用 Aspose.Slides
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
| [getContentType()](#getContentType--) | (\#getBinaryData.getBinaryData)でエンコードされたビデオのMIMEタイプを返します。 |
| [getBinaryData()](#getBinaryData--) | オーディオデータのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用のStreamストリームを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


(\#getBinaryData.getBinaryData)でエンコードされたビデオのMIMEタイプを返します。 読み取り専用 String.

**戻り値:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


オーディオデータのコピーを返します。 大量のデータの場合は、ビデオのデータをメモリに不要に読み込んだりOutOfMemoryExceptionが発生したりしないように、\#getStream.getStreamメソッドの使用を検討してください。 読み取り専用 byte[].

**戻り値:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


読み取り用のStreamストリームを返します。 使用後は 'using' を使用するか、ストリームを閉じてください。

**戻り値:**
java.io.InputStream - 読み取り用ストリーム。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediateオブジェクトを返します。 読み取り専用 IDOMObject.

**戻り値:**
com.aspose.slides.IDOMObject