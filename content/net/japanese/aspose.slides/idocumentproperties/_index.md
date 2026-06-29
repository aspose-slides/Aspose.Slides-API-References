---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
weight: 5690
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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | アプリケーションのテンプレートを取得または設定します。読み書き可能 String。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | アプリのバージョンを取得します。読み取り専用 String。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | プレゼンテーションの作成者を取得または設定します。読み書き可能 String。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | プレゼンテーションのカテゴリを取得または設定します。読み書き可能 String。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | プレゼンテーションのコメントを取得または設定します。読み書き可能 String。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 会社プロパティを取得または設定します。読み書き可能 String。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | プレゼンテーションのコンテンツステータスを取得または設定します。読み書き可能 String。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | プレゼンテーションのコンテンツタイプを取得または設定します。読み書き可能 String。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | コレクションに実際に含まれるカスタムプロパティの数を取得します。読み取り専用 Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | プレゼンテーションが作成された日付を取得します。値は UTC です。読み書き可能 DateTime。 |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | ドキュメントパーツのグループ化と各グループ内のパーツ数を示します。読み取り専用 IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | プレゼンテーションドキュメント内の非表示スライド数を指定します。読み取り専用 Int32。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase ドキュメントプロパティを取得または設定します。読み書き可能 String。 |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | このパート内の 1 つ以上のハイパーリンクがプロデューサーによってこのパートだけで更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新します。読み書き可能 Boolean。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。読み書き可能 Object。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | プレゼンテーションのキーワードを取得または設定します。読み書き可能 String。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | プレゼンテーションが最後に印刷された日時を取得します。読み書き可能 DateTime。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | プレゼンテーションを最後に編集した人物の名前を取得または設定します。読み書き可能 String。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | プレゼンテーションが最後に変更された日時を取得します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です（IPresentation オブジェクトの保存プロセス中に内部で更新されるため）。[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) メソッドが返す DocumentProperties インスタンスを介して変更できます。[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) メソッドの概要にある例をご参照ください。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されていることを示します。**false** に設定するとハイパーリンクが古くなっていることを示します。読み書き可能 Boolean。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | マネージャー プロパティを取得または設定します。読み書き可能 String。 |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | ドキュメントに存在するサウンドまたはビデオクリップの合計数を指定します。読み取り専用 Int32。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | アプリケーションの名前を取得または設定します。読み書き可能 String。 |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | ノートを含むプレゼンテーションのスライド数を指定します。読み取り専用 Int32。 |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 該当する場合、ドキュメント内に見つかった段落の総数を指定します。読み取り専用 Int32。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | プレゼンテーションの意図された形式を取得または設定します。読み書き可能 String。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | プレゼンテーションのリビジョン番号を取得または設定します。読み書き可能 Int32。 |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定すると、サムネイルをディスプレイに合わせて拡大縮小できます。**false** に設定すると、ディスプレイに合うセクションだけを表示するようにサムネイルを切り取ります。読み書き可能 Boolean。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | プレゼンテーションが複数のユーザー間で共有されているかどうかを決定します。読み書き可能 Boolean。 |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | プレゼンテーションドキュメント内のスライド総数を指定します。読み取り専用 Int32。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | プレゼンテーションの件名を取得または設定します。読み書き可能 String。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | プレゼンテーションのタイトルを取得または設定します。読み書き可能 String。 |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 各ドキュメントパートのタイトルを指定します。これらのパートは実際のドキュメントパートではなく、ドキュメントセクションの概念的表現です。読み取り専用 string[]。 |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | プレゼンテーションの総編集時間です。読み書き可能 TimeSpan。 |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | ドキュメントに含まれる単語の総数を指定します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | すべての組み込みプロパティをクリアし、デフォルト値を設定します。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | すべてのカスタムプロパティを削除します。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 指定された名前のカスタムプロパティの存在を確認します。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | カスタムプロパティから指定された名前の Boolean 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | カスタムプロパティから指定された名前の DateTime 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | カスタムプロパティから指定された名前の double 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | カスタムプロパティから指定された名前の float 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | カスタムプロパティから指定された名前の整数値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | カスタムプロパティから指定された名前の文字列値を取得します。 |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | カスタムドキュメントプロパティから感度ラベルの配列を取得します（Microsoft Information Protection SDK メタデータ）。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 名前付き Boolean カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 名前付き DateTime カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 名前付き double カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 名前付き float カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 名前付き整数カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 名前付き文字列カスタムプロパティを設定します。 |

### 参照

* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->