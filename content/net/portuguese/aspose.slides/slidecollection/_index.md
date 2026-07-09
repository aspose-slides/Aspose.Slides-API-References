---
title: SlideCollection
second_title: Aspose.Sildes para .NET Referência da API
description: Representa uma coleção de slides.
type: docs
weight: 9970
url: /pt/aspose.slides/slidecollection/
---
## SlideCollection classe

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Obtém o número de elementos realmente contidos na coleção. Somente leitura Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Obtém o elemento no índice especificado. Somente leitura [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Retorna uma raiz de sincronização. Somente leitura Object. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, IL… ) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Adiciona uma cópia de um slide especificado ao final da seção especificada. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Adiciona uma cópia de um slide de origem especificado ao final da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome do layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Adiciona um novo slide vazio ao final da coleção. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Copia todos os elementos da coleção para o array especificado. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Retorna um enumerador que itera pela coleção. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Retorna o índice do slide especificado na coleção. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Insere uma cópia de um slide de origem especificado na posição especificada da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome do layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Remove o elemento no índice especificado da coleção. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Move o slide da coleção para a posição especificada. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Move slides da coleção para a posição especificada. Os slides serão colocados a partir do índice na ordem em que aparecem na lista. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Cria e retorna um array contendo todos os slides. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Cria e retorna um array contendo todos os slides do intervalo especificado. Um índice do primeiro slide a ser adicionado. Um número de slides a serem adicionados. |

### Ver Também

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->