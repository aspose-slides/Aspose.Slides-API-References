---
title: WebDocument
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションを Web 形式で保存するための遷移形態を表します。
type: docs
url: /ja/com.aspose.slides/webdocument/
---
**継承:**  
java.lang.Object  
```
public class WebDocument
```

プレゼンテーションを Web 形式で保存するための遷移形式を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) コンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [save()](#save--) | ドキュメントの出力を保存します。 |
| [getInput()](#getInput--) | ドキュメントの入力要素（テンプレート）のコレクションを返します。 |
| [getOutput()](#getOutput--) | ドキュメントの出力要素のコレクションを返します。 |
| [getGlobal()](#getGlobal--) | ドキュメントのグローバルストレージを返します。 |

### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) コンストラクタ。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | ドキュメントに設定されたオプション。 |

### save() {#save--}
```
public final void save()
```

ドキュメントの出力を保存します。

### getInput() {#getInput--}
```
public final Input getInput()
```

ドキュメントの入力要素（テンプレート）のコレクションを返します。読み取り専用 [Input](../../com.aspose.slides/input)(\#getInput.getInput)。

**戻り値:**
[Input](../../com.aspose.slides/input)

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

ドキュメントの出力要素のコレクションを返します。読み取り専用 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput)。

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // テンプレートから使用するために "slideMargin" プロパティを設定
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... ドキュメントの他のオプションを設定し、そしてドキュメントを保存
>   document.save();
> ```

**戻り値:**
[Output](../../com.aspose.slides/output)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

ドキュメントのグローバルストレージを返します。読み取り専用 [Storage](../../com.aspose.slides/storage)。

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // テンプレートから使用するために "slideMargin" プロパティを設定
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... ドキュメントの他のオプションを設定し、そしてドキュメントを保存
>   document.save();
> ```

**戻り値:**
[Storage](../../com.aspose.slides/storage)