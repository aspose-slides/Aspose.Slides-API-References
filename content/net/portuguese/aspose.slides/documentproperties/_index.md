---
title: DocumentProperties
second_title: Referência da API Aspose.Sildes para .NET
description: Representa as propriedades de uma apresentação.
type: docs
weight: 2770
url: /pt/aspose.slides/documentproperties/
---
## DocumentProperties classe

Representa as propriedades de uma apresentação.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [DocumentProperties](documentproperties)() | Inicializa uma nova instância da classe [`DocumentProperties`](../documentproperties). |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Retorna ou define o modelo de um aplicativo. Leitura/gravação String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Retorna a versão do aplicativo. Somente leitura String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Retorna ou define o autor de uma apresentação. Leitura/gravação String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Retorna ou define a categoria de uma apresentação. Leitura/gravação String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Retorna ou define os comentários de uma apresentação. Leitura/gravação String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Retorna ou define a propriedade empresa. Leitura/gravação String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Retorna ou define o status de conteúdo de uma apresentação. Leitura/gravação String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Retorna ou define o tipo de conteúdo de uma apresentação. Leitura/gravação String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Retorna o número de propriedades personalizadas realmente contidas em uma coleção. Somente leitura Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Retorna a data em que a apresentação foi criada. Os valores estão em UTC. Leitura/gravação DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Indica o agrupamento de partes do documento e o número de partes em cada grupo. Somente leitura IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Retorna o número de slides ocultos em um documento de apresentação. Somente leitura Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Retorna ou define a propriedade de documento HyperlinkBase. Leitura/gravação String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento deverá atualizar os relacionamentos de hyperlinks com os novos hyperlinks especificados nesta parte. Leitura/gravação Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Retorna ou define a propriedade personalizada associada a um nome especificado. Leitura/gravação Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Retorna ou define as palavras-chave de uma apresentação. Leitura/gravação String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Retorna a data em que a apresentação foi impressa pela última vez. Leitura/gravação DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Retorna ou define o nome da última pessoa que modificou a apresentação. Leitura/gravação String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Retorna a data em que a apresentação foi modificada pela última vez. Os valores estão em UTC. Somente leitura no caso de Presentation.DocumentProperties (pois será atualizado internamente durante o processo de gravação do objeto IPresentation). Pode ser alterado via instância DocumentProperties retornada pelo método [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Consulte o exemplo no resumo do método [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Indica se os hyperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hyperlinks estão atualizados. Defina como **false** para indicar que os hyperlinks estão desatualizados. Leitura/gravação Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Retorna ou define a propriedade manager. Leitura/gravação String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Retorna o número total de clipes de som ou vídeo presentes no documento. Somente leitura Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Retorna ou define o nome do aplicativo. Leitura/gravação String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Retorna o número de slides em uma apresentação que contêm anotações. Somente leitura Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Retorna o número total de parágrafos encontrados em um documento, se aplicável. Somente leitura Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Retorna ou define o formato pretendido de uma apresentação. Leitura/gravação String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Retorna ou define o número de revisão da apresentação. Leitura/gravação Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura do documento ao visor. Defina como **false** para habilitar o recorte da miniatura do documento para mostrar apenas as seções que cabem no visor. Leitura/gravação Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Determina se a apresentação é compartilhada entre várias pessoas. Leitura/gravação Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Retorna o número total de slides em um documento de apresentação. Somente leitura Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Retorna ou define o assunto da apresentação. Leitura/gravação String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Retorna ou define o título da apresentação. Leitura/gravação String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Especifica o título de cada parte do documento. Essas partes não são partes do documento, mas representações conceituais de seções do documento. Somente leitura string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Tempo total de edição de uma apresentação. Leitura/gravação TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Retorna o número total de palavras contidas em um documento. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Limpa e define valores padrão para todas as propriedades builtIn. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Remove todas as propriedades personalizadas. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Clona o objeto atual |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Clona o objeto atual |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Verifica a presença de uma propriedade personalizada com um nome especificado. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Retorna o nome de uma propriedade personalizada no índice especificado. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtém um valor booleano nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtém um valor DateTime nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtém um valor double nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtém um valor float nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtém um valor inteiro nomeado das propriedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtém um valor string nomeado das propriedades personalizadas. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Obtém um array de rótulos de sensibilidade das propriedades personalizadas do documento (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Remove uma propriedade personalizada associada a um nome especificado. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Define uma propriedade personalizada booleana nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Define uma propriedade personalizada DateTime nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Define uma propriedade personalizada double nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Define uma propriedade personalizada float nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Define uma propriedade personalizada inteira nomeada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Define uma propriedade personalizada string nomeada. |

### Exemplos

O exemplo abaixo mostra como acessar as Propriedades built-in de uma apresentação do PowerPoint.

```csharp
[C#]
// Instanciar a classe Presentation que representa a apresentação
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Criar uma referência ao objeto IDocumentProperties associado à Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Exibir as propriedades incorporadas
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

O exemplo abaixo mostra como modificar as Propriedades built-in de uma apresentação do PowerPoint.

```csharp
[C#]
// Instanciar a classe Presentation que representa a Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Criar uma referência ao objeto IDocumentProperties associado à Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Definir as propriedades incorporadas
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Salvar sua apresentação em um arquivo
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Ver Também

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->