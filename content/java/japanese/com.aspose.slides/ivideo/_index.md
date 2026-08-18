---
title: IVideo
second_title: Aspose.Slides の Java API リファレンス
description: プレゼンテーションに埋め込まれたビデオを表します。
type: docs
url: /ja/com.aspose.slides/ivideo/
---```
public interface IVideo
```

プレゼンテーションに埋め込まれたビデオを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | ビデオの MIME タイプを返します（\#getBinaryData.getBinaryData でエンコード）。 |
| [getBinaryData()](#getBinaryData--) | オーディオ データのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用の Stream ストリームを返します。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


ビデオの MIME タイプを返します（\#getBinaryData.getBinaryData でエンコード）。読み取り専用 String。

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


オーディオ データのコピーを返します。大量のデータがある場合は、\#getStream.getStream メソッドを使用して、ビデオ データをメモリに不要にロードしたり、OutOfMemoryException が発生したりするのを防止してください。読み取り専用 byte[]。

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


読み取り用の Stream ストリームを返します。'using' を使用するか、使用後にストリームを閉じてください。

**Returns:**
java.io.InputStream - 読み取り用ストリーム。