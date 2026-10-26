---
title: IDocumentProperties
second_title: Referência da API Aspose.Sildes para .NET
description: Representa propriedades de uma apresentação.
type: docs
weight: 5710
url: /pt/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Representa propriedades de uma apresentação.

```csharp
public interface IDocumentProperties
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Retorna ou define o modelo de um aplicativo. Leitura/Gravação String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Retorna a versão do aplicativo. Somente leitura String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Retorna ou define o autor de uma apresentação. Leitura/Gravação String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Retorna ou define a categoria de uma apresentação. Leitura/Gravação String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Retorna ou define os comentários de uma apresentação. Leitura/Gravação String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Retorna ou define a propriedade company. Leitura/Gravação String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Retorna ou define o status de conteúdo de uma apresentação. Leitura/Gravação String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Retorna ou define o tipo de conteúdo de uma apresentação. Leitura/Gravação String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Retorna o número de propriedades personalizadas contidas na coleção. Somente leitura Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Retorna a data em que a apresentação foi criada. Valores em UTC. Leitura/Gravação DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indica o agrupamento de partes do documento e o número de partes em cada grupo. Somente leitura IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Especifica o número de slides ocultos em um documento de apresentação. Somente leitura Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Retorna ou define a propriedade HyperlinkBase do documento. Leitura/Gravação String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento deve atualizar os relacionamentos de hyperlink com os novos hyperlinks especificados nesta parte. Leitura/Gravação Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Retorna ou define a propriedade personalizada associada a um nome especificado. Leitura/Gravação Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Retorna ou define as palavras-chave de uma apresentação. Leitura/Gravação String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Retorna a data em que a apresentação foi impressa pela última vez. Leitura/Gravação DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Retorna ou define o nome da última pessoa que modificou a apresentação. Leitura/Gravação String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Retorna a data em que a apresentação foi modificada pela última vez. Valores em UTC. Somente leitura no caso de Presentation.DocumentProperties (pois será atualizado internamente durante o processo de salvamento do objeto IPresentation). Pode ser alterado via instância DocumentProperties retornada pelo método [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Consulte o exemplo no resumo do método [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indica se os hyperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hyperlinks estão atualizados. Defina como **false** para indicar que estão desatualizados. Leitura/Gravação Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Retorna ou define a propriedade manager. Leitura/Gravação String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Especifica o número total de clipes de som ou vídeo presentes no documento. Somente leitura Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Retorna ou define o nome do aplicativo. Leitura/Gravação String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Especifica o número de slides em uma apresentação que contêm notas. Somente leitura Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Especifica o número total de parágrafos encontrados em um documento, se aplicável. Somente leitura Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Retorna ou define o formato pretendido de uma apresentação. Leitura/Gravação String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Retorna ou define o número da revisão da apresentação. Leitura/Gravação Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura ao display. Defina como **false** para habilitar o recorte da miniatura, mostrando apenas as seções que cabem no display. Leitura/Gravação Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Determina se a apresentação é compartilhada entre várias pessoas. Leitura/Gravação Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Especifica o número total de slides em um documento de apresentação. Somente leitura Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Retorna ou define o assunto da apresentação. Leitura/Gravação String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Retorna ou define o título da apresentação. Leitura/Gravação String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Especifica o título de cada parte do documento. Estas partes não são partes do documento, mas representações conceituais de seções do documento. Somente leitura string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Tempo total de edição da apresentação. Leitura/Gravação TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Especifica o número total de palavras contidas no documento. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Limpa e define valores padrão para todas as propriedades builtIn. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Remove todas as propriedades personalizadas. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Verifica a presença de uma propriedade personalizada com um nome especificado. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Retorna o nome de uma propriedade personalizada no índice especificado. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtém um valor booleano nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtém um valor DateTime nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtém um valor double nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtém um valor float nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtém um valor inteiro nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtém um valor string nomeado das propriedades personalizadas. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Obtém um array de rótulos de sensibilidade das propriedades personalizadas do documento (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Remove uma propriedade personalizada associada a um nome especificado. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Define uma propriedade personalizada booleana nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Define uma propriedade personalizada DateTime nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Define uma propriedade personalizada double nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Define uma propriedade personalizada float nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Define uma propriedade personalizada inteira nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Define uma propriedade personalizada string nomeada. |

### Veja Também

* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->