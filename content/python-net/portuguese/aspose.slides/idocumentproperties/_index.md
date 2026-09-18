---
title: IDocumentProperties class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/idocumentproperties/
---
## IDocumentProperties classe

Representa as propriedades de uma apresentação.

O tipo IDocumentProperties expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/pt/aspose.slides/idocumentproperties/app_version/) | Retorna a versão do aplicativo.<br/>            Somente leitura **str**. |
| [`name_of_application`](/slides/python-net/pt/aspose.slides/idocumentproperties/name_of_application/) | Retorna ou define o nome do aplicativo.<br/>            Leitura/gravação **str**. |
| [`company`](/slides/python-net/pt/aspose.slides/idocumentproperties/company/) | Retorna ou define a propriedade da empresa.<br/>            Leitura/gravação **str**. |
| [`manager`](/slides/python-net/pt/aspose.slides/idocumentproperties/manager/) | Retorna ou define a propriedade do gerente.<br/>            Leitura/gravação **str**. |
| [`presentation_format`](/slides/python-net/pt/aspose.slides/idocumentproperties/presentation_format/) | Retorna ou define o formato pretendido de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`shared_doc`](/slides/python-net/pt/aspose.slides/idocumentproperties/shared_doc/) | Determina se a apresentação está compartilhada entre várias pessoas.<br/>            Leitura/gravação **bool**. |
| [`application_template`](/slides/python-net/pt/aspose.slides/idocumentproperties/application_template/) | Retorna ou define o modelo de um aplicativo.<br/>            Leitura/gravação **str**. |
| [`total_editing_time`](/slides/python-net/pt/aspose.slides/idocumentproperties/total_editing_time/) | Tempo total de edição de uma apresentação.<br/>            Leitura/gravação **System.TimeSpan**. |
| [`title`](/slides/python-net/pt/aspose.slides/idocumentproperties/title/) | Retorna ou define o título de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`subject`](/slides/python-net/pt/aspose.slides/idocumentproperties/subject/) | Retorna ou define o assunto de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`author`](/slides/python-net/pt/aspose.slides/idocumentproperties/author/) | Retorna ou define o autor de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`keywords`](/slides/python-net/pt/aspose.slides/idocumentproperties/keywords/) | Retorna ou define as palavras-chave de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`comments`](/slides/python-net/pt/aspose.slides/idocumentproperties/comments/) | Retorna ou define os comentários de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`category`](/slides/python-net/pt/aspose.slides/idocumentproperties/category/) | Retorna ou define a categoria de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`created_time`](/slides/python-net/pt/aspose.slides/idocumentproperties/created_time/) | Retorna a data em que uma apresentação foi criada.<br/>            Os valores estão em UTC.<br/>            Leitura/gravação **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/pt/aspose.slides/idocumentproperties/last_saved_time/) | Retorna a data em que uma apresentação foi modificada pela última vez.<br/>            Os valores estão em UTC.<br/>            Somente leitura no caso de Presentation.DocumentProperties (porque será atualizado internamente durante o processo de salvamento do objeto IPresentation). <br/>            Pode ser alterado via instância DocumentProperties retornada pelo método [`IPresentationInfo.read_document_properties`](/slides/python-net/pt/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Consulte o exemplo em **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** resumo do método. |
| [`last_printed`](/slides/python-net/pt/aspose.slides/idocumentproperties/last_printed/) | Retorna a data em que uma apresentação foi impressa pela última vez.<br/>            Leitura/gravação **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/pt/aspose.slides/idocumentproperties/last_saved_by/) | Retorna ou define o nome da última pessoa que modificou uma apresentação.<br/>            Leitura/gravação **str**. |
| [`revision_number`](/slides/python-net/pt/aspose.slides/idocumentproperties/revision_number/) | Retorna ou define o número da revisão da apresentação.<br/>            Leitura/gravação **int**. |
| [`content_status`](/slides/python-net/pt/aspose.slides/idocumentproperties/content_status/) | Retorna ou define o status do conteúdo de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`content_type`](/slides/python-net/pt/aspose.slides/idocumentproperties/content_type/) | Retorna ou define o tipo de conteúdo de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`hyperlink_base`](/slides/python-net/pt/aspose.slides/idocumentproperties/hyperlink_base/) | Retorna ou define a propriedade de documento HyperlinkBase.<br/>            Leitura/gravação **str**. |
| [`scale_crop`](/slides/python-net/pt/aspose.slides/idocumentproperties/scale_crop/) | Indica o modo de exibição da miniatura do documento.<br/>            Defina este elemento como **true** para habilitar a escala da miniatura do documento ao display.<br/>            Defina este elemento como **false** para habilitar o recorte da miniatura do documento para mostrar apenas as seções que cabem no display.<br/>            Leitura/gravação **bool**. |
| [`links_up_to_date`](/slides/python-net/pt/aspose.slides/idocumentproperties/links_up_to_date/) | Indica se os hyperlinks em um documento estão atualizados.<br/>            Defina este elemento como **true** para indicar que os hyperlinks foram atualizados.<br/>            Defina este elemento como **false** para indicar que os hyperlinks estão desatualizados.<br/>            Leitura/gravação **bool**. |
| [`hyperlinks_changed`](/slides/python-net/pt/aspose.slides/idocumentproperties/hyperlinks_changed/) | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor.<br/>            O próximo produtor a abrir este documento deverá atualizar os relacionamentos de hyperlink com os novos hyperlinks especificados nesta parte.<br/>            Leitura/gravação **bool**. |
| [`slides`](/slides/python-net/pt/aspose.slides/idocumentproperties/slides/) | Especifica o número total de slides em um documento de apresentação.<br/pt/>            Somente leitura **int**. |
| [`hidden_slides`](/slides/python-net/pt/aspose.slides/idocumentproperties/hidden_slides/) | Especifica o número de slides ocultos em um documento de apresentação.<br/>            Somente leitura **int**. |
| [`notes`](/slides/python-net/pt/aspose.slides/idocumentproperties/notes/) | Especifica o número de slides em uma apresentação que contêm notas.<br/>            Somente leitura **int**. |
| [`paragraphs`](/slides/python-net/pt/aspose.slides/idocumentproperties/paragraphs/) | Especifica o número total de parágrafos encontrados em um documento, se aplicável.<br/>            Somente leitura **int**. |
| [`words`](/slides/python-net/pt/aspose.slides/idocumentproperties/words/) | Especifica o número total de palavras contidas em um documento.<br/>            Somente leitura **int**. |
| [`multimedia_clips`](/slides/python-net/pt/aspose.slides/idocumentproperties/multimedia_clips/) | Especifica o número total de clipes de áudio ou vídeo presentes no documento.<br/>            Somente leitura **int**. |
| [`titles_of_parts`](/slides/python-net/pt/aspose.slides/idocumentproperties/titles_of_parts/) | Especifica o título de cada parte do documento.<br/>            Estas partes não são partes do documento, mas representações conceituais de seções do documento.<br/>            Somente leitura **List[str]**. |
| [`heading_pairs`](/slides/python-net/pt/aspose.slides/idocumentproperties/heading_pairs/) | Indica o agrupamento de partes do documento e o número de partes em cada grupo.<br/>            Somente leitura **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/pt/aspose.slides/idocumentproperties/count_of_custom_properties/) | Retorna o número de propriedades personalizadas realmente contidas em uma coleção.<br/>            Somente leitura **int**. |

## Métodos

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtém um valor booleano nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtém um valor inteiro nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtém um valor DateTime nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtém um valor string nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Define uma propriedade personalizada booleana nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Define uma propriedade personalizada inteira nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Define uma propriedade personalizada DateTime nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Define uma propriedade personalizada string nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Define uma propriedade personalizada float nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Define uma propriedade personalizada double nomeada. |
| [`get_custom_property_name(self, index)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Retorna um nome de propriedade personalizada no índice especificado. |
| [`remove_custom_property(self, name)`](/slides/python-net/pt/aspose.slides/idocumentproperties/remove_custom_property/#str) | Remove uma propriedade personalizada associada a um nome especificado. |
| [`contains_custom_property(self, name)`](/slides/python-net/pt/aspose.slides/idocumentproperties/contains_custom_property/#str) | Verifica a presença de uma propriedade personalizada com um nome especificado. |
| [`clear_custom_properties(self)`](/slides/python-net/pt/aspose.slides/idocumentproperties/clear_custom_properties/#) | Remove todas as propriedades personalizadas. |
| [`clear_built_in_properties(self)`](/slides/python-net/pt/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Limpa e define valores padrão para todas as propriedades incorporadas. |
| [`get_sensitivity_labels(self)`](/slides/python-net/pt/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Obtém uma matriz de rótulos de sensibilidade das propriedades de documento personalizadas (Metadados do Microsoft Information Protection SDK). |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)