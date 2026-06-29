---
title: LoadOptions
second_title: Referência da API Aspose.Sildes para .NET
description: Permite especificar opções adicionais, como formato ou fonte padrão, ao carregar uma apresentação.
type: docs
weight: 7820
url: /pt/aspose.slides/loadoptions/
---
## classe LoadOptions

Permite especificar opções adicionais (como formato ou fonte padrão) ao carregar uma apresentação.

```csharp
public class LoadOptions : ILoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Cria novas opções de carregamento padrão. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Cria novas opções de carregamento. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como o uso de arquivos temporários ou o número máximo de bytes de BLOBs na memória. Essas opções destinam-se a definir a melhor relação desempenho/consumo de memória para um ambiente ou requisitos específicos. Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade – ou seja, BLOB pode ser um áudio, vídeo ou a própria apresentação. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Retorna ou define a fonte asiática usada caso a fonte original não seja encontrada. Leitura/gravação String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Retorna ou define a fonte regular usada caso a fonte original não seja encontrada. Leitura/gravação String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Retorna ou define a fonte Symbol usada caso a fonte original não seja encontrada. Leitura/gravação String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Retorna ou define o idioma padrão para o texto da apresentação. Leitura/gravação String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina se Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Especifica as fontes externas a serem usadas pela apresentação. Essas fontes ficam disponíveis para a apresentação durante todo o seu ciclo de vida e não são compartilhadas com outras apresentações |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | O token para monitorar solicitações de interrupção. Este token gerencia toda a instância [`IPresentation`](../ipresentation) durante sua vida útil. Qualquer operação de longa duração, como carregar ou salvar uma apresentação, será interrompida chamando o método [`Interrupt`](../interruptiontokensource/interrupt) do [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Retorna ou define o formato de uma apresentação a ser carregada. Leitura/gravação [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada. Valor false significa que a apresentação inteira criptografada deve ser carregada usando a senha correta. Se a apresentação não estiver criptografada, o valor da propriedade é sempre ignorado. Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, então as propriedades do documento não poderão ser carregadas e uma exceção será lançada. Leitura/gravação Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtém ou define a senha. Leitura/gravação String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. Leitura/gravação [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtém opções para planilhas. Por exemplo, essas opções afetam o cálculo de fórmulas para gráficos. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/gravação [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Veja Também

* interface [ILoadOptions](../iloadoptions)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->