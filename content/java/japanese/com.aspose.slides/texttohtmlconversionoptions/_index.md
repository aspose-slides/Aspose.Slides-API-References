---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides for Java API リファレンス
description: Pptx テキストから HTML を抽出するためのオプション。
type: docs
url: /ja/com.aspose.slides/texttohtmlconversionoptions/
---
**継承:**
java.lang.Object

**実装されたインターフェイス:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Pptx テキストから HTML を抽出するオプションです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Clipboard ヘッダーを追加すべきかを示す値を取得または設定します。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Clipboard ヘッダーを追加すべきかを示す値を取得または設定します。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | テキストプロパティの継承深さを取得または設定します。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | テキストプロパティの継承深さを取得または設定します。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。 |
| [getEncodingName()](#getEncodingName--) | HTML エンコーディング名を取得または設定します。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML エンコーディング名を取得または設定します。 |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Clipboard ヘッダーを追加すべきかを示す値を取得または設定します。 読み書き可能な boolean.

**戻り値:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Clipboard ヘッダーを追加すべきかを示す値を取得または設定します。 読み書き可能な boolean.

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


テキストプロパティの継承深さを取得または設定します。 読み書き可能 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**戻り値:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


テキストプロパティの継承深さを取得または設定します。 読み書き可能 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。 読み書き可能 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**戻り値:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


外部オブジェクトの保存方法を制御するコールバックオブジェクトを取得または設定します。 読み書き可能 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


HTML エンコーディング名を取得または設定します。 この値は生成された HTML ファイルに保存されますが、ファイルがこのエンコーディングで保存されることは呼び出し元の責任です。 読み書き可能 String.

**戻り値:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


HTML エンコーディング名を取得または設定します。 この値は生成された HTML ファイルに保存されますが、ファイルがこのエンコーディングで保存されることは呼び出し元の責任です。 読み書き可能 String.

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |