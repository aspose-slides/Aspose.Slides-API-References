---
title: IDocumentProperties
second_title: Referência da API Aspose.Slides para C++
description: Representa propriedades de uma apresentação.
type: docs
weight: 1977
url: /pt/aspose.slides/idocumentproperties/
---
## IDocumentProperties classe

Representa propriedades de uma apresentação.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Limpa e define valores padrão para todas as propriedades builtIn. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Remove todas as propriedades personalizadas. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Verifica a presença de uma propriedade personalizada com um nome especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Retorna o modelo de uma aplicação. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Retorna a versão do aplicativo. Somente leitura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Retorna o autor de uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Retorna a categoria de uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Retorna os comentários de uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Retorna a propriedade company. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Retorna o status de conteúdo de uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Retorna o tipo de conteúdo de uma apresentação. Leia [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Retorna o número de propriedades personalizadas realmente contidas em uma coleção. Somente leitura **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Retorna a data em que a apresentação foi criada. Os valores estão em UTC. Leia [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Indica o agrupamento das partes do documento e o número de partes em cada grupo. Somente leitura [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Especifica o número de slides ocultos em um documento de apresentação. Somente leitura **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Retorna a propriedade de documento HyperlinkBase. Leia [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento deverá atualizar os relacionamentos de hyperlink com os novos hyperlinks especificados nesta parte. Leia **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Retorna as palavras-chave de uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Retorna a data em que a apresentação foi impressa pela última vez. Leia [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Retorna o nome da última pessoa que modificou uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Retorna a data em que a apresentação foi modificada pela última vez. Os valores estão em UTC. Somente leitura no caso de Presentation.DocumentProperties (pois será atualizado internamente durante o processo de salvamento do objeto [IPresentation](../ipresentation/)). Pode ser alterado via instância [DocumentProperties](../documentproperties/) retornada pelo método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Veja o exemplo no resumo do método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Indica se os hyperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hyperlinks estão atualizados. Defina como **false** para indicar que os hyperlinks estão desatualizados. Leia **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Retorna a propriedade manager. Leia [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Especifica o número total de clipes de áudio ou vídeo presentes no documento. Somente leitura **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Retorna o nome da aplicação. Leia [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Especifica o número de slides em uma apresentação que contêm notas. Somente leitura **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Especifica o número total de parágrafos encontrados em um documento, se aplicável. Somente leitura **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Retorna o formato pretendido de uma apresentação. Leia [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Retorna o número de revisão da apresentação. Leia **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura do documento ao display. Defina como **false** para habilitar o recorte da miniatura para mostrar apenas as seções que cabem no display. Leia **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Determina se a apresentação é compartilhada entre várias pessoas. Leia **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Especifica o número total de slides em um documento de apresentação. Somente leitura **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Retorna o assunto de uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Retorna o título de uma apresentação. Leia [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Especifica o título de cada parte do documento. Essas partes não são partes de documento, mas representações conceituais de seções do documento. Somente leitura [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Tempo total de edição de uma apresentação. Leia [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Especifica o número total de palavras contidas em um documento. Somente leitura **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Retorna o nome de uma propriedade personalizada no índice especificado. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Obtém um valor booleano nomeado das propriedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Obtém um valor inteiro nomeado das propriedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Obtém um valor DateTime nomeado das propriedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Obtém um valor string nomeado das propriedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Obtém um valor float nomeado das propriedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Obtém um valor double nomeado das propriedades personalizadas. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Habilita o hash de objetos personalizados. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Obtém uma matriz de rótulos de sensibilidade das propriedades de documento personalizadas (Metadados do Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Retorna a propriedade personalizada associada a um nome especificado. Leia [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Define a propriedade personalizada associada a um nome especificado. Escrita [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias nas subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias nas subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Remove uma propriedade personalizada associada a um nome especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Define o modelo de uma aplicação. Escrita [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Define o autor de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Define a categoria de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Define os comentários de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Define a propriedade company. Escrita [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Define o status de conteúdo de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Define o tipo de conteúdo de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Define a data em que a apresentação foi criada. Os valores estão em UTC. Escrita [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Define a propriedade de documento HyperlinkBase. Escrita [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento deverá atualizar os relacionamentos de hyperlink com os novos hyperlinks especificados nesta parte. Escrita **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Define as palavras-chave de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Define a data em que a apresentação foi impressa pela última vez. Escrita [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Define o nome da última pessoa que modificou uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Retorna a data em que a apresentação foi modificada pela última vez. Os valores estão em UTC. Somente leitura no caso de Presentation.DocumentProperties (pois será atualizado internamente durante o processo de salvamento do objeto [IPresentation](../ipresentation/)). Pode ser alterado via instância [DocumentProperties](../documentproperties/) retornada pelo método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Veja o exemplo no resumo do método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Indica se os hyperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hyperlinks estão atualizados. Defina como **false** para indicar que os hyperlinks estão desatualizados. Escrita **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Define a propriedade manager. Escrita [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Define o nome da aplicação. Escrita [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Define o formato pretendido de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Define o número de revisão da apresentação. Escrita **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura do documento ao display. Defina como **false** para habilitar o recorte da miniatura para mostrar apenas as seções que cabem no display. Escrita **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Determina se a apresentação é compartilhada entre várias pessoas. Escrita **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Define o assunto de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Define o título de uma apresentação. Escrita [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Tempo total de edição de uma apresentação. Escrita [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Define uma propriedade personalizada booleana nomeada. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Define uma propriedade personalizada inteira nomeada. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Define uma propriedade personalizada DateTime nomeada. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Define uma propriedade personalizada string nomeada. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Define uma propriedade personalizada float nomeada. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Define uma propriedade personalizada double nomeada. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método [Object.ToString()](../../system/object/tostring/) do C#. Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)