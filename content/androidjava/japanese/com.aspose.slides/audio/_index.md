---
title: Audio
second_title: Java API リファレンスによる Aspose.Slides for Android
description: 埋め込みオーディオ ファイルを表します。
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
| [getContentType()](#getContentType--) | オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData) です。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData) です。 |
| [getBinaryData()](#getBinaryData--) | オーディオのデータのコピーを返します。 |
| [getStream()](#getStream--) | 読み取り用の Stream ストリームを返します。 |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData) です。読み取り専用 String。

**戻り値:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

オーディオの MIME タイプを返します。エンコードは (\#getBinaryData.getBinaryData) です。読み取り専用 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

オーディオのデータのコピーを返します。大量のデータの場合は、\#getStream.getStream メソッドを使用して、オーディオのデータをメモリに不要にロードしたり、OutOfMemoryException が発生するのを防いでください。読み取り専用 byte[]。

**戻り値:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

読み取り用の Stream ストリームを返します。使用後は 'using' を使用するか、ストリームを閉じてください。

**戻り値:**
java.io.InputStream - 読み取り用のストリーム。