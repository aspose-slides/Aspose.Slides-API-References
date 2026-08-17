---
title: IAudio
second_title: Aspose.Slides の Java API リファレンス
description: 埋め込みオーディオファイルを表します。
type: docs
url: /ja/com.aspose.slides/iaudio/
---```
public interface IAudio
```

埋め込みオーディオファイルを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | オーディオの MIME タイプを返します、(\#getBinaryData.getBinaryData)でエンコードされています。 |
| [getBinaryData()](#getBinaryData--) | オーディオのデータのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用の Stream ストリームを返します。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

オーディオの MIME タイプを返します、(\#getBinaryData.getBinaryData)でエンコードされています。 読み取り専用 String.

**戻り値:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

オーディオのデータのコピーを返します。 大量のデータの場合は、\#getStream.getStream メソッドを使用して、オーディオデータをメモリに不要にロードしたり、OutOfMemoryException が発生するのを防いでください。 読み取り専用 byte[].

**戻り値:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

読み取り用の Stream ストリームを返します。 使用後は 'using' を使用するか、ストリームを閉じてください。

**戻り値:**  
java.io.InputStream - 読み取り用ストリーム。