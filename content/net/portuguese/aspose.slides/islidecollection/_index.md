---
title: ISlideCollection
second_title: Aspose.Sildes para .NET Referência da API
description: Representa uma coleção de slides.
type: docs
weight: 7050
url: /pt/aspose.slides/islidecollection/
---
## ISlideCollection interface

Representa uma coleção de slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Obtém o elemento no índice especificado. Somente leitura [`ISlide`](../islide). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Adiciona uma cópia de um slide especificado ao final da seção especificada. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Adiciona uma cópia de um slide de origem especificado ao final da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (layout apropriado é o layout com o mesmo Tipo ou Nome do layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Adiciona um novo slide vazio ao final da coleção. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação de PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Retorna o índice do slide especificado na coleção. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Insere uma cópia de um slide de origem especificado na posição especificada da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (layout apropriado é o layout com o mesmo Tipo ou Nome do layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Remove o elemento no índice especificado da coleção. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Move o slide da coleção para a posição especificada. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Move slides da coleção para a posição especificada. Os slides serão colocados a partir do índice, na ordem em que aparecem na lista. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Cria e retorna um array contendo todos os slides. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Cria e retorna um array contendo todos os slides do intervalo especificado. |

### Veja Também

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->