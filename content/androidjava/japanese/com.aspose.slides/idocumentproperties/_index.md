---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: プレゼンテーションのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

プレゼンテーションのプロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | アプリのバージョンを返します。 |
| [getNameOfApplication()](#getNameOfApplication--) | アプリケーションの名前を取得または設定します。 |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | アプリケーションの名前を取得または設定します。 |
| [getCompany()](#getCompany--) | 会社プロパティを取得または設定します。 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 会社プロパティを取得または設定します。 |
| [getManager()](#getManager--) | マネージャーのプロパティを取得または設定します。 |
| [setManager(String value)](#setManager-java.lang.String-) | マネージャーのプロパティを取得または設定します。 |
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
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase ドキュメントプロパティを取得または設定します。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase ドキュメントプロパティを取得または設定します。 |
| [getScaleCrop()](#getScaleCrop--) | ドキュメントサムネイルの表示モードを示します。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | ドキュメントサムネイルの表示モードを示します。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | このパート内の1つ以上のハイパーリンクが、プロデューサーによってこのパート内でのみ更新されたことを指定します。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | このパート内の1つ以上のハイパーリンクが、プロデューサーによってこのパート内でのみ更新されたことを指定します。 |
| [getSlides()](#getSlides--) | プレゼンテーションドキュメントの総スライド数を指定します。 |
| [getHiddenSlides()](#getHiddenSlides--) | プレゼンテーションドキュメントの非表示スライド数を指定します。 |
| [getNotes()](#getNotes--) | ノートを含むプレゼンテーションのスライド数を指定します。 |
| [getParagraphs()](#getParagraphs--) | 該当する場合、ドキュメント内に見つかった段落の総数を指定します。 |
| [getWords()](#getWords--) | ドキュメントに含まれる総単語数を指定します。 |
| [getMultimediaClips()](#getMultimediaClips--) | ドキュメントに存在する音声またはビデオクリップの総数を指定します。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 各ドキュメントパートのタイトルを指定します。 |
| [getHeadingPairs()](#getHeadingPairs--) | ドキュメントパートのグループ化と各グループ内のパート数を示します。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | コレクションに実際に含まれるカスタムプロパティの数を返します。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 指定された名前のカスタムプロパティが存在するか確認します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。 |
| [clearCustomProperties()](#clearCustomProperties--) | すべてのカスタムプロパティを削除します。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | すべての組み込みプロパティをクリアし、デフォルト値を設定します。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 指定された名前のブール型カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 指定された名前の整数型カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 指定された名前の DateTime カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 指定された名前の文字列カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 指定された名前の浮動小数点型カスタムプロパティを設定します。 |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 指定された名前の倍精度浮動小数点型カスタムプロパティを設定します。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

アプリのバージョンを返します。読み取り専用 String。

--------------------

この要素の内容は XX.YYYY の形式である必要があります。X と Y は数値を表します。これに従わない場合、ドキュメントは非準拠と見なされます。Aspose.Slides はバージョンを XX.YY.ZZ の形式で表します。ここで:  
XX - メジャーバージョン  
YY - マイナーバージョン  
ZZ - パッチバージョン  
例えば、値 23.0105 は Aspose.Slides バージョン 23.1.5 を意味します。

**戻り値:**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

アプリケーションの名前を取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

アプリケーションの名前を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

会社プロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

会社プロパティを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

マネージャーのプロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

マネージャーのプロパティを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

プレゼンテーションの意図された形式を取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

プレゼンテーションの意図された形式を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

プレゼンテーションが複数のユーザーで共有されているかどうかを判定します。読み取り/書き込み boolean。

**戻り値:**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

プレゼンテーションが複数のユーザーで共有されているかどうかを判定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

アプリケーションのテンプレートを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

アプリケーションのテンプレートを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

プレゼンテーションの総編集時間です。読み取り/書き込み double。

**戻り値:**  
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

プレゼンテーションの総編集時間です。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

プレゼンテーションのタイトルを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

プレゼンテーションのタイトルを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

プレゼンテーションの件名を取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

プレゼンテーションの件名を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

プレゼンテーションの作成者を取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

プレゼンテーションの作成者を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

プレゼンテーションのキーワードを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

プレゼンテーションのキーワードを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

プレゼンテーションのコメントを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

プレゼンテーションのコメントを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

プレゼンテーションのカテゴリを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public void 

はじめません

```

プレゼンテーションのカテゴリを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

プレゼンテーションが作成された日付を返します。値は UTC です。読み取り/書き込み java.util.Date。

**戻り値:**  
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

プレゼンテーションが作成された日付を返します。値は UTC です。読み取り/書き込み java.util.Date。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

プレゼンテーションが最後に変更された日付を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用 (IPresentation オブジェクトの保存プロセス中に内部で更新されます)。[IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) メソッドで返される DocumentProperties インスタンスを介して変更可能です。例は [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッド概要をご参照ください。

**戻り値:**  
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

プレゼンテーションが最後に変更された日付を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用 (IPresentation オブジェクトの保存プロセス中に内部で更新されます)。[IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) メソッドで返される DocumentProperties インスタンスを介して変更可能です。例は [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッド概要をご参照ください。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

プレゼンテーションが最後に印刷された日付を返します。読み取り/書き込み java.util.Date。

**戻り値:**  
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

プレゼンテーションが最後に印刷された日付を返します。読み取り/書き込み java.util.Date。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

プレゼンテーションを最後に変更した人物の名前を取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

プレゼンテーションを最後に変更した人物の名前を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

プレゼンテーションのリビジョン番号を取得または設定します。読み取り/書き込み int。

**戻り値:**  
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

プレゼンテーションのリビジョン番号を取得または設定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

プレゼンテーションのコンテンツステータスを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

プレゼンテーションのコンテンツステータスを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

プレゼンテーションのコンテンツタイプを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

プレゼンテーションのコンテンツタイプを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

HyperlinkBase ドキュメントプロパティを取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

HyperlinkBase ドキュメントプロパティを取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

ドキュメントサムネイルの表示モードを示します。**true** に設定するとサムネイルがディスプレイに合わせて拡大縮小されます。**false** に設定するとサムネイルがトリミングされ、ディスプレイに合う部分だけが表示されます。読み取り/書き込み boolean。

**戻り値:**  
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

ドキュメントサムネイルの表示モードを示します。**true** に設定するとサムネイルがディスプレイに合わせて拡大縮小されます。**false** に設定するとサムネイルがトリミングされ、ディスプレイに合う部分だけが表示されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

ドキュメント内のハイパーリンクが最新かどうかを示します。**true** に設定するとハイパーリンクが更新されていることを示し、**false** に設定するとハイパーリンクが古いことを示します。読み取り/書き込み boolean。

**戻り値:**  
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

ドキュメント内のハイパーリンクが最新かどうかを示します。**true** に設定するとハイパーリンクが更新されていることを示し、**false** に設定するとハイパーリンクが古いことを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

このパート内の1つ以上のハイパーリンクが、プロデューサーによってこのパート内でのみ更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新します。読み取り/書き込み boolean。

**戻り値:**  
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

このパート内の1つ以上のハイパーリンクが、プロデューサーによってこのパート内でのみ更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

プレゼンテーションドキュメントの総スライド数を指定します。読み取り専用 int。

**戻り値:**  
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

プレゼンテーションドキュメントの非表示スライド数を指定します。読み取り専用 int。

**戻り値:**  
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

ノートを含むプレゼンテーションのスライド数を指定します。読み取り専用 int。

**戻り値:**  
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

該当する場合、ドキュメント内に見つかった段落の総数を指定します。読み取り専用 int。

**戻り値:**  
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

ドキュメントに含まれる総単語数を指定します。読み取り専用 int。

**戻り値:**  
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

ドキュメントに存在する音声またはビデオクリップの総数を指定します。読み取り専用 int。

**戻り値:**  
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

各ドキュメントパートのタイトルを指定します。これらのパートは実際のドキュメントパートではなく、ドキュメントセクションの概念的表現です。読み取り専用 String[]。

**戻り値:**  
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

ドキュメントパートのグループ化と各グループ内のパート数を示します。読み取り専用 IHeadingPair[]。

**戻り値:**  
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

コレクションに実際に含まれるカスタムプロパティの数を返します。読み取り専用 int。

**戻り値:**  
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

指定されたインデックスのカスタムプロパティ名を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得するカスタムプロパティのゼロベースインデックス。 |

**戻り値:**  
java.lang.String - 指定されたインデックスのカスタムプロパティ名。

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
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
public abstract boolean containsCustomProperty(String name)
```

指定された名前のカスタムプロパティが存在するか確認します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 確認するカスタムプロパティの名前。 |

**戻り値:**  
boolean - プロパティが存在すれば true、存在しなければ false。

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

指定された名前に関連付けられたカスタムプロパティを取得または設定します。読み取り/書き込み Object。

--------------------

値は **int**, **float**, **double**, **String**, **boolean** または **Date** のいずれかです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**戻り値:**  
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

指定された名前に関連付けられたカスタムプロパティを取得または設定します。読み取り/書き込み Object。

--------------------

値は **int**, **float**, **double**, **String**, **boolean** または **Date** のいずれかです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

すべてのカスタムプロパティを削除します。

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

すべての組み込みプロパティをクリアし、デフォルト値を設定します。

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

指定された名前のブール型カスタムプロパティ値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | boolean[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

指定された名前の整数型カスタムプロパティ値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | int[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

指定された名前の DateTime 型カスタムプロパティ値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | java.util.Date[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

指定された名前の文字列型カスタムプロパティ値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | java.lang.String[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

指定された名前の浮動小数点型カスタムプロパティ値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前 |
| value | float[] | カスタムプロパティの値 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

指定された名前の倍精度浮動小数点型カスタムプロパティ値を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタムプロパティの名前。 |
| value | double[] | カスタムプロパティの値 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

指定された名前のブール型カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | boolean | カスタムプロパティの値 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

指定された名前の整数型カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | int | カスタムプロパティの値 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

指定された名前の DateTime 型カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | java.util.Date | カスタムプロパティの値 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

指定された名前の文字列型カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | java.lang.String | カスタムプロパティの値 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

指定された名前の浮動小数点型カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | float | カスタムプロパティの値 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

指定された名前の倍精度浮動小数点型カスタムプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタムプロパティの名前 |
| value | double | カスタムプロパティの値 |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

カスタムドキュメントプロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK メタデータ)。

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**  
com.aspose.slides.ISensitivityLabel[]