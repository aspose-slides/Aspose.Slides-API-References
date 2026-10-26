---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Represents properties of a presentation.
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
| [getManager()](#getManager--) | マネージャープロパティを取得または設定します。 |
| [setManager(String value)](#setManager-java.lang.String-) | マネージャープロパティを取得または設定します。 |
| [getPresentationFormat()](#getPresentationFormat--) | プレゼンテーションの意図した形式を取得または設定します。 |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | プレゼンテーションの意図した形式を取得または設定します。 |
| [getSharedDoc()](#getSharedDoc--) | プレゼンテーションが複数のユーザー間で共有されているかどうかを判定します。 |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | プレゼンテーションが複数のユーザー間で共有されているかどうかを判定します。 |
| [getApplicationTemplate()](#getApplicationTemplate--) | アプリケーションのテンプレートを取得または設定します。 |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | アプリケーションのテンプレートを取得または設定します。 |
| [getTotalEditingTime()](#getTotalEditingTime--) | プレゼンテーションの総編集時間です。 |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | プレゼンテーションの総編集時間です。 |
| [getTitle()](#getTitle--) | プレゼンテーションのタイトルを取得または設定します。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | プレゼンテーションのタイトルを取得または設定します。 |
| [getSubject()](#getSubject--) | プレゼンテーションのサブジェクトを取得または設定します。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | プレゼンテーションのサブジェクトを取得または設定します。 |
| [getAuthor()](#getAuthor--) | プレゼンテーションの作成者を取得または設定します。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | プレゼンテーションの作成者を取得または設定します。 |
| [getKeywords()](#getKeywords--) | プレゼンテーションのキー ワードを取得または設定します。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | プレゼンテーションのキー ワードを取得または設定します。 |
| [getComments()](#getComments--) | プレゼンテーションのコメントを取得または設定します。 |
| [setComments(String value)](#setComments-java.lang.String-) | プレゼンテーションのコメントを取得または設定します。 |
| [getCategory()](#getCategory--) | プレゼンテーションのカテゴリを取得または設定します。 |
| [setCategory(String value)](#setCategory-java.lang.String-) | プレゼンテーションのカテゴリを取得または設定します。 |
| [getCreatedTime()](#getCreatedTime--) | プレゼンテーションが作成された日時を返します。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | プレゼンテーションが作成された日時を返します。 |
| [getLastSavedTime()](#getLastSavedTime--) | プレゼンテーションが最後に変更された日時を返します。 |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | プレゼンテーションが最後に変更された日時を返します。 |
| [getLastPrinted()](#getLastPrinted--) | プレゼンテーションが最後に印刷された日時を返します。 |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | プレゼンテーションが最後に印刷された日時を返します。 |
| [getLastSavedBy()](#getLastSavedBy--) | プレゼンテーションを最後に変更した人物の名前を取得または設定します。 |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | プレゼンテーションを最後に変更した人物の名前を取得または設定します。 |
| [getRevisionNumber()](#getRevisionNumber--) | プレゼンテーションのリビジョン番号を取得または設定します。 |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | プレゼンテーションのリビジョン番号を取得または設定します。 |
| [getContentStatus()](#getContentStatus--) | プレゼンテーションのコンテンツ ステータスを取得または設定します。 |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | プレゼンテーションのコンテンツ ステータスを取得または設定します。 |
| [getContentType()](#getContentType--) | プレゼンテーションのコンテンツ タイプを取得または設定します。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | プレゼンテーションのコンテンツ タイプを取得または設定します。 |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase ドキュメント プロパティを取得または設定します。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase ドキュメント プロパティを取得または設定します。 |
| [getScaleCrop()](#getScaleCrop--) | ドキュメント サムネイルの表示モードを示します。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | ドキュメント サムネイルの表示モードを示します。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | ドキュメント内のハイパーリンクが最新かどうかを示します。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | このパート内の 1 つ以上のハイパーリンクが、プロデューサーによってこのパートだけで更新されたことを指定します。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | このパート内の 1 つ以上のハイパーリンクが、プロデューサーによってこのパートだけで更新されたことを指定します。 |
| [getSlides()](#getSlides--) | プレゼンテーション ドキュメント内のスライド総数を指定します。 |
| [getHiddenSlides()](#getHiddenSlides--) | プレゼンテーション ドキュメント内の非表示スライド数を指定します。 |
| [getNotes()](#getNotes--) | ノートを含むスライドの数を指定します。 |
| [getParagraphs()](#getParagraphs--) | 該当する場合、ドキュメント内で見つかった段落の総数を指定します。 |
| [getWords()](#getWords--) | ドキュメント内の単語総数を指定します。 |
| [getMultimediaClips()](#getMultimediaClips--) | ドキュメントに含まれる音声またはビデオ クリップの総数を指定します。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 各ドキュメント パートのタイトルを指定します。 |
| [getHeadingPairs()](#getHeadingPairs--) | ドキュメント パートのグループ化と各グループ内のパート数を示します。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | コレクションに実際に含まれるカスタム プロパティの数を返します。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 指定したインデックスのカスタム プロパティ名を返します。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 指定された名前に関連付けられたカスタム プロパティを削除します。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 指定された名前のカスタム プロパティの存在をチェックします。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 指定された名前に関連付けられたカスタム プロパティを取得または設定します。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定された名前に関連付けられたカスタム プロパティを取得または設定します。 |
| [clearCustomProperties()](#clearCustomProperties--) | すべてのカスタム プロパティを削除します。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | すべての組み込みプロパティをクリアし、デフォルト値を設定します。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | カスタム プロパティから名前付きブール値を取得します。 |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | カスタム プロパティから名前付き整数値を取得します。 |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | カスタム プロパティから名前付き DateTime 値を取得します。 |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | カスタム プロパティから名前付き文字列値を取得します。 |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | カスタム プロパティから名前付き float 値を取得します。 |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | カスタム プロパティから名前付き double 値を取得します。 |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 名前付きブール カスタム プロパティを設定します。 |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 名前付き整数カスタム プロパティを設定します。 |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 名前付き DateTime カスタム プロパティを設定します。 |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 名前付き文字列カスタム プロパティを設定します。 |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 名前付き float カスタム プロパティを設定します。 |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 名前付き double カスタム プロパティを設定します。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | カスタム ドキュメント プロパティから Sensitivity ラベルの配列を取得します (Microsoft Information Protection SDK Metadata)。 |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

アプリのバージョンを返します。読み取り専用 String.

--------------------

この要素の内容は XX.YYYY の形式である必要があります。X と Y は数値を表します。そうでない場合、ドキュメントは非準拠とみなされます。Aspose.Slides はバージョンを XX.YY.ZZ の形式で表します。: XX - メジャーバージョン、YY - マイナーバージョン、ZZ - パッチバージョン 例として、値 23.0105 は Aspose.Slides バージョン 23.1.5 を意味します。

**戻り値:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

アプリケーションの名前を取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

アプリケーションの名前を取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

会社プロパティを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

会社プロパティを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

マネージャープロパティを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

マネージャープロパティを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

プレゼンテーションの意図した形式を取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

プレゼンテーションの意図した形式を取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

プレゼンテーションが複数のユーザー間で共有されているかどうかを判定します。読み書き可能 boolean.

**戻り値:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

プレゼンテーションが複数のユーザー間で共有されているかどうかを判定します。読み書き可能 boolean.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

アプリケーションのテンプレートを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

アプリケーションのテンプレートを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

プレゼンテーションの総編集時間です。読み書き可能 double.

**戻り値:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

プレゼンテーションの総編集時間です。読み書き可能 double.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

プレゼンテーションのタイトルを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

プレゼンテーションのタイトルを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

プレゼンテーションのサブジェクトを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

プレゼンテーションのサブジェクトを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

プレゼンテーションの作成者を取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

プレゼンテーションの作成者を取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

プレゼンテーションのキー ワードを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

プレゼンテーションのキー ワードを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

プレゼンテーションのコメントを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

プレゼンテーションのコメントを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

プレゼンテーションのカテゴリを取得または設定します。読み書き可能 String.

**戻り値:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

プレゼンテーションのカテゴリを取得または設定します。読み書き可能 String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


プレゼンテーションが作成された日時を返します。値は UTC です。読み書き可能 java.util.Date。

**戻り値:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


プレゼンテーションが作成された日時を設定します。値は UTC です。読み書き可能 java.util.Date。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```


プレゼンテーションが最後に変更された日時を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です (保存プロセス中に内部で更新されます)。メソッド [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) が返す DocumentProperties インスタンスを介して変更できます。例は [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッドの概要をご参照ください。

**戻り値:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```


プレゼンテーションが最後に変更された日時を設定します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です (保存プロセス中に内部で更新されます)。メソッド [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) が返す DocumentProperties インスタンスを介して変更できます。例は [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) メソッドの概要をご参照ください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```


プレゼンテーションが最後に印刷された日時を返します。読み書き可能 java.util.Date。

**戻り値:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```


プレゼンテーションが最後に印刷された日時を設定します。読み書き可能 java.util.Date。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```


最後にプレゼンテーションを変更した人物の名前を取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```


最後にプレゼンテーションを変更した人物の名前を取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```


プレゼンテーションのリビジョン番号を取得または設定します。読み書き可能 int。

**戻り値:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```


プレゼンテーションのリビジョン番号を取得または設定します。読み書き可能 int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```


プレゼンテーションのコンテンツステータスを取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```


プレゼンテーションのコンテンツステータスを取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


プレゼンテーションのコンテンツタイプを取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```


プレゼンテーションのコンテンツタイプを取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```


HyperlinkBase ドキュメントプロパティを取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```


HyperlinkBase ドキュメントプロパティを取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```


ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定すると、サムネイルをディスプレイに合わせて拡大できます。この要素を **false** に設定すると、ディスプレイに合わせるセクションのみを表示するようにサムネイルを切り抜きます。読み書き可能 boolean。

**戻り値:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```


ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定すると、サムネイルをディスプレイに合わせて拡大できます。この要素を **false** に設定すると、ディスプレイに合わせるセクションのみを表示するようにサムネイルを切り抜きます。読み書き可能 boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```


ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定すると、ハイパーリンクが更新されていることを示します。この要素を **false** に設定すると、ハイパーリンクが古いことを示します。読み書き可能 boolean。

**戻り値:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```


ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定すると、ハイパーリンクが更新されていることを示します。この要素を **false** に設定すると、ハイパーリンクが古いことを示します。読み書き可能 boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```


この部品内の 1 つ以上のハイパーリンクが、プロデューサーによってこの部品だけで更新されたことを示します。次にこの文書を開くプロデューサーは、この部品で指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。読み書き可能 boolean。

**戻り値:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```


この部品内の 1 つ以上のハイパーリンクが、プロデューサーによってこの部品だけで更新されたことを示します。次にこの文書を開くプロデューサーは、この部品で指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。読み書き可能 boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```


プレゼンテーション ドキュメントのスライド総数を指定します。読み取り専用 int。

**戻り値:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```


プレゼンテーション ドキュメント内の非表示スライド数を指定します。読み取り専用 int。

**戻り値:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```


ノートを含むスライドの数を指定します。読み取り専用 int。

**戻り値:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```


ドキュメント内に見つかった段落の総数を指定します（該当する場合）。読み取り専用 int。

**戻り値:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```


ドキュメントに含まれる単語の総数を指定します。読み取り専用 int。

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


各ドキュメント部品のタイトルを指定します。これらの部品は実際のドキュメント部品ではなく、ドキュメントセクションの概念的表現です。読み取り専用 String[]。

**戻り値:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```


ドキュメント部品のグループ化と各グループ内の部品数を示します。読み取り専用 IHeadingPair[]。

**戻り値:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```


コレクションに実際に含まれるカスタム プロパティの数を返します。読み取り専用 int。

**戻り値:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```


指定したインデックスのカスタム プロパティ名を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得するカスタム プロパティのゼロベースインデックス。 |

**戻り値:**
java.lang.String - 指定インデックスのカスタム プロパティ名。
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```


指定された名前に関連付けられたカスタム プロパティを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 削除するカスタム プロパティの名前。 |

**戻り値:**
boolean - プロパティが削除された場合は true、そうでなければ false。
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```


指定された名前のカスタム プロパティが存在するかどうかを確認します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 確認するカスタム プロパティの名前。 |

**戻り値:**
boolean - プロパティが存在すれば true、存在しなければ false。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```


指定された名前に関連付けられたカスタム プロパティを取得または設定します。読み書き可能 Object。

--------------------

値は **int**、**float**、**double**、**String**、**boolean** または **Date** にできます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**戻り値:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```


指定された名前に関連付けられたカスタム プロパティを取得または設定します。読み書き可能 Object。

--------------------

値は **int**、**float**、**double**、**String**、**boolean** または **Date** にできます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```


すべてのカスタム プロパティを削除します。

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```


すべての builtIn プロパティをクリアし、デフォルト値を設定します。

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```


カスタム プロパティから指定された boolean 値を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | boolean[] | カスタム プロパティの値 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```


カスタム プロパティから指定された整数値を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | int[] | カスタム プロパティの値 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```


カスタム プロパティから指定された DateTime 値を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | java.util.Date[] | カスタム プロパティの値 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```


カスタム プロパティから指定された文字列値を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | java.lang.String[] | カスタム プロパティの値 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```


カスタム プロパティから指定された float 値を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | float[] | カスタム プロパティの値 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```


カスタム プロパティから指定された double 値を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 取得するカスタム プロパティの名前 |
| value | double[] | カスタム プロパティの値 |
| 名前 | java.lang.String | 取得するカスタム プロパティの名前。 |
| 値 | double[] | カスタム プロパティの値 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

名前付きのブール型カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | boolean | カスタム プロパティの値 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

名前付きの整数型カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | int | カスタム プロパティの値 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

名前付きの DateTime カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | java.util.Date | カスタム プロパティの値 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

名前付きの文字列カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | java.lang.String | カスタム プロパティの値 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

名前付きの float カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | float | カスタム プロパティの値 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

名前付きの double カスタム プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 設定するカスタム プロパティの名前 |
| value | double | カスタム プロパティの値 |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

カスタム ドキュメント プロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK メタデータ)。

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