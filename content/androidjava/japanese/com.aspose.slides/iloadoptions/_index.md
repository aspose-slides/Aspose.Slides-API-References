---
title: ILoadOptions
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレゼンテーションの読み込み時に、形式やデフォルトフォントなどの追加オプションを指定できます。
type: docs
url: /ja/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

プレゼンテーションの読み込み時に、形式やデフォルトフォントなどの追加オプションを指定できます。
## メソッド

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | ロードするプレゼンテーションの形式を取得または設定します。 |
| [setLoadFormat(int value)](#setLoadFormat-int-) | ロードするプレゼンテーションの形式を取得または設定します。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | ソースフォントが見つからない場合に使用する標準フォントを取得または設定します。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | ソースフォントが見つからない場合に使用する標準フォントを取得または設定します。 |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | ソースフォントが見つからない場合に使用するシンボルフォントを取得または設定します。 |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | ソースフォントが見つからない場合に使用するシンボルフォントを取得または設定します。 |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | ソースフォントが見つからない場合に使用するアジアフォントを取得または設定します。 |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | ソースフォントが見つからない場合に使用するアジアフォントを取得または設定します。 |
| [getPassword()](#getPassword--) | パスワードを取得または設定します。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを取得または設定します。 |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。 |
| [getWarningCallback()](#getWarningCallback--) | 警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 一時ファイルの使用やメモリ内の BLOB バイト数の上限など、Binary Large Objects (BLOB) の処理動作を管理するために使用できるオプションを表します。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 一時ファイルの使用やメモリ内の BLOB バイト数の上限など、Binary Large Objects (BLOB) の処理動作を管理するために使用できるオプションを表します。 |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | プレゼンテーションで使用される外部フォントのソースを指定します。 |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | プレゼンテーションで使用される外部フォントのソースを指定します。 |
| [getInterruptionToken()](#getInterruptionToken--) | 中断要求を監視するトークンです。 |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 中断要求を監視するトークンです。 |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 外部リソースの読み込みを管理するコールバックインターフェイスを取得または設定します。 |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 外部リソースの読み込みを管理するコールバックインターフェイスを取得または設定します。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 追加のスプレッドシート動作を指定するために使用できるオプションを表します。 |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | 追加のスプレッドシート動作を指定するために使用できるオプションを表します。 |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | プレゼンテーションテキストのデフォルト言語を取得または設定します。 |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | プレゼンテーションテキストのデフォルト言語を取得または設定します。 |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | プレゼンテーションの読み込み時に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | プレゼンテーションの読み込み時に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


ロードするプレゼンテーションの形式を取得または設定します。 読み書き可能 [LoadFormat](../../com.aspose.slides/loadformat)。

**戻り値:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```


ロードするプレゼンテーションの形式を取得または設定します。 読み書き可能 [LoadFormat](../../com.aspose.slides/loadformat)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


ソースフォントが見つからない場合に使用する標準フォントを取得または設定します。 読み書き可能 String。

**戻り値:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


ソースフォントが見つからない場合に使用する標準フォントを取得または設定します。 読み書き可能 String。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```


ソースフォントが見つからない場合に使用するシンボルフォントを取得または設定します。 読み書き可能 String。

**戻り値:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```


ソースフォントが見つからない場合に使用するシンボルフォントを取得または設定します。 読み書き可能 String。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```


ソースフォントが見つからない場合に使用するアジアフォントを取得または設定します。 読み書き可能 String。

**戻り値:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```


ソースフォントが見つからない場合に使用するアジアフォントを取得または設定します。 読み書き可能 String。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


パスワードを取得または設定します。 読み書き可能 String。

Value: The password.

**戻り値:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


パスワードを取得または設定します。 読み書き可能 String。

Value: The password.

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```


このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。 true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。 false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティは常に無視されます。暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティが true の場合、ドキュメントプロパティはロードできず例外がスローされます。 読み書き可能 boolean。

**戻り値:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```


このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。 true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。 false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティは常に無視されます。暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティが true の場合、ドキュメントプロパティはロードできず例外がスローされます。 読み書き可能 boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 読み書き可能 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**戻り値:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 読み書き可能 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```


一時ファイルの使用やメモリ内の BLOB バイト数の上限など、Binary Large Objects (BLOB) の処理動作を管理するために使用できるオプションを表します。 これらのオプションは、特定の環境や要件に対して最適なパフォーマンス／メモリ消費のバランスを設定することを目的としています。

--------------------

Binary Large Object (BLOB) は、単一エンティティとして格納されるバイナリデータです。たとえば、BLOB は音声、動画、またはプレゼンテーション自体になることがあります。

**戻り値:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```


一時ファイルの使用やメモリ内の BLOB バイト数の上限など、Binary Large Objects (BLOB) の処理動作を管理するために使用できるオプションを表します。 これらのオプションは、特定の環境や要件に対して最適なパフォーマンス／メモリ消費のバランスを設定することを目的としています。

--------------------

Binary Large Object (BLOB) は、単一エンティティとして格納されるバイナリデータです。たとえば、BLOB は音声、動画、またはプレゼンテーション自体になることがあります。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```


プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションとは共有されません。

**戻り値:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```


プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションとは共有されません。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```


中断要求を監視するトークンです。

--------------------

このトークンは、[IPresentation](../../com.aspose.slides/ipresentation) インスタンス全体の寿命を管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) の [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) メソッドを呼び出すことで中断されます。

**戻り値:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```


中断要求を監視するトークンです。

--------------------

このトークンは、[IPresentation](../../com.aspose.slides/ipresentation) インスタンス全体の寿命を管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) の [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) メソッドを呼び出すことで中断されます。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```


外部リソースの読み込みを管理するコールバックインターフェイスを取得または設定します。 読み書き可能 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**戻り値:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```


外部リソースの読み込みを管理するコールバックインターフェイスを取得または設定します。 読み書き可能 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```


追加のスプレッドシート動作を指定するために使用できるオプションを表します。

**戻り値:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```


追加のスプレッドシート動作を指定するために使用できるオプションを表します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```


プレゼンテーションテキストのデフォルト言語を取得または設定します。 読み書き可能 String。

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```


プレゼンテーションテキストのデフォルト言語を取得または設定します。 読み書き可能 String。

--------------------

> ```
> Example:
>   
>  // ロードオプションを使用してデフォルトテキストカルチャーを定義します
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // テキスト付きの新しい矩形シェイプを追加します
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 最初のポーションの言語を確認します
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```


プレゼンテーションの読み込み時に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。

The types of the embedded binary objects:

 *  
 *  
 *  

読み書き可能 boolean 。

--------------------

> ```
> 以下の例は、埋め込みバイナリオブジェクトなしでプレゼンテーションをロードする方法を示しています。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルトは **false** です。

**戻り値:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```


プレゼンテーションの読み込み時に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。

The types of the embedded binary objects:

 *  
 *  
 *  

読み書き可能 boolean 。

--------------------

> ```
> 以下の例は、埋め込みバイナリオブジェクトなしでプレゼンテーションをロードする方法を示しています。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

デフォルトは **false** です。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |