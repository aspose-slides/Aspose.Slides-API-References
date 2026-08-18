---
title: LoadOptions
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションの読み込み時に、フォーマットやデフォルトフォントなどの追加オプションを指定できます。
type: docs
url: /ja/com.aspose.slides/loadoptions/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

プレゼンテーションの読み込み時に、フォーマットやデフォルトフォントなどの追加オプションを指定できます。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | 新しいデフォルトのロード オプションを作成します。 |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | 新しいロード オプションを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | ロードするプレゼンテーションのフォーマットを取得または設定します。 |
| [setLoadFormat(int value)](#setLoadFormat-int-) | ロードするプレゼンテーションのフォーマットを取得または設定します。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 元フォントが見つからない場合に使用される Regular フォントを取得または設定します。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 元フォントが見つからない場合に使用される Regular フォントを取得または設定します。 |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | 元フォントが見つからない場合に使用される Symbol フォントを取得または設定します。 |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | 元フォントが見つからない場合に使用される Symbol フォントを取得または設定します。 |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | 元フォントが見つからない場合に使用される Asian フォントを取得または設定します。 |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | 元フォントが見つからない場合に使用される Asian フォントを取得または設定します。 |
| [getPassword()](#getPassword--) | パスワードを取得または設定します。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを取得または設定します。 |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | プレゼンテーション ファイルがパスワードで保護されている場合に意味があります。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | プレゼンテーション ファイルがパスワードで保護されている場合に意味があります。 |
| [getWarningCallback()](#getWarningCallback--) | 警告を受け取り、ロード プロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 警告を受け取り、ロード プロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | バイナリ ラージ オブジェクト (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。たとえば、一時ファイルの使用やメモリ内の BLOB の最大バイト数などです。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | バイナリ ラージ オブジェクト (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。たとえば、一時ファイルの使用やメモリ内の BLOB の最大バイト数などです。 |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | プレゼンテーションで使用される外部フォントのソースを指定します。 |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | プレゼンテーションで使用される外部フォントのソースを指定します。 |
| [getInterruptionToken()](#getInterruptionToken--) | 中断リクエストを監視するトークンです。 |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 中断リクエストを監視するトークンです。 |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 外部リソースの読み込みを管理するコールバック インターフェイスを取得または設定します。 |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 外部リソースの読み込みを管理するコールバック インターフェイスを取得または設定します。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | スプレッドシートのオプションを取得します。 |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | スプレッドシートのオプションを取得します。 |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | プレゼンテーション テキストのデフォルト言語を取得または設定します。 |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | プレゼンテーション テキストのデフォルト言語を取得または設定します。 |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Aspose.Slides がプレゼンテーションの読み込み中に埋め込みバイナリ オブジェクトをすべて削除するかどうかを決定します。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Aspose.Slides がプレゼンテーションの読み込み中に埋め込みバイナリ オブジェクトをすべて削除するかどうかを決定します。 |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

新しいデフォルトのロード オプションを作成します。

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

新しいロード オプションを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| loadFormat | int | ロードするプレゼンテーションのフォーマット。 |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

ロードするプレゼンテーションのフォーマットを取得または設定します。 読み取り/書き込み [LoadFormat](../../com.aspose.slides/loadformat)。

**戻り値:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

ロードするプレゼンテーションのフォーマットを取得または設定します。 読み取り/書き込み [LoadFormat](../../com.aspose.slides/loadformat)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

元フォントが見つからない場合に使用される Regular フォントを取得または設定します。 読み取り/書き込み String.

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションのレンダリング時にデフォルトフォントを設定する方法を示しています。
>  
>  // ロード オプションを使用して、デフォルトの Regular フォントと Asian フォントを定義します
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // プレゼンテーションをロードします
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // スライドのサムネイルを生成します
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // PDF を生成します
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS を生成します
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

元フォントが見つからない場合に使用される Regular フォントを取得または設定します。 読み取り/書き込み String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // ロード オプションを使用して、デフォルトの Regular フォントと Asian フォントを定義します
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // プレゼンテーションをロードします
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // スライドのサムネイルを生成します
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // PDF を生成します
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS を生成します
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

元フォントが見つからない場合に使用される Symbol フォントを取得または設定します。 読み取り/書き込み String.

**戻り値:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

元フォントが見つからない場合に使用される Symbol フォントを取得または設定します。 読み取り/書き込み String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

元フォントが見つからない場合に使用される Asian フォントを取得または設定します。 読み取り/書き込み String.

**戻り値:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

元フォントが見つからない場合に使用される Asian フォントを取得または設定します。 読み取り/書き込み String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

パスワードを取得または設定します。 読み取り/書き込み String.

--------------------

> ```
> 以下のサンプルコードは、パスワードで保護された PowerPoint プレゼンテーションを開く方法を示しています。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 復号化されたプレゼンテーションで作業します
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


値: パスワード。

**戻り値:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

パスワードを取得または設定します。 読み取り/書き込み String.

--------------------

> ```
> 以下のサンプルコードは、パスワードで保護された PowerPoint プレゼンテーションを開く方法を示しています。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 復号化されたプレゼンテーションで作業します
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

プレゼンテーション ファイルがパスワードで保護されている場合に意味があります。 true の場合、暗号化されたプレゼンテーション ファイルからドキュメント プロパティのみをロードし、パスワードは無視されます。 false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティは常に無視されます。暗号化されたファイルのドキュメント プロパティが公開されておらず、かつこのプロパティが true の場合、ドキュメント プロパティはロードできず例外がスローされます。 読み取り/書き込み boolean.

**戻り値:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

プレゼンテーション ファイルがパスワードで保護されている場合に意味があります。 true の場合、暗号化されたプレゼンテーション ファイルからドキュメント プロパティのみをロードし、パスワードは無視されます。 false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティは常に無視されます。暗号化されたファイルのドキュメント プロパティが公開されておらず、かつこのプロパティが true の場合、ドキュメント プロパティはロードできず例外がスローされます。 読み取り/書き込み boolean.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

警告を受け取り、ロード プロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**戻り値:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

警告を受け取り、ロード プロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

バイナリ ラージ オブジェクト (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。たとえば、一時ファイルの使用やメモリ内の BLOB の最大バイト数などです。これらのオプションは、特定の環境や要件に対して、最高のパフォーマンス/メモリ使用率のバランスを設定することを目的としています。

--------------------

Binary Large Object (BLOB) は、単一のエンティティとして保存されるバイナリ データです。つまり、BLOB は音声、ビデオ、またはプレゼンテーションそのものになることがあります。

**戻り値:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

バイナリ ラージ オブジェクト (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。たとえば、一時ファイルの使用やメモリ内の BLOB の最大バイト数などです。これらのオプションは、特定の環境や要件に対して、最高のパフォーマンス/メモリ使用率のバランスを設定することを目的としています。

--------------------

Binary Large Object (BLOB) は、単一のエンティティとして保存されるバイナリ データです。つまり、BLOB は音声、ビデオ、またはプレゼンテーションそのものになることがあります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用でき、他のプレゼンテーションとは共有されません。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションで使用されるカスタムフォントを指定する方法を示しています。
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //プレゼンテーションで作業します
>  //CustomFont1、CustomFont2 に加えて assets\\fonts と global\\fonts フォルダーおよびそのサブフォルダーのフォントもプレゼンテーションで使用可能です
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用でき、他のプレゼンテーションとは共有されません。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションで使用されるカスタムフォントを指定する方法を示しています。
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //プレゼンテーションで作業します
>  //CustomFont1、CustomFont2 に加えて assets\fonts と global\fonts フォルダーおよびそのサブフォルダーのフォントもプレゼンテーションで使用可能です
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

中断リクエストを監視するトークンです。

--------------------

このトークンは [IPresentation](../../com.aspose.slides/ipresentation) インスタンス全体のライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) の [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) メソッドを呼び出すことで中断されます。

**戻り値:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

中断リクエストを監視するトークンです。

--------------------

このトークンは [IPresentation](../../com.aspose.slides/ipresentation) インスタンス全体のライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) の [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) メソッドを呼び出すことで中断されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

外部リソースの読み込みを管理するコールバック インターフェイスを取得または設定します。 読み取り/書き込み [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**戻り値:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

外部リソースの読み込みを管理するコールバック インターフェイスを取得または設定します。 読み取り/書き込み [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

スプレッドシートのオプションを取得します。たとえば、これらのオプションはチャートの数式計算に影響します。

**戻り値:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

スプレッドシートのオプションを取得します。たとえば、これらのオプションはチャートの数式計算に影響します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

プレゼンテーション テキストのデフォルト言語を取得または設定します。 読み取り/書き込み String.

--------------------

> ```
> 例:
>   
>  // ロード オプションを使用してデフォルトのテキスト ロケールを定義します
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // テキスト付きの新しい長方形シェイプを追加します
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 最初の部分の言語を確認します
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

プレゼンテーション テキストのデフォルト言語を取得または設定します。 読み取り/書き込み String.

--------------------

> ```
> 例:
>   
>  // ロード オプションを使用してデフォルトのテキスト ロケールを定義します
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // テキスト付きの新しい長方形シェイプを追加します
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 最初の部分の言語を確認します
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Aspose.Slides がプレゼンテーションの読み込み中に埋め込みバイナリ オブジェクトをすべて削除するかどうかを決定します。

埋め込みバイナリ オブジェクトの種類:

読み取り/書き込み boolean .

--------------------

> ```
> 以下の例は、埋め込みバイナリ オブジェクトを含まないプレゼンテーションの読み込み方法を示しています。
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
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Aspose.Slides がプレゼンテーションの読み込み中に埋め込みバイナリ オブジェクトをすべて削除するかどうかを決定します。

埋め込みバイナリ オブジェクトの種類:

読み取り/書き込み boolean .

--------------------

> ```
> 以下の例は、埋め込みバイナリ オブジェクトを含まないプレゼンテーションの読み込み方法を示しています。
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |