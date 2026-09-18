---
title: DocumentProperties class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/documentproperties/
---
## DocumentProperties classe

Representa propriedades de uma apresentação.

O tipo DocumentProperties expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/documentproperties/__init__/#) | Inicializa nova instância da classe [`DocumentProperties`](/slides/python-net/pt/aspose.slides/documentproperties). |

## Propriedades

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/pt/aspose.slides/documentproperties/app_version/) | Retorna a versão do aplicativo.<br/>            Somente leitura **str**. |
| [`name_of_application`](/slides/python-net/pt/aspose.slides/documentproperties/name_of_application/) | Retorna ou define o nome da aplicação.<br/>            Leitura/gravação **str**. |
| [`company`](/slides/python-net/pt/aspose.slides/documentproperties/company/) | Retorna ou define a propriedade da empresa.<br/>            Leitura/gravação **str**. |
| [`manager`](/slides/python-net/pt/aspose.slides/documentproperties/manager/) | Retorna ou define a propriedade do gerente.<br/>            Leitura/gravação **str**. |
| [`presentation_format`](/slides/python-net/pt/aspose.slides/documentproperties/presentation_format/) | Retorna ou define o formato pretendido de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`shared_doc`](/slides/python-net/pt/aspose.slides/documentproperties/shared_doc/) | Determina se a apresentação é compartilhada entre várias pessoas.<br/>            Leitura/gravação **bool**. |
| [`application_template`](/slides/python-net/pt/aspose.slides/documentproperties/application_template/) | Retorna ou define o modelo de uma aplicação.<br/>            Leitura/gravação **str**. |
| [`total_editing_time`](/slides/python-net/pt/aspose.slides/documentproperties/total_editing_time/) | Tempo total de edição de uma apresentação.<br/>            Leitura/gravação **System.TimeSpan**. |
| [`title`](/slides/python-net/pt/aspose.slides/documentproperties/title/) | Retorna ou define o título de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`subject`](/slides/python-net/pt/aspose.slides/documentproperties/subject/) | Retorna ou define o assunto de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`author`](/slides/python-net/pt/aspose.slides/documentproperties/author/) | Retorna ou define o autor de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`keywords`](/slides/python-net/pt/aspose.slides/documentproperties/keywords/) | Retorna ou define as palavras-chave de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`comments`](/slides/python-net/pt/aspose.slides/documentproperties/comments/) | Retorna ou define os comentários de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`category`](/slides/python-net/pt/aspose.slides/documentproperties/category/) | Retorna ou define a categoria de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`created_time`](/slides/python-net/pt/aspose.slides/documentproperties/created_time/) | Retorna a data em que uma apresentação foi criada.<br/>            Os valores estão em UTC.<br/>            Leitura/gravação **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/pt/aspose.slides/documentproperties/last_saved_time/) | Retorna a data em que uma apresentação foi modificada pela última vez.<br/>            Os valores estão em UTC.<br/>            Somente leitura no caso de Presentation.DocumentProperties (porque será atualizado internamente durante o processo de salvamento do objeto IPresentation). <br/>            Pode ser alterado via instância DocumentProperties retornada pelo método [`IPresentationInfo.read_document_properties`](/slides/python-net/pt/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Consulte o exemplo em **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** resumo do método. |
| [`last_printed`](/slides/python-net/pt/aspose.slides/documentproperties/last_printed/) | Retorna a data em que uma apresentação foi impressa pela última vez.<br/>            Leitura/gravação **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/pt/aspose.slides/documentproperties/last_saved_by/) | Retorna ou define o nome da última pessoa que modificou uma apresentação.<br/>            Leitura/gravação **str**. |
| [`revision_number`](/slides/python-net/pt/aspose.slides/documentproperties/revision_number/) | Retorna ou define o número de revisão da apresentação.<br/>            Leitura/gravação **int**. |
| [`content_status`](/slides/python-net/pt/aspose.slides/documentproperties/content_status/) | Retorna ou define o status do conteúdo de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`content_type`](/slides/python-net/pt/aspose.slides/documentproperties/content_type/) | Retorna ou define o tipo de conteúdo de uma apresentação.<br/>            Leitura/gravação **str**. |
| [`hyperlink_base`](/slides/python-net/pt/aspose.slides/documentproperties/hyperlink_base/) | Retorna ou define a propriedade HyperlinkBase do documento.<br/>            Leitura/gravação **str**. |
| [`count_of_custom_properties`](/slides/python-net/pt/aspose.slides/documentproperties/count_of_custom_properties/) | Retorna o número de propriedades personalizadas realmente contidas em uma coleção.<br/>            Somente leitura **int**. |
| [`scale_crop`](/slides/python-net/pt/aspose.slides/documentproperties/scale_crop/) | Indica o modo de exibição da miniatura do documento. <br/>            Defina este elemento como **true**  para habilitar o dimensionamento da miniatura do documento para a exibição. <br/>            Defina este elemento como **false**  para habilitar o recorte da miniatura do documento para mostrar apenas as seções que se ajustam à exibição.<br/>            Leitura/gravação **bool**. |
| [`links_up_to_date`](/slides/python-net/pt/aspose.slides/documentproperties/links_up_to_date/) | Indica se os hyperlinks em um documento estão atualizados. <br/>            Defina este elemento como **true**  para indicar que os hyperlinks foram atualizados. <br/>            Defina este elemento como **false**  para indicar que os hyperlinks estão desatualizados.<br/>            Leitura/gravação **bool**. |
| [`hyperlinks_changed`](/slides/python-net/pt/aspose.slides/documentproperties/hyperlinks_changed/) | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. <br/>            O próximo produtor a abrir este documento deverá atualizar os relacionamentos de hyperlink com os novos hyperlinks especificados nesta parte.<br/>            Leitura/gravação **bool**. |
| [`slides`](/slides/python-net/pt/aspose.slides/documentproperties/slides/) | Retorna o número total de slides em um documento de apresentação.<br/pt/>            Somente leitura **int**. |
| [`hidden_slides`](/slides/python-net/pt/aspose.slides/documentproperties/hidden_slides/) | Retorna o número de slides ocultos em um documento de apresentação.<br/>            Somente leitura **int**. |
| [`notes`](/slides/python-net/pt/aspose.slides/documentproperties/notes/) | Retorna o número de slides em uma apresentação que contêm anotações.<br/>            Somente leitura **int**. |
| [`paragraphs`](/slides/python-net/pt/aspose.slides/documentproperties/paragraphs/) | Retorna o número total de parágrafos encontrados em um documento, se aplicável.<br/>            Somente leitura **int**. |
| [`words`](/slides/python-net/pt/aspose.slides/documentproperties/words/) | Retorna o número total de palavras contidas em um documento.<br/>            Somente leitura **int**. |
| [`multimedia_clips`](/slides/python-net/pt/aspose.slides/documentproperties/multimedia_clips/) | Retorna o número total de clipes de áudio ou vídeo presentes no documento.<br/>            Somente leitura **int**. |
| [`titles_of_parts`](/slides/python-net/pt/aspose.slides/documentproperties/titles_of_parts/) | Especifica o título de cada parte do documento. <br/>            Essas partes não são partes do documento, mas representações conceituais de seções do documento.<br/>            Somente leitura **List[str]**. |
| [`heading_pairs`](/slides/python-net/pt/aspose.slides/documentproperties/heading_pairs/) | Indica a agrupamento das partes do documento e o número de partes em cada grupo.<br/>            Somente leitura **List[IHeadingPair]**. |

## Métodos

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtém um valor booleano nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtém um valor inteiro nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtém um valor DateTime nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtém um valor string nomeado das propriedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Define uma propriedade personalizada boolean nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Define uma propriedade personalizada inteira nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Define uma propriedade personalizada DateTime nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Define uma propriedade personalizada string nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Define uma propriedade personalizada float nomeada. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pt/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Define uma propriedade personalizada double nomeada. |
| [`get_custom_property_name(self, index)`](/slides/python-net/pt/aspose.slides/documentproperties/get_custom_property_name/#int) | Retorna o nome de uma propriedade personalizada no índice especificado. |
| [`remove_custom_property(self, name)`](/slides/python-net/pt/aspose.slides/documentproperties/remove_custom_property/#str) | Remove uma propriedade personalizada associada a um nome especificado. |
| [`contains_custom_property(self, name)`](/slides/python-net/pt/aspose.slides/documentproperties/contains_custom_property/#str) | Verifica a presença de uma propriedade personalizada com um nome especificado. |
| [`clear_custom_properties(self)`](/slides/python-net/pt/aspose.slides/documentproperties/clear_custom_properties/#) | Remove todas as propriedades personalizadas. |
| [`get_sensitivity_labels(self)`](/slides/python-net/pt/aspose.slides/documentproperties/get_sensitivity_labels/#) | Obtém um array de rótulos de sensibilidade das propriedades personalizadas do documento (Microsoft Information Protection SDK Metadata). |
| [`clear_built_in_properties(self)`](/slides/python-net/pt/aspose.slides/documentproperties/clear_built_in_properties/#) | Limpa e define valores padrão para todas as propriedades incorporadas. |
| [`clone(self)`](/slides/python-net/pt/aspose.slides/documentproperties/clone/#) | Clona o objeto atual |
| [`clone_t(self)`](/slides/python-net/pt/aspose.slides/documentproperties/clone_t/#) | Clona o objeto atual |


### Veja Também
* classe [`DocumentProperties`](/slides/python-net/pt/aspose.slides/documentproperties)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)