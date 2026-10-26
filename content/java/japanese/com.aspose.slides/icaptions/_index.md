---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /ja/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

WebVTT クローズドキャプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | クローズドキャプションのグローバルに一意な識別子 (GUID) を返します。読み取り専用 java.util.UUID。 |
| [getLabel()](#getLabel--) | クローズドキャプションのラベルを取得または設定します。読み取り/書き込み String。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | クローズドキャプションのラベルを取得または設定します。読み取り/書き込み String。 |
| [getBinaryData()](#getBinaryData--) | クローズドキャプションのバイナリデータを返します。読み取り専用 byte[]。 |
| [getDataAsString()](#getDataAsString--) | クローズドキャプションのデータを UTF-8 エンコードされた文字列として返します。読み取り専用 String。 |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

クローズドキャプションのグローバルに一意な識別子 (GUID) を返します。読み取り専用 java.util.UUID。

**戻り値:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

クローズドキャプションのラベルを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

クローズドキャプションのラベルを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

クローズドキャプションのバイナリデータを返します。読み取り専用 byte[]。

**戻り値:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

クローズドキャプションのデータを UTF-8 エンコードされた文字列として返します。読み取り専用 String。

**戻り値:**
java.lang.String