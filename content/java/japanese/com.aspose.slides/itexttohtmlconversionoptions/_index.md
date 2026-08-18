---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Pptx テキストから HTML を抽出するためのオプション。
type: docs
url: /ja/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Pptx テキストから HTML を抽出するためのオプション。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | クリップボードヘッダーを追加するかどうかを示す値を取得または設定します。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | クリップボードヘッダーを追加するかどうかを示す値を取得または設定します。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | テキストプロパティの継承深度を取得または設定します。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | テキストプロパティの継承深度を取得または設定します。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。 |
| [getEncodingName()](#getEncodingName--) | HTML エンコーディング名を取得または設定します。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML エンコーディング名を取得または設定します。 |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

クリップボードヘッダーを追加するかどうかを示す値を取得または設定します。読み取り/書き込み boolean.

**戻り値:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

クリップボードヘッダーを追加するかどうかを示す値を取得または設定します。読み取り/書き込み boolean.

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

テキストプロパティの継承深度を取得または設定します。読み取り/書き込み [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**戻り値:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

テキストプロパティの継承深度を取得または設定します。読み取り/書き込み [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。読み取り/書き込み [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**戻り値:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。読み取り/書き込み [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

HTML エンコーディング名を取得または設定します。この値は生成された HTML ファイルに保存されますが、呼び出し側がこのエンコーディングでファイルが保存されるようにする必要があります。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

HTML エンコーディング名を取得または設定します。この値は生成された HTML ファイルに保存されますが、呼び出し側がこのエンコーディングでファイルが保存されるようにする必要があります。読み取り/書き込み String。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |