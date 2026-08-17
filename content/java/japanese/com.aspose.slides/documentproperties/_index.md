---
title: DocumentProperties
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/documentproperties/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
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
>      // プレゼンテーションに関連付けられた IDocumentProperties オブジェクトへの参照を作成します
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
>  // プレゼンテーションを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // プレゼンテーションに関連付けられた IDocumentProperties オブジェクトへの参照を作成します
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // 組み込みプロパティを設定します
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // プレゼンテーションをファイルに保存します
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | クラス [DocumentProperties](../../com.aspose.slides/documentproperties) の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | アプリ バージョンを返します。 |
| [getNameOfApplication()](#getNameOfApplication--) | アプリケーションの名前を取得または設定します。 |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | アプリケーションの名前を取得または設定します。 |
| [getCompany()](#getCompany--) | 会社プロパティを取得または設定します。 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 会社プロパティを取得または設定します。 |
| [getManager()](#getManager--) | マネージャープロパティを取得または設定します。 |
| [setManager(String value)](#setManager-java.lang.String-) | マネージャープロパティを取得または設定します。 |
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
| [getSubject()](#getSubject--) | プレゼンテーションのテーマを取得または設定します。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | プレゼンテーションのテーマを取得または設定します。 |
| [getAuthor()](#getAuthor--) | プレゼンテーションの作成者を取得または設定します。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | プレゼンテーションの作成者を取得または設定します。 |
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
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase ドキュメント プロパティを取得または設定します。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase ドキュメント プロパティを取得または設定します。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | コレクションに実際に含まれているカスタムプロパティの数を返します。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 指定したインデックスのカスタムプロパティ名を返します。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 指定された名前のカスタムプロパティの存在を確認します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | カスタムプロパティから名前付きブール値を取得します。 |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | カスタムプロパティから名前付き整数値を取得します。 |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | カスタムプロパティから名前付き DateTime 値を取得します。 |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | カスタムプロパティから名前付き文字列値を取得します。 |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | カスタムプロパティから名前付き float 値を取得します。 |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | カスタムプロパティから名前付き double 値を取得します。 |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 名前付きブール カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 名前付き整数 カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 名前付き DateTime カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 名前付き文字列 カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 名前付き float カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 名前付き double カスタムプロパティを設定します。 |
| [clearCustomProperties()](#clearCustomProperties--) | すべてのカスタムプロパティを削除します。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | カスタム ドキュメント プロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK メタデータ)。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | すべての組み込みプロパティの既定値をクリアして設定します。 |
| [getScaleCrop()](#getScaleCrop--) | ドキュメントのサムネイルの表示モードを示します。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | ドキュメントのサムネイルの表示モードを示します。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | このパート内の 1 つ以上のハイパーリンクが、プロデューサーによってこのパートだけで更新されたことを指定します。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | このパート内の 1 つ以上のハイパーリンクが、プロデューサーによってこのパートだけで更新されたことを指定します。 |
| [getSlides()](#getSlides--) | プレゼンテーション ドキュメントのスライド総数を返します。 |
| [getHiddenSlides()](#getHiddenSlides--) | プレゼンテーション ドキュメントの非表示スライド数を返します。 |
| [getNotes()](#getNotes--) | ノートが含まれるプレゼンテーションのスライド数を返します。 |
| [getParagraphs()](#getParagraphs--) | 該当する場合、ドキュメント内に見つかった段落の総数を返します。 |
| [getWords()](#getWords--) | ドキュメントに含まれる単語数の合計を返します。 |
| [getMultimediaClips()](#getMultimediaClips--) | ドキュメントに存在する音声またはビデオ クリップの総数を返します。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 各ドキュメント パートのタイトルを指定します。 |
| [getHeadingPairs()](#getHeadingPairs--) | ドキュメント パートのグループ化と各グループ内のパート数を示します。 |
| [deepClone()](#deepClone--) | 現在のオブジェクトをクローンします。 |
| [cloneT()](#cloneT--) | 現在のオブジェクトをクローンします。 |

### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

クラス [DocumentProperties](../../com.aspose.slides/documentproperties) の新しいインスタンスを初期化します。

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

アプリ バージョンを返します。読み取り専用 String。

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

マネージャープロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

マネージャープロパティを取得または設定します。読み取り/書き込み String。

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

プレゼンテーションのテーマを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

プレゼンテーションのテーマを取得または設定します。読み取り/書き込み String。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

プレゼンテーションの作成者を取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

プレゼンテーションの作成者を取得または設定します。読み取り/書き込み String。

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
プレゼンテーションが作成された日時を返します。値は UTC です。読み取り/書き込み java.util.Date。

**戻り値:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


プレゼンテーションが作成された日時を返します。値は UTC です。読み取り/書き込み java.util.Date。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


プレゼンテーションが最後に変更された日時を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です (IPresentation オブジェクトの保存プロセス中に内部で更新されます)。[IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) メソッドで返される DocumentProperties インスタンスを介して変更できます。例は [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッドの概要をご覧ください。

**戻り値:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


プレゼンテーションが最後に変更された日時を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です (IPresentation オブジェクトの保存プロセス中に内部で更新されます)。[IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) メソッドで返される DocumentProperties インスタンスを介して変更できます。例は [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッドの概要をご覧ください。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


プレゼンテーションが最後に印刷された日時を返します。読み取り/書き込み java.util.Date。

**戻り値:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


プレゼンテーションが最後に印刷された日時を返します。読み取り/書き込み java.util.Date。

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


HyperlinkBase ドキュメント プロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


HyperlinkBase ドキュメント プロパティを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


コレクションに実際に含まれるカスタム プロパティの数を返します。読み取り専用 int。

**戻り値:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


指定されたインデックスのカスタム プロパティ名を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | カスタム プロパティを取得する 0 ベースのインデックス。 |

**戻り値:**
java.lang.String - 指定されたインデックスのカスタム プロパティ名。
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


指定された名前に関連付けられたカスタム プロパティを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 削除するカスタム プロパティの名前。 |

**戻り値:**
boolean - プロパティが削除された場合は true、そうでなければ false。
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```


指定された名前のカスタム プロパティの有無を確認します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 確認するカスタム プロパティの名前。 |

**戻り値:**
boolean - プロパティが存在すれば true、存在しなければ false。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


指定された名前に関連付けられたカスタム プロパティを取得または設定します。読み取り/書き込み Object。

--------------------

値は **int**、**float**、**String**、**boolean** または **Date** にできます。

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


指定された名前に関連付けられたカスタム プロパティを取得または設定します。読み取り/書き込み Object。

--------------------

値は **int**、**float**、**String**、**boolean** または **Date** にできます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


カスタム プロパティから名前付きの boolean 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | boolean[] | カスタム プロパティの値 |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


カスタム プロパティから名前付きの整数値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | int[] | カスタム プロパティの値 |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


カスタム プロパティから名前付きの DateTime 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | java.util.Date[] | カスタム プロパティの値 |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


カスタム プロパティから名前付きの文字列値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | java.lang.String[] | カスタム プロパティの値 |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


カスタム プロパティから名前付きの float 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | float[] | カスタム プロパティの値 |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


カスタム プロパティから名前付きの double 値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前。 |
| value | double[] | カスタム プロパティの値 |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


名前付きの boolean カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | boolean | カスタム プロパティの値 |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


名前付きの整数カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | int | カスタム プロパティの値 |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


名前付きの DateTime カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | java.util.Date | カスタム プロパティの値 |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


名前付きの文字列カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | java.lang.String | カスタム プロパティの値 |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


名前付きの float カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | float | カスタム プロパティの値 |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


名前付きの double カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | double | カスタム プロパティの値 |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


すべてのカスタム プロパティを削除します。

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```


カスタム ドキュメント プロパティ (Microsoft Information Protection SDK メタデータ) から感度ラベルの配列を取得します。

--------------------

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
>          // ラベルをコレクションに追加します
>          // ここでラベル情報の有効性（ラベルが利用可能かなど）をチェックすることができます
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


ドキュメント サムネイルの表示モードを示します。この要素を **true** に設定すると、サムネイルがディスプレイに合わせて拡大縮小されます。この要素を **false** に設定すると、ディスプレイに収まるセクションのみが表示されるようにサムネイルが切り取られます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```


ドキュメント サムネイルの表示モードを示します。この要素を **true** に設定すると、サムネイルがディスプレイに合わせて拡大縮小されます。この要素を **false** に設定すると、ディスプレイに収まるセクションのみが表示されるようにサムネイルが切り取られます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```


ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されていることを示し、**false** に設定するとハイパーリンクが古いことを示します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. 読み書き可能な boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

このパート内のhyperlinkがプロデューサーによって専用に更新されたことを示します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいhyperlinkでhyperlink関係を更新する必要があります。読み書き可能な boolean.

**戻り値:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

このパート内のhyperlinkがプロデューサーによって専用に更新されたことを示します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいhyperlinkでhyperlink関係を更新する必要があります。読み書き可能な boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

プレゼンテーションドキュメント内のスライドの総数を返します。読み取り専用 int.

**戻り値:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

プレゼンテーションドキュメント内の非表示スライドの数を返します。読み取り専用 int.

**戻り値:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

ノートを含むプレゼンテーション内のスライド数を返します。読み取り専用 int.

**戻り値:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

該当する場合、ドキュメント内で見つかった段落の総数を返します。読み取り専用 int.

**戻り値:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

ドキュメントに含まれる単語の総数を返します。読み取り専用 int.

**戻り値:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

ドキュメントに存在する音声またはビデオクリップの総数を返します。読み取り専用 int.

**戻り値:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

各ドキュメントパートのタイトルを指定します。これらのパートはドキュメントパートではなく、ドキュメントセクションの概念的表現です。読み取り専用 String[].

**戻り値:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

ドキュメントパートのグループ化と各グループ内のパート数を示します。読み取り専用 IHeadingPair[].

**戻り値:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

現在のオブジェクトをクローンします

**戻り値:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

現在のオブジェクトをクローンします

**戻り値:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone