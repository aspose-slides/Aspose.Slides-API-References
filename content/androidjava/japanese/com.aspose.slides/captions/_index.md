---
title: Captions
second_title: Aspose.Slides for Android 向け Java API リファレンス
description: WebVTT のクローズドキャプションを表します。
type: docs
url: /ja/com.aspose.slides/captions/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

WebVTT のクローズドキャプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | クローズドキャプションのグローバルに一意な識別子 (GUID) を返します。 |
| [getLabel()](#getLabel--) | クローズドキャプションのラベルを取得または設定します。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | クローズドキャプションのラベルを取得または設定します。 |
| [getBinaryData()](#getBinaryData--) | クローズドキャプションのバイナリーデータを返します。 |
| [getDataAsString()](#getDataAsString--) | クローズドキャプションのデータを UTF-8 エンコードされた文字列として返します。読み取り専用 String。 |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


クローズドキャプションのグローバルに一意な識別子 (GUID) を返します。読み取り専用 java.util.UUID。

**戻り値:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


クローズドキャプションのラベルを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


クローズドキャプションのラベルを取得または設定します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


クローズドキャプションのバイナリーデータを返します。読み取り専用 byte[] 。

**戻り値:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


クローズドキャプションのデータを UTF-8 エンコードされた文字列として返します。読み取り専用 String。

**戻り値:**
java.lang.String