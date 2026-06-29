---
title: DocumentProperties
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
weight: 2770
url: /ja/aspose.slides/documentproperties/
---
## DocumentProperties クラス

プレゼンテーションのプロパティを表します。

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DocumentProperties](documentproperties)() | クラス [`DocumentProperties`](../documentproperties) の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | アプリケーションのテンプレートを取得または設定します。読み取り/書き込み String。 |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | アプリのバージョンを取得します。読み取り専用 String。 |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | プレゼンテーションの作者を取得または設定します。読み取り/書き込み String。 |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | プレゼンテーションのカテゴリを取得または設定します。読み取り/書き込み String。 |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | プレゼンテーションのコメントを取得または設定します。読み取り/書き込み String。 |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | 会社プロパティを取得または設定します。読み取り/書き込み String。 |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | プレゼンテーションのコンテンツステータスを取得または設定します。読み取り/書き込み String。 |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | プレゼンテーションのコンテンツタイプを取得または設定します。読み取り/書き込み String。 |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | コレクションに実際に含まれるカスタムプロパティの数を取得します。読み取り専用 Int32。 |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | プレゼンテーションが作成された日付を取得します。値は UTC です。読み取り/書き込み DateTime。 |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | ドキュメントパーツのグルーピングと各グループ内のパーツ数を示します。読み取り専用 IHeadingPair[]。 |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | プレゼンテーションドキュメント内の非表示スライドの数を取得します。読み取り専用 Int32。 |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | HyperlinkBase ドキュメントプロパティを取得または設定します。読み取り/書き込み String。 |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | このパート内の 1 つ以上のハイパーリンクが、プロデューサーによってこのパート内でのみ更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。読み取り/書き込み Boolean。 |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | 指定された名前に関連付けられたカスタムプロパティを取得または設定します。読み取り/書き込み Object。 |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | プレゼンテーションのキーワードを取得または設定します。読み取り/書き込み String。 |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | プレゼンテーションが最後に印刷された日時を取得します。読み取り/書き込み DateTime。 |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | プレゼンテーションを最後に変更した人物の名前を取得または設定します。読み取り/書き込み String。 |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | プレゼンテーションが最後に変更された日時を取得します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です（IPresentation オブジェクトの保存プロセス中に内部で更新されるため）。[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) メソッドが返す DocumentProperties インスタンスを介して変更できます。例は [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) メソッドの概要をご覧ください。 |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新済みであることを示します。**false** に設定するとハイパーリンクが古くなっていることを示します。読み取り/書き込み Boolean。 |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | manager プロパティを取得または設定します。読み取り/書き込み String。 |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | ドキュメントに含まれるサウンドまたはビデオクリップの総数を取得します。読み取り専用 Int32。 |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | アプリケーションの名前を取得または設定します。読み取り/書き込み String。 |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | ノートを含むプレゼンテーションのスライド数を取得します。読み取り専用 Int32。 |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | 該当する場合、ドキュメント内に見つかった段落の総数を取得します。読み取り専用 Int32。 |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | プレゼンテーションの目的のフォーマットを取得または設定します。読み取り/書き込み String。 |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | プレゼンテーションのリビジョン番号を取得または設定します。読み取り/書き込み Int32。 |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルがディスプレイに合わせてスケーリングされます。**false** に設定するとサムネイルがディスプレイに合う部分だけが表示されるようにトリミングされます。読み取り/書き込み Boolean。 |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | プレゼンテーションが複数のユーザー間で共有されているかどうかを決定します。読み取り/書き込み Boolean。 |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | プレゼンテーションドキュメント内のスライド総数を取得します。読み取り専用 Int32。 |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | プレゼンテーションの主題を取得または設定します。読み取り/書き込み String。 |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | プレゼンテーションのタイトルを取得または設定します。読み取り/書き込み String。 |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | 各ドキュメントパートのタイトルを指定します。これらのパートは実際のドキュメントパートではなく、ドキュメントセクションの概念的な表現です。読み取り専用 string[]。 |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | プレゼンテーションの総編集時間です。読み取り/書き込み TimeSpan。 |
| [Words](../../aspose.slides/documentproperties/words) { get; } | ドキュメントに含まれる総単語数を取得します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | すべての組み込みプロパティをクリアし、デフォルト値を設定します。 |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | すべてのカスタムプロパティを削除します。 |
| [Clone](../../aspose.slides/documentproperties/clone)() | 現在のオブジェクトをクローンします |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | 現在のオブジェクトをクローンします |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | 指定された名前のカスタムプロパティの存在を確認します。 |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | カスタムプロパティから名前付きのブール値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | カスタムプロパティから名前付きの DateTime 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | カスタムプロパティから名前付きの double 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | カスタムプロパティから名前付きの float 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | カスタムプロパティから名前付きの整数値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | カスタムプロパティから名前付きの文字列値を取得します。 |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | カスタムドキュメントプロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK メタデータ)。 |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 名前付きブールカスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 名前付き DateTime カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 名前付き double カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 名前付き float カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 名前付き整数カスタムプロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 名前付き文字列カスタムプロパティを設定します。 |

### 例

以下の例は PowerPoint プレゼンテーションの組み込みプロパティへのアクセス方法を示しています。

```csharp
[C#]
// プレゼンテーションを表す Presentation クラスのインスタンスを作成します
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Presentation に関連付けられた IDocumentProperties オブジェクトへの参照を作成します
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// 組み込みプロパティを表示します
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

以下の例は PowerPoint プレゼンテーションの組み込みプロパティを変更する方法を示しています。

```csharp
[C#]
// プレゼンテーションを表す Presentation クラスのインスタンスを作成します
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Presentation に関連付けられた IDocumentProperties オブジェクトへの参照を作成します
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// 組み込みプロパティを設定します
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// プレゼンテーションをファイルに保存します
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### 参照

* インターフェイス [IDocumentProperties](../idocumentproperties)
* インターフェイス [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->