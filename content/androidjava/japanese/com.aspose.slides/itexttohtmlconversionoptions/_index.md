---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: PPTX テキストから HTML を抽出するためのオプションです。
type: docs
url: /ja/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

PPTX テキストから HTML を抽出するためのオプションです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 値を取得または設定し、Clipboard ヘッダーを追加するかどうかを示します。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 値を取得または設定し、Clipboard ヘッダーを追加するかどうかを示します。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | テキスト プロパティの継承深さを取得または設定します。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | テキスト プロパティの継承深さを取得または設定します。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 外部オブジェクトの保存方法を制御するコールバック オブジェクトを取得または設定します。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 外部オブジェクトの保存方法を制御するコールバック オブジェクトを取得または設定します。 |
| [getEncodingName()](#getEncodingName--) | html エンコーディング名を取得または設定します。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | html エンコーディング名を取得または設定します。 |

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

値を取得または設定し、Clipboard ヘッダーを追加するかどうかを示します。読み書き可能な boolean.

**戻り値:**
boolean

### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

値を取得または設定し、Clipboard ヘッダーを追加するかどうかを示します。読み書き可能な boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

テキスト プロパティの継承深さを取得または設定します。読み書き可能な [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**戻り値:**
int

### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

テキスト プロパティの継承深さを取得または設定します。読み書き可能な [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

外部オブジェクトの保存方法を制御するコールバック オブジェクトを取得または設定します。読み書き可能な [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**戻り値:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)

### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

外部オブジェクトの保存方法を制御するコールバック オブジェクトを取得または設定します。読み書き可能な [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

html エンコーディング名を取得または設定します。この値は生成された HTML ファイルに保存されますが、ファイルがこのエンコーディングで保存されることは呼び出し側が保証する必要があります。読み書き可能な String.

**戻り値:**
java.lang.String

### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

html エンコーディング名を取得または設定します。この値は生成された HTML ファイルに保存されますが、ファイルがこのエンコーディングで保存されることは呼び出し側が保証する必要があります。読み書き可能な String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |