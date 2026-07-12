---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /ja/com.aspose.slides/ivideo/
---```
public interface IVideo
```

プレゼンテーションに埋め込まれたビデオを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContentType()](#getContentType--) | ビデオの MIME タイプを返します。 (\#getBinaryData.getBinaryData) でエンコードされています。 |
| [getBinaryData()](#getBinaryData--) | オーディオ データのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用の Stream ストリームを返します。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

ビデオの MIME タイプを返します。 (\#getBinaryData.getBinaryData) でエンコードされています。 読み取り専用 String。

**戻り値:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

オーディオ データのコピーを返します。大量のデータの場合は、\#getStream.getStream メソッドの使用を検討してください。ビデオのデータをメモリに不要に読み込んだり、OutOfMemoryException が発生したりしないようにするためです。 読み取り専用 byte[]。

**戻り値:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

読み取り用の Stream ストリームを返します。使用後は 'using' を使用するか、ストリームを閉じてください。

**戻り値:**
java.io.InputStream - 読み取り用のストリーム.