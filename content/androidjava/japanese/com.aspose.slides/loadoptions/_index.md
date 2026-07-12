---
title: LoadOptions
second_title: Java API リファレンス - Android 用 Aspose.Slides
description: プレゼンテーションの読み込み時に、形式やデフォルトフォントなどの追加オプションを指定できます。
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

プレゼンテーションを読み込む際に、形式やデフォルトフォントなどの追加オプションを指定できます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | 新しいデフォルトのロードオプションを作成します。 |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | 新しいロードオプションを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | プレゼンテーションの読み込み形式を取得または設定します。 |
| [setLoadFormat(int value)](#setLoadFormat-int-) | プレゼンテーションの読み込み形式を取得または設定します。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | ソースフォントが見つからない場合に使用される標準フォントを取得または設定します。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | ソースフォントが見つからない場合に使用される標準フォントを取得または設定します。 |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | ソースフォントが見つからない場合に使用されるシンボルフォントを取得または設定します。 |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | ソースフォントが見つからない場合に使用されるシンボルフォントを取得または設定します。 |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | ソースフォントが見つからない場合に使用されるアジアフォントを取得または設定します。 |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | ソースフォントが見つからない場合に使用されるアジアフォントを取得または設定します。 |
| [getPassword()](#getPassword--) | パスワードを取得または設定します。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを取得または設定します。 |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。 |
| [getWarningCallback()](#getWarningCallback--) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 一時ファイルの使用やメモリ内の BLOB の最大バイト数など、Binary Large Objects (BLOB) の取り扱い動作を管理するオプションを表します。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 一時ファイルの使用やメモリ内の BLOB の最大バイト数など、Binary Large Objects (BLOB) の取り扱い動作を管理するオプションを表します。 |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | プレゼンテーションで使用する外部フォントのソースを指定します。 |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | プレゼンテーションで使用する外部フォントのソースを指定します。 |
| [getInterruptionToken()](#getInterruptionToken--) | 割り込み要求を監視するトークンです。 |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 割り込み要求を監視するトークンです。 |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 外部リソースのロードを管理するコールバックインターフェイスを取得または設定します。 |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 外部リソースのロードを管理するコールバックインターフェイスを取得または設定します。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | スプレッドシートのオプションを取得します。 |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | スプレッドシートのオプションを取得します。 |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | プレゼンテーションテキストのデフォルト言語を取得または設定します。 |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | プレゼンテーションテキストのデフォルト言語を取得または設定します。 |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | プレゼンテーションの読み込み時に Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | プレゼンテーションの読み込み時に Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

新しいデフォルトのロードオプションを作成します。

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

新しいロードオプションを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| loadFormat | int | 読み込むプレゼンテーションの形式。 |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

プレゼンテーションの読み込み形式を取得または設定します。読み取り/書き込み [LoadFormat](../../com.aspose.slides/loadformat)。

**戻り値:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

プレゼンテーションの読み込み形式を取得または設定します。読み取り/書き込み [LoadFormat](../../com.aspose.slides/loadformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

ソースフォントが見つからない場合に使用される標準フォントを取得または設定します。読み取り/書き込み String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // ロードオプションを使用してデフォルトの標準フォントとアジアフォントを定義します
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // プレゼンテーションをロードします
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // スライドのサムネイルを生成します
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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

ソースフォントが見つからない場合に使用される標準フォントを取得または設定します。読み取り/書き込み String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // ロードオプションを使用してデフォルトの標準フォントとアジアフォントを定義します
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // プレゼンテーションをロードします
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // スライドのサムネイルを生成します
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF を生成します
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS を生成します
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

ソースフォントが見つからない場合に使用されるシンボルフォントを取得または設定します。読み取り/書き込み String.

**戻り値:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

ソースフォントが見つからない場合に使用されるシンボルフォントを取得または設定します。読み取り/書き込み String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

ソースフォントが見つからない場合に使用されるアジアフォントを取得または設定します。読み取り/書き込み String.

**戻り値:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

ソースフォントが見つからない場合に使用されるアジアフォントを取得または設定します。読み取り/書き込み String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

パスワードを取得または設定します。読み取り/書き込み String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
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

パスワードを取得または設定します。読み取り/書き込み String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティの値は常に無視されます。暗号化されたファイルのドキュメントプロパティが公開されておらず、かつプロパティの値が true の場合、ドキュメントプロパティはロードできず例外がスローされます。読み取り/書き込み boolean.

**戻り値:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティの値は常に無視されます。暗号化されたファイルのドキュメントプロパティが公開されておらず、かつプロパティの値が true の場合、ドキュメントプロパティはロードできず例外がスローされます。読み取り/書き込み boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**戻り値:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Binary Large Objects (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。たとえば、一時ファイルの使用やメモリ内の BLOB の最大バイト数などです。これらのオプションは、特定の環境や要件に対して最高のパフォーマンス/メモリ消費比を設定することを目的としています。

--------------------

Binary Large Object (BLOB) は単一のエンティティとして格納されるバイナリデータです。つまり、BLOB はオーディオ、ビデオ、またはプレゼンテーション自体になることがあります。

**戻り値:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Binary Large Objects (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。たとえば、一時ファイルの使用やメモリ内の BLOB の最大バイト数などです。これらのオプションは、特定の環境や要件に対して最高のパフォーマンス/メモリ消費比を設定することを目的としています。

--------------------

Binary Large Object (BLOB) は単一のエンティティとして格納されるバイナリデータです。つまり、BLOB はオーディオ、ビデオ、またはプレゼンテーション自体になることがあります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションとは共有されません。

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // プレゼンテーションで作業します
>  // CustomFont1、CustomFont2 と assets\fonts および global\fonts フォルダーとそのサブフォルダー内のフォントがプレゼンテーションで使用可能です
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

プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションとは共有されません。

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // プレゼンテーションで作業します
>  // CustomFont1、CustomFont2 と assets\fonts および global\fonts フォルダーとそのサブフォルダー内のフォントがプレゼンテーションで使用可能です
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

割り込み要求を監視するトークンです。

--------------------

このトークンは [IPresentation](../../com.aspose.slides/ipresentation) インスタンス全体のライフタイムを管理します。プレゼンテーションのロードや保存などの長時間実行される操作は、[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) の [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) メソッドを呼び出すことで中断されます。

**戻り値:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

割り込み要求を監視するトークンです。

--------------------

このトークンは [IPresentation](../../com.aspose.slides/ipresentation) インスタンス全体のライフタイムを管理します。プレゼンテーションのロードや保存などの長時間実行される操作は、[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) の [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) メソッドを呼び出すことで中断されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

外部リソースのロードを管理するコールバックインターフェイスを取得または設定します。読み取り/書き込み [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**戻り値:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

外部リソースのロードを管理するコールバックインターフェイスを取得または設定します。読み取り/書き込み [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**パラメータ:**
| パラメータ | 型 | 説明 |
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

プレゼンテーションテキストのデフォルト言語を取得または設定します。読み取り/書き込み String。

--------------------

> ```
> Example:
>   
>  // ロードオプションを使用してデフォルトのテキストカルチャーを定義します
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // テキスト付きの新しい長方形シェイプを追加します
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 最初のポーションの言語をチェックします
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

プレゼンテーションテキストのデフォルト言語を取得または設定します。読み取り/書き込み String。

--------------------

> ```
> Example:
>   
>  // ロードオプションを使用してデフォルトのテキストカルチャーを定義します
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // テキスト付きの新しい長方形シェイプを追加します
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 最初のポーションの言語をチェックします
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

プレゼンテーションの読み込み時に Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。

埋め込まれたバイナリオブジェクトの種類:

読み取り/書き込み boolean.

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
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

プレゼンテーションの読み込み時に Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。

埋め込まれたバイナリオブジェクトの種類:

読み取り/書き込み boolean.

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |