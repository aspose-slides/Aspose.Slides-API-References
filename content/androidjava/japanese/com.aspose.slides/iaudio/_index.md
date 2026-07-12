---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an embedded audio file.
type: docs
url: /ja/com.aspose.slides/iaudio/
---```
public interface IAudio
```

埋め込みオーディオファイルを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | オーディオの MIME タイプを返します。 (\#getBinaryData.getBinaryData) でエンコードされています。 |
| [getBinaryData()](#getBinaryData--) | オーディオ データのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用の Stream ストリームを返します。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

オーディオの MIME タイプを返します。 (\#getBinaryData.getBinaryData) でエンコードされています。 読み取り専用 String。

**戻り値:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

オーディオ データのコピーを返します。大量のデータの場合は、メモリへの不要なロードや OutOfMemoryException を防ぐために \#getStream.getStream メソッドの使用を検討してください。 読み取り専用 byte[]。

**戻り値:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

読み取り用の Stream ストリームを返します。'using' を使用するか、使用後にストリームを閉じてください。

**戻り値:**  
java.io.InputStream - Stream for reading.