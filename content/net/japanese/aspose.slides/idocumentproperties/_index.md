---
title: IDocumentProperties
second_title: Aspose.Slides for .NET API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
weight: 5710
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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | アプリケーションのテンプレートを取得または設定します。読み取り/書き込み String。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | アプリケーションのバージョンを取得します。読み取り専用 String。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | プレゼンテーションの作成者を取得または設定します。読み取り/書き込み String。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | プレゼンテーションのカテゴリを取得または設定します。読み取り/書き込み String。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | プレゼンテーションのコメントを取得または設定します。読み取り/書き込み String。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 会社プロパティを取得または設定します。読み取り/書き込み String。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | プレゼンテーションのコンテンツステータスを取得または設定します。読み取り/書き込み String。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | プレゼンテーションのコンテンツタイプを取得または設定します。読み取り/書き込み String。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | コレクションに実際に含まれるカスタムプロパティの数を取得します。読み取り専用 Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | プレゼンテーションが作成された日時を取得します。値は UTC です。読み取り/書き込み DateTime。 |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | ドキュメントパーツのグループ化と各グループ内のパーツ数を示します。読み取り専用 IHeadingPair[]。 |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | プレゼンテーションドキュメント内の非表示スライド数を指定します。読み取り専用 Int32。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase ドキュメントプロパティを取得または設定します。読み取り/書き込み String。 |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | このパート内のハイパーリンクがプロデューサーによってこのパートだけで更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。読み取り/書き込み Boolean。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。読み取り/書き込み Object。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | プレゼンテーションのキーワードを取得または設定します。読み取り/書き込み String。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | プレゼンテーションが最後に印刷された日付を取得します。読み取り/書き込み DateTime。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | プレゼンテーションを最後に変更した人物の名前を取得または設定します。読み取り/書き込み String。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | プレゼンテーションが最後に変更された日時を取得します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です（IPresentation オブジェクトの保存プロセス中に内部で更新されるため）。[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) メソッドが返す DocumentProperties インスタンスを介して変更可能です。例については [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) メソッドの概要をご覧ください。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されたことを示します。この要素を **false** に設定するとハイパーリンクが古いことを示します。読み取り/書き込み Boolean。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | マネージャー プロパティを取得または設定します。読み取り/書き込み String。 |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | ドキュメントに含まれるサウンドまたはビデオクリップの総数を指定します。読み取り専用 Int32。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | アプリケーションの名前を取得または設定します。読み取り/書き込み String。 |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | ノートを含むプレゼンテーションのスライド数を指定します。読み取り専用 Int32。 |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 該当する場合、ドキュメント内に見つかった段落の総数を指定します。読み取り専用 Int32。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | プレゼンテーションの意図された形式を取得または設定します。読み取り/書き込み String。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | プレゼンテーションのリビジョン番号を取得または設定します。読み取り/書き込み Int32。 |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定すると、サムネイルをディスプレイに合わせて拡大できます。この要素を **false** に設定すると、ディスプレイに適合するセクションだけを表示するようにサムネイルを切り取ります。読み取り/書き込み Boolean。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | プレゼンテーションが複数のユーザー間で共有されているかどうかを決定します。読み取り/書き込み Boolean。 |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | プレゼンテーションドキュメント内のスライド総数を指定します。読み取り専用 Int32。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | プレゼンテーションの件名を取得または設定します。読み取り/書き込み String。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | プレゼンテーションのタイトルを取得または設定します。読み取り/書き込み String。 |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 各ドキュメントパートのタイトルを指定します。これらのパートは実際のドキュメントパートではなく、ドキュメントセクションの概念的表現です。読み取り専用 string[]。 |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | プレゼンテーションの総編集時間です。読み取り/書き込み TimeSpan。 |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | ドキュメントに含まれる単語の総数を指定します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | すべての組み込みプロパティをクリアし、デフォルト値を設定します。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | すべてのカスタムプロパティを削除します。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 指定された名前のカスタムプロパティの存在を確認します。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | カスタムプロパティから名前付きのブール値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | カスタムプロパティから名前付きの DateTime 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | カスタムプロパティから名前付きの double 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | カスタムプロパティから名前付きの float 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | カスタムプロパティから名前付きの int 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | カスタムプロパティから名前付きの string 値を取得します。 |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | カスタムドキュメントプロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK メタデータ)。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 名前付きのブール型カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 名前付きの DateTime カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 名前付きの double カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 名前付きの float カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 名前付きの int カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 名前付きの string カスタムプロパティを設定します。 |

### 参照

* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->