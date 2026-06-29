---
title: SlideCollection
second_title: Aspose.Slides for .NET API リファレンス
description: スライドのコレクションを表します。
type: docs
weight: 9950
url: /ja/aspose.slides/slidecollection/
---
## SlideCollection クラス

スライドのコレクションを表します。

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | コレクションに実際に含まれる要素の数を取得します。読み取り専用 Int32。 |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | コレクションへのアクセスが同期化されているか (スレッド セーフ) を示す値を返します。読み取り専用 Boolean。 |
| [Item](../../aspose.slides/slidecollection/item) { get; } | 指定したインデックスの要素を取得します。読み取り専用 [`Slide`](../slide)。 |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | 同期化ルートを返します。読み取り専用 Object。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | 指定されたスライドのコピーを指定したセクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 指定されたソース スライドのコピーをコレクションの末尾に追加します。適切なレイアウトは指定されたマスターから自動的に選択されます (適切なレイアウトは、ソース スライドのレイアウトと同じ Type または Name を持つレイアウト)。適切なレイアウトが存在しない場合、ソース スライドのレイアウトはクローンされます (allowCloneMissingLayout が true の場合) または PptxEditException がスローされます (allowCloneMissingLayout が false の場合)。 |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | 新しい空のスライドをコレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF インポート オプションを考慮して、PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | コレクションのすべての要素を指定された配列にコピーします。 |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | コレクション内の指定されたスライドのインデックスを返します。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | 指定した位置に指定されたスライドのコピーを挿入します。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 指定した位置に指定されたスライドのコピーを挿入します。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 指定した位置に指定されたソース スライドのコピーを挿入します。適切なレイアウトは指定されたマスターから自動的に選択されます (適切なレイアウトは、ソース スライドのレイアウトと同じ Type または Name を持つレイアウト)。適切なレイアウトが存在しない場合、ソース スライドのレイアウトはクローンされます (allowCloneMissingLayout が true の場合) または PptxEditException がスローされます (allowCloneMissingLayout が false の場合)。 |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | 指定した位置に指定されたスライドのコピーを挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML テキストからスライドを作成し、指定した位置に挿入します。 |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | 指定したインデックスの要素をコレクションから削除します。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | スライドをコレクションから指定した位置に移動します。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | スライドをコレクションから指定した位置に移動します。スライドはインデックスから順にリストに現れる順序で配置されます。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | すべてのスライドを含む配列を作成して返します。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | 指定した範囲のスライドを含む配列を作成して返します。開始スライドのインデックスと取得するスライド数を指定します。 |

### 参照

* クラス [DomObject&lt;TParent&gt;](../domobject-1)
* クラス [Presentation](../presentation)
* インターフェイス [ISlideCollection](../islidecollection)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->