---
title: Audio
second_title: Aspose.Slides for Java API リファレンス
description: 埋め込みオーディオファイルを表します。
type: docs
url: /ja/com.aspose.slides/audio/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

埋め込みオーディオ ファイルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContentType()](#getContentType--) | オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData)。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData)。 |
| [getBinaryData()](#getBinaryData--) | オーディオのデータのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用の Stream ストリームを返します。 |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData)。 読み取り専用 String.

**返却値:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData)。 読み取り専用 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

オーディオ データのコピーを返します。大量のデータがある場合は、\#getStream.getStream メソッドの使用を検討してください。メモリへの不要なロードや OutOfMemoryException を防止できます。 読み取り専用 byte[]。

**返却値:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

読み取り用の Stream ストリームを返します。'using' を使用するか、使用後にストリームを閉じてください。

**返却値:**
java.io.InputStream - 読み取り用の Stream。