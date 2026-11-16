---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
weight: 5730
url: /ja/aspose.slides/idocumentproperties/
---
## IDocumentProperties インターフェイス

プレゼンテーションのプロパティを表します。

```csharp
public interface IDocumentProperties
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | アプリケーションのテンプレートを取得または設定します。Read/write String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | アプリのバージョンを取得します。Read-only String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | プレゼンテーションの作成者を取得または設定します。Read/write String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | プレゼンテーションのカテゴリを取得または設定します。Read/write String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | プレゼンテーションのコメントを取得または設定します。Read/write String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 会社プロパティを取得または設定します。Read/write String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | プレゼンテーションのコンテンツステータスを取得または設定します。Read/write String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | プレゼンテーションのコンテンツタイプを取得または設定します。Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | コレクションに実際に含まれるカスタムプロパティの数を取得します。Read-only Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | プレゼンテーションが作成された日付を取得または設定します。値は UTC です。Read/write DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | ドキュメントパーツのグループ化と各グループのパーツ数を示します。Read-only IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | プレゼンテーションドキュメント内の非表示スライド数を指定します。Read-only Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase ドキュメントプロパティを取得または設定します。Read/write String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | このパート内の1つ以上のハイパーリンクがプロデューサーによってこのパートだけで更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。Read/write Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。Read/write Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | プレゼンテーションのキーワードを取得または設定します。Read/write String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | プレゼンテーションが最後に印刷された日付を取得します。Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | プレゼンテーションを最後に変更した人物の名前を取得または設定します。Read/write String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | プレゼンテーションが最後に変更された日付を取得します。値は UTC です。Presentation.DocumentProperties の場合はRead-onlyです（IPresentation オブジェクトの保存プロセス中に内部で更新されるため）。[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) メソッドで返される DocumentProperties インスタンスを介して変更できます。[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) メソッドの概要の例をご覧ください。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されていることを示します。この要素を **false** に設定するとハイパーリンクが古いことを示します。Read/write Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | マネージャープロパティを取得または設定します。Read/write String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | ドキュメントに含まれるサウンドまたはビデオクリップの総数を指定します。Read-only Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | アプリケーションの名前を取得または設定します。Read/write String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | ノートを含むプレゼンテーションのスライド数を指定します。Read-only Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 該当する場合、ドキュメント内に見つかった段落の総数を指定します。Read-only Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | プレゼンテーションの意図された形式を取得または設定します。Read/write String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | プレゼンテーションのリビジョン番号を取得または設定します。Read/write Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルをディスプレイに合わせて拡大縮小できます。この要素を **false** に設定するとサムネイルをクロップしてディスプレイに適合するセクションのみ表示できます。Read/write Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | プレゼンテーションが複数のユーザー間で共有されているかどうかを決定します。Read/write Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | プレゼンテーションドキュメントのスライド総数を指定します。Read-only Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | プレゼンテーションの件名を取得または設定します。Read/write String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | プレゼンテーションのタイトルを取得または設定します。Read/write String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 各ドキュメントパートのタイトルを指定します。これらのパートはドキュメントパートではなく、ドキュメントセクションの概念的な表現です。Read-only string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | プレゼンテーションの総編集時間を取得または設定します。Read/write TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | ドキュメントに含まれる総単語数を指定します。Read-only Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | すべての組み込みプロパティのデフォルト値をクリアして設定します。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | すべてのカスタムプロパティを削除します。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 指定された名前のカスタムプロパティの存在を確認します。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | カスタムプロパティから名前付きブール値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | カスタムプロパティから名前付き DateTime 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | カスタムプロパティから名前付き double 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | カスタムプロパティから名前付き float 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | カスタムプロパティから名前付き整数値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | カスタムプロパティから名前付き文字列値を取得します。 |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | カスタムドキュメントプロパティから感度ラベルの配列を取得します（Microsoft Information Protection SDK メタデータ）。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 名前付きブール型カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 名前付き DateTime カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 名前付き double カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 名前付き float カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 名前付き整数型カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 名前付き文字列型カスタムプロパティを設定します。 |

### 参照

* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->