---
title: ISlideCollection
second_title: Aspose.Sildes の .NET API リファレンス
description: スライドのコレクションを表します。
type: docs
weight: 7050
url: /ja/aspose.slides/islidecollection/
---
## ISlideCollection インターフェイス

Represents a collection of a slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | 指定されたインデックスの要素を取得します。読み取り専用 [`ISlide`](../islide)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | 指定されたスライドのコピーを指定されたセクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 指定されたソーススライドのコピーをコレクションの末尾に追加します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウト）。適切なレイアウトがない場合、ソーススライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | 新しい空のスライドをコレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF ドキュメントからスライドを作成し、PDF インポートオプションを考慮してコレクションの末尾に追加します。 |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | コレクション内の指定されたスライドのインデックスを返します。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | 指定された位置に指定されたスライドのコピーを挿入します。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 指定された位置に指定されたスライドのコピーを挿入します。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 指定された位置に指定されたソーススライドのコピーを挿入します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウト）。適切なレイアウトがない場合、ソーススライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | 指定された位置に指定されたスライドのコピーを挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | コレクションの指定されたインデックスの要素を削除します。 |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | スライドをコレクションから指定された位置へ移動します。 |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | スライドをコレクションから指定された位置へ移動します。スライドはインデックスから開始し、リストに現れる順序で配置されます。 |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | すべてのスライドを含む配列を作成して返します。 |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | 指定された範囲のすべてのスライドを含む配列を作成して返します。 |

### 参照

* インターフェイス [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* インターフェイス [ISlide](../islide)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->