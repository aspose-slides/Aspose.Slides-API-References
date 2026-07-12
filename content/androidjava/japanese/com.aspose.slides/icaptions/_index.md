---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /ja/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

WebVTT のクローズドキャプションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 閉じたキャプションのグローバルに一意な識別子 (GUID) を返します。 |
| [getLabel()](#getLabel--) | 閉じたキャプションのラベルを取得または設定します。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | 閉じたキャプションのラベルを取得または設定します。 |
| [getBinaryData()](#getBinaryData--) | 閉じたキャプションのバイナリ データを返します。 |
| [getDataAsString()](#getDataAsString--) | UTF-8 エンコードされた文字列として閉じたキャプションのデータを返します。読み取り専用 String。 |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

閉じたキャプションのグローバルに一意な識別子 (GUID) を返します。読み取り専用 java.util.UUID。

**戻り値:**  
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

閉じたキャプションのラベルを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

閉じたキャプションのラベルを取得または設定します。読み取り/書き込み String。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

閉じたキャプションのバイナリ データを返します。読み取り専用 byte[]。

**戻り値:**  
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

UTF-8 エンコードされた文字列として閉じたキャプションのデータを返します。読み取り専用 String。

**戻り値:**  
java.lang.String