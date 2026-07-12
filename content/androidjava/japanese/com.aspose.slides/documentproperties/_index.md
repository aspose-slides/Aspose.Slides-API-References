---
title: DocumentProperties
second_title: Java API リファレンス経由の Android 用 Aspose.Slides
description: プレゼンテーションのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/documentproperties/
---
**継承:**  
java.lang.Object

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable  
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

プレゼンテーションのプロパティを表します。

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // プレゼンテーションを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Presentation に関連付けられた IDocumentProperties オブジェクトへの参照を作成します
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // 組み込みプロパティを表示します
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Presentation を表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Presentation に関連付けられた IDocumentProperties オブジェクトへの参照を作成します
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // 組み込みプロパティを設定します
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // プレゼンテーションをファイルに保存します
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | クラス [DocumentProperties](../../com.aspose.slides/documentproperties) の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | アプリのバージョンを返します。 |
| [getNameOfApplication()](#getNameOfApplication--) | アプリケーションの名前を取得または設定します。 |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | アプリケーションの名前を取得または設定します。 |
| [getCompany()](#getCompany--) | 会社プロパティを取得または設定します。 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 会社プロパティを取得または設定します。 |
| [getManager()](#getManager--) | マネージャー プロパティを取得または設定します。 |
| [setManager(String value)](#setManager-java.lang.String-) | マネージャー プロパティを取得または設定します。 |
| [getPresentationFormat()](#getPresentationFormat--) | プレゼンテーションの意図された形式を取得または設定します。 |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | プレゼンテーションの意図された形式を取得または設定します。 |
| [getSharedDoc()](#getSharedDoc--) | プレゼンテーションが複数のユーザーで共有されているかどうかを判定します。 |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | プレゼンテーションが複数のユーザーで共有されているかどうかを判定します。 |
| [getApplicationTemplate()](#getApplicationTemplate--) | アプリケーションのテンプレートを取得または設定します。 |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | アプリケーションのテンプレートを取得または設定します。 |
| [getTotalEditingTime()](#getTotalEditingTime--) | プレゼンテーションの総編集時間です。 |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | プレゼンテーションの総編集時間です。 |
| [getTitle()](#getTitle--) | プレゼンテーションのタイトルを取得または設定します。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | プレゼンテーションのタイトルを取得または設定します。 |
| [getSubject()](#getSubject--) | プレゼンテーションの件名を取得または設定します。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | プレゼンテーションの件名を取得または設定します。 |
| [getAuthor()](#getAuthor--) | プレゼンテーションの著者を取得または設定します。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | プレゼンテーションの著者を取得または設定します。 |
| [getKeywords()](#getKeywords--) | プレゼンテーションのキーワードを取得または設定します。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | プレゼンテーションのキーワードを取得または設定します。 |
| [getComments()](#getComments--) | プレゼンテーションのコメントを取得または設定します。 |
| [setComments(String value)](#setComments-java.lang.String-) | プレゼンテーションのコメントを取得または設定します。 |
| [getCategory()](#getCategory--) | プレゼンテーションのカテゴリを取得または設定します。 |
| [setCategory(String value)](#setCategory-java.lang.String-) | プレゼンテーションのカテゴリを取得または設定します。 |
| [getCreatedTime()](#getCreatedTime--) | プレゼンテーションが作成された日付を返します。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | プレゼンテーションが作成された日付を返します。 |
| [getLastSavedTime()](#getLastSavedTime--) | プレゼンテーションが最後に変更された日付を返します。 |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | プレゼンテーションが最後に変更された日付を返します。 |
| [getLastPrinted()](#getLastPrinted--) | プレゼンテーションが最後に印刷された日付を返します。 |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | プレゼンテーションが最後に印刷された日付を返します。 |
| [getLastSavedBy()](#getLastSavedBy--) | プレゼンテーションを最後に変更した人物の名前を取得または設定します。 |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | プレゼンテーションを最後に変更した人物の名前を取得または設定します。 |
| [getRevisionNumber()](#getRevisionNumber--) | プレゼンテーションのリビジョン番号を取得または設定します。 |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | プレゼンテーションのリビジョン番号を取得または設定します。 |
| [getContentStatus()](#getContentStatus--) | プレゼンテーションのコンテンツステータスを取得または設定します。 |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | プレゼンテーションのコンテンツステータスを取得または設定します。 |
| [getContentType()](#getContentType--) | プレゼンテーションのコンテンツタイプを取得または設定します。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | プレゼンテーションのコンテンツタイプを取得または設定します。 |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase ドキュメントプロパティを取得または設定します。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase ドキュメントプロパティを取得または設定します。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | コレクションに実際に含まれるカスタムプロパティの数を返します。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 指定された名前のカスタムプロパティの存在を確認します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | カスタムプロパティから名前付き boolean 値を取得します。 |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | カスタムプロパティから名前付き integer 値を取得します。 |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | カスタムプロパティから名前付き DateTime 値を取得します。 |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | カスタムプロパティから名前付き string 値を取得します。 |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | カスタムプロパティから名前付き float 値を取得します。 |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | カスタムプロパティから名前付き double 値を取得します。 |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 名前付き boolean カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 名前付き integer カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 名前付き DateTime カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 名前付き string カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 名前付き float カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 名前付き double カスタムプロパティを設定します。 |
| [clearCustomProperties()](#clearCustomProperties--) | すべてのカスタムプロパティを削除します。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | カスタムドキュメントプロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK Metadata)。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | すべての組み込みプロパティをクリアし、デフォルト値を設定します。 |
| [getScaleCrop()](#getScaleCrop--) | ドキュメントサムネイルの表示モードを示します。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | ドキュメントサムネイルの表示モードを示します。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | このパートのハイパーリンクがプロデューサーによってこのパートのみで更新されたことを指定します。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | このパートのハイパーリンクがプロデューサーによってこのパートのみで更新されたことを指定します。 |
| [getSlides()](#getSlides--) | プレゼンテーションドキュメントの総スライド数を返します。 |
| [getHiddenSlides()](#getHiddenSlides--) | プレゼンテーションドキュメントの非表示スライド数を返します。 |
| [getNotes()](#getNotes--) | ノートを含むプレゼンテーションのスライド数を返します。 |
| [getParagraphs()](#getParagraphs--) | 該当する場合、ドキュメントに見つかった段落の総数を返します。 |
| [getWords()](#getWords--) | ドキュメントに含まれる単語の総数を返します。 |
| [getMultimediaClips()](#getMultimediaClips--) | ドキュメントに存在する音声またはビデオクリップの総数を返します。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 各ドキュメントパートのタイトルを指定します。 |
| [getHeadingPairs()](#getHeadingPairs--) | ドキュメントパートのグループ化と各グループのパート数を示します。 |
| [deepClone()](#deepClone--) | 現在のオブジェクトをクローンします |
| [cloneT()](#cloneT--) | 現在のオブジェクトをクローンします |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

クラス [DocumentProperties](../../com.aspose.slides/documentproperties) の新しいインスタンスを初期化します。

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

アプリのバージョンを返します。読み取り専用 String。

**戻り値:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

アプリケーションの名前を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

アプリケーションの名前を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

会社プロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

会社プロパティを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

マネージャー プロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

マネージャー プロパティを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

プレゼンテーションの意図された形式を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

プレゼンテーションの意図された形式を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

プレゼンテーションが複数のユーザーで共有されているかどうかを判定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

プレゼンテーションが複数のユーザーで共有されているかどうかを判定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

アプリケーションのテンプレートを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

アプリケーションのテンプレートを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

プレゼンテーションの総編集時間です。読み取り/書き込み double。

**戻り値:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

プレゼンテーションの総編集時間です。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

プレゼンテーションのタイトルを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

プレゼンテーションのタイトルを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

プレゼンテーションの件名を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

プレゼンテーションの件名を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

プレゼンテーションの著者を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

プレゼンテーションの著者を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

プレゼンテーションのキーワードを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

プレゼンテーションのキーワードを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

プレゼンテーションのコメントを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

プレゼンテーションのコメントを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

プレゼンテーションのカテゴリを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

プレゼンテーションのカテゴリを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

プレゼンテーションが作成された日付を返します。値は UTC です。読み取り/書き込み java.util.Date。

**戻り値:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

プレゼンテーションが作成された日付を設定します。値は UTC です。読み取り/書き込み java.util.Date。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

プレゼンテーションが最後に変更された日付を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です（IPresentation オブジェクト保存プロセス中に内部で更新されます）。[IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) が返す DocumentProperties インスタンスを介して変更できます。[IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッドの概要をご参照ください。

**戻り値:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

プレゼンテーションが最後に変更された日付を設定します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です（IPresentation オブジェクト保存プロセス中に内部で更新されます）。[IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) が返す DocumentProperties インスタンスを介して変更できます。[IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッドの概要をご参照ください。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

プレゼンテーションが最後に印刷された日付を返します。読み取り/書き込み java.util.Date。

**戻り値:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

プレゼンテーションが最後に印刷された日付を設定します。読み取り/書き込み java.util.Date。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

プレゼンテーションを最後に変更した人物の名前を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

プレゼンテーションを最後に変更した人物の名前を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

プレゼンテーションのリビジョン番号を取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

プレゼンテーションのリビジョン番号を取得または設定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

プレゼンテーションのコンテンツステータスを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

プレゼンテーションのコンテンツステータスを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

プレゼンテーションのコンテンツタイプを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

プレゼンテーションのコンテンツタイプを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

HyperlinkBase ドキュメントプロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

HyperlinkBase ドキュメントプロパティを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

コレクションに実際に含まれるカスタムプロパティの数を返します。読み取り専用 int。

**戻り値:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

指定されたインデックスのカスタムプロパティ名を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得するカスタムプロパティの 0 ベース インデックス。 |

**戻り値:**
java.lang.String - 指定されたインデックスのカスタムプロパティ名。

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

指定された名前に関連付けられたカスタムプロパティを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 削除するカスタムプロパティの名前。 |

**戻り値:**
boolean - プロパティが削除された場合は true、そうでない場合は false。

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

指定された名前のカスタムプロパティの存在を確認します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 確認するカスタムプロパティの名前。 |

**戻り値:**
boolean - プロパティが存在する場合は true、存在しない場合は false。

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

指定された名前に関連付けられたカスタムプロパティを取得または設定します。読み取り/書き込み Object。

---

値は **int**、**float**、**String**、**boolean** または **Date** のいずれかです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**戻り値:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

指定された名前に関連付けられたカスタムプロパティを取得または設定します。読み取り/書き込み Object。

---

値は **int**、**float**、**String**、**boolean** または **Date** のいずれかです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

カスタムプロパティから名前付き boolean 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | boolean[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

カスタムプロパティから名前付き integer 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | int[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

カスタムプロパティから名前付き DateTime 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | java.util.Date[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

カスタムプロパティから名前付き string 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | java.lang.String[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

カスタムプロパティから名前付き float 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | float[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

カスタムプロパティから名前付き double 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | double[] | カスタムプロパティの値 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

名前付き boolean カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | boolean | カスタムプロパティの値 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

名前付き integer カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | int | カスタムプロパティの値 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

名前付き DateTime カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | java.util.Date | カスタムプロパティの値 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

名前付き string カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | java.lang.String | カスタムプロパティの値 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

名前付き float カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | float | カスタムプロパティの値 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

名前付き double カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | double | カスタムプロパティの値 |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

すべてのカスタムプロパティを削除します。

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

カスタムドキュメントプロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK Metadata)。

**戻り値:**
com.aspose.slides.ISensitivityLabel[]

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // カスタムドキュメントプロパティから感度ラベルを取得します
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // コレクションにラベルを追加します
>          // ここでラベル情報の有効性（ラベルが利用可能かなど）をチェックできます
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
com.aspose.slides.ISensitivityLabel[]

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

すべての組み込みプロパティをクリアし、デフォルト値を設定します。

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルが表示領域に合わせて拡大縮小されます。**false** に設定するとサムネイルが切り取られ、表示領域に収まる部分だけが表示されます。読み取り/書き込み boolean。

**戻り値:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルが表示領域に合わせて拡大縮小されます。**false** に設定するとサムネイルが切り取られ、表示領域に収まる部分だけが表示されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されていることを示します。**false** に設定するとハイパーリンクが古いことを示します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されていることを示します。**false** に設定するとハイパーリンクが古いことを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

このパートのハイパーリンクがプロデューサーによってこのパートのみで更新されたことを指定します。このドキュメントを次に開くプロデューサーは、指定された新しいハイパーリンクでハイパーリンク関係を更新します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

このパートのハイパーリンクがプロデューサーによってこのパートのみで更新されたことを指定します。このドキュメントを次に開くプロデューサーは、指定された新しいハイパーリンクでハイパーリンク関係を更新します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

プレゼンテーションドキュメントの総スライド数を返します。読み取り専用 int。

**戻り値:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

プレゼンテーションドキュメントの非表示スライド数を返します。読み取り専用 int。

**戻り値:**
int

### getNotes() {#getNotes--}
```
public final int getNotes()
```

ノートを含むプレゼンテーションのスライド数を返します。読み取り専用 int。

**戻り値:**
int

### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

該当する場合、ドキュメントに見つかった段落の総数を返します。読み取り専用 int。

**戻り値:**
int

### getWords() {#getWords--}
```
public final int getWords()
```

ドキュメントに含まれる単語の総数を返します。読み取り専用 int。

**戻り値:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

ドキュメントに存在する音声またはビデオクリップの総数を返します。読み取り専用 int。

**戻り値:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

各ドキュメントパートのタイトルを指定します。これらは実際のドキュメントパートではなく、ドキュメントセクションの概念的表現です。読み取り専用 String[]。

**戻り値:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

ドキュメントパートのグループ化と各グループのパート数を示します。読み取り専用 IHeadingPair[]。

**戻り値:**
com.aspose.slides.IHeadingPair[]

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

現在のオブジェクトをクローンします

**戻り値:**
java.lang.Object - クローン

### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

現在のオブジェクトをクローンします

**戻り値:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - クローン