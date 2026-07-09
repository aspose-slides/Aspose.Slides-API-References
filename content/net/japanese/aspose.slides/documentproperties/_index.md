---
title: DocumentProperties
second_title: Aspose.Sildes の .NET API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
weight: 2790
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
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | プレゼンテーションの作成者を取得または設定します。読み取り/書き込み String。 |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | プレゼンテーションのカテゴリを取得または設定します。読み取り/書き込み String。 |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | プレゼンテーションのコメントを取得または設定します。読み取り/書き込み String。 |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | 会社情報を取得または設定します。読み取り/書き込み String。 |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | プレゼンテーションのコンテンツステータスを取得または設定します。読み取り/書き込み String。 |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | プレゼンテーションのコンテンツタイプを取得または設定します。読み取り/書き込み String。 |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | コレクションに実際に含まれるカスタム プロパティの数を取得します。読み取り専用 Int32。 |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | プレゼンテーションが作成された日付を取得または設定します。値は UTC です。読み取り/書き込み DateTime。 |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | 文書パーツのグループ化と各グループ内のパーツ数を示します。読み取り専用 IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | プレゼンテーション ドキュメント内の非表示スライド数を取得します。読み取り専用 Int32。 |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | HyperlinkBase ドキュメント プロパティを取得または設定します。読み取り/書き込み String。 |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | このパーツ内の 1 つ以上のハイパーリンクが、製作者によってこのパーツだけで更新されたことを示します。次にこのドキュメントを開く製作者は、このパーツで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。読み取り/書き込み Boolean。 |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | 指定された名前に関連付けられたカスタム プロパティを取得または設定します。読み取り/書き込み Object。 |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | プレゼンテーションのキーワードを取得または設定します。読み取り/書き込み String。 |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | プレゼンテーションが最後に印刷された日時を取得または設定します。読み取り/書き込み DateTime。 |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | プレゼンテーションを最後に変更した人物の名前を取得または設定します。読み取り/書き込み String。 |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | プレゼンテーションが最後に変更された日時を取得します。値は UTC です。読み取り専用（Presentation.DocumentProperties の場合は内部で保存時に更新されるため）。[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) メソッドが返す DocumentProperties インスタンスを介して変更できます。詳細は [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) メソッドの概要をご参照ください。 |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | ドキュメント内のハイパーリンクが最新であるかどうかを示します。ハイパーリンクが更新されていることを示すには **true**、古くなっていることを示すには **false** を設定してください。読み取り/書き込み Boolean。 |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | マネージャー プロパティを取得または設定します。読み取り/書き込み String。 |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | ドキュメントに含まれるサウンドまたはビデオ クリップの総数を取得します。読み取り専用 Int32。 |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | アプリケーション名を取得または設定します。読み取り/書き込み String。 |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | ノートが含まれるスライドの枚数を取得します。読み取り専用 Int32。 |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | 文書内に存在する段落の総数を取得します（該当する場合）。読み取り専用 Int32。 |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | プレゼンテーションの意図された形式を取得または設定します。読み取り/書き込み String。 |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | プレゼンテーションのリビジョン番号を取得または設定します。読み取り/書き込み Int32。 |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | ドキュメント サムネイルの表示モードを示します。サムネイルをディスプレイに合わせて拡大縮小する場合は **true**、ディスプレイに収まる部分だけを切り取って表示する場合は **false** を設定してください。読み取り/書き込み Boolean。 |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | プレゼンテーションが複数のユーザー間で共有されているかどうかを決定します。読み取り/書き込み Boolean。 |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | プレゼンテーション ドキュメント内のスライド総数を取得します。読み取り専用 Int32。 |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | プレゼンテーションの件名を取得または設定します。読み取り/書き込み String。 |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | プレゼンテーションのタイトルを取得または設定します。読み取り/書き込み String。 |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | 各文書パーツのタイトルを指定します。これらは実際の文書パーツではなく、文書セクションの概念的表現です。読み取り専用 string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | プレゼンテーションの総編集時間です。読み取り/書き込み TimeSpan。 |
| [Words](../../aspose.slides/documentproperties/words) { get; } | 文書に含まれる総単語数を取得します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | すべての組み込みプロパティをクリアし、デフォルト値に設定します。 |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | すべてのカスタム プロパティを削除します。 |
| [Clone](../../aspose.slides/documentproperties/clone)() | 現在のオブジェクトをクローンします。 |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | 現在のオブジェクトをクローンします。 |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | 指定された名前のカスタム プロパティの存在を確認します。 |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | 指定されたインデックスのカスタム プロパティ名を返します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | カスタム プロパティから名前付きブール値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | カスタム プロパティから名前付き DateTime 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | カスタム プロパティから名前付き double 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | カスタム プロパティから名前付き float 値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | カスタム プロパティから名前付き整数値を取得します。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | カスタム プロパティから名前付き文字列値を取得します。 |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | カスタム ドキュメント プロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK メタデータ)。 |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | 指定された名前に関連付けられたカスタム プロパティを削除します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 名前付きブール カスタム プロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 名前付き DateTime カスタム プロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 名前付き double カスタム プロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 名前付き float カスタム プロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 名前付き整数カスタム プロパティを設定します。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 名前付き文字列カスタム プロパティを設定します。 |

### 例

以下の例は、PowerPoint プレゼンテーションの組み込みプロパティにアクセスする方法を示します。

```csharp
[C#]
// プレゼンテーションを表す Presentation クラスをインスタンス化する
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Presentation に関連付けられた IDocumentProperties オブジェクトへの参照を作成する
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// 組み込みプロパティを表示する
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

以下の例は、PowerPoint プレゼンテーションの組み込みプロパティを変更する方法を示します。

```csharp
[C#]
// プレゼンテーションを表す Presentation クラスのインスタンスを作成する
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Presentation に関連付けられた IDocumentProperties オブジェクトへの参照を作成する
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// 組み込みプロパティを設定する
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// プレゼンテーションをファイルに保存する
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### 参照

* インターフェイス [IDocumentProperties](../idocumentproperties)
* インターフェイス [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->