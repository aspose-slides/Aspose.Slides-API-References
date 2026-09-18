---
title: ILoadOptions class
second_title: Aspose.Slides para Python via .NET - Referência da API
description: 
type: docs
url: /pt/aspose.slides/iloadoptions/
---
## ILoadOptions classe

Permite especificar opções adicionais (como formato ou fonte padrão) ao carregar uma apresentação.

O tipo ILoadOptions expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`load_format`](/slides/python-net/pt/aspose.slides/iloadoptions/load_format/) | Retorna ou define o formato de uma apresentação a ser carregada.<br/>            Leitura/Escrita [`LoadFormat`](/slides/python-net/pt/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides/iloadoptions/default_regular_font/) | Retorna ou define a fonte Regular usada caso a fonte de origem não seja encontrada.<br/>            Leitura-escrita **str**. |
| [`default_symbol_font`](/slides/python-net/pt/aspose.slides/iloadoptions/default_symbol_font/) | Retorna ou define a fonte Symbol usada caso a fonte de origem não seja encontrada.<br/>            Leitura-escrita **str**. |
| [`default_asian_font`](/slides/python-net/pt/aspose.slides/iloadoptions/default_asian_font/) | Retorna ou define a fonte Asian usada caso a fonte de origem não seja encontrada.<br/>            Leitura-escrita **str**. |
| [`password`](/slides/python-net/pt/aspose.slides/iloadoptions/password/) | Obtém ou define a senha.<br/>            Leitura-escrita **str**. |
| [`only_load_document_properties`](/slides/python-net/pt/aspose.slides/iloadoptions/only_load_document_properties/) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha.<br/>            Valor true significa que somente as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada.<br/>            Valor false significa que toda a apresentação criptografada deve ser carregada usando a senha correta.<br/>            Se a apresentação não estiver criptografada, o valor da propriedade será sempre ignorado.<br/>            Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, então as propriedades do documento não poderão ser carregadas e uma exceção será lançada.<br/>            Leitura-escrita **bool**. |
| [`warning_callback`](/slides/python-net/pt/aspose.slides/iloadoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Leitura/Escrita [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/pt/aspose.slides/iloadoptions/blob_management_options/) | Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs),<br/>            como o uso de arquivos temporários ou o número máximo de bytes de BLOBs na memória. Essas opções têm como objetivo configurar<br/>            a melhor relação desempenho/consumo de memória para um ambiente ou requisitos específicos.<br/>            Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade – ou seja, um BLOB pode<br/>            ser um áudio, vídeo ou a própria apresentação. |
| [`document_level_font_sources`](/slides/python-net/pt/aspose.slides/iloadoptions/document_level_font_sources/) | Especifica as fontes externas a serem usadas pela apresentação.<br/>            Essas fontes estão disponíveis para a apresentação durante todo o seu tempo de vida e não são compartilhadas com outras apresentações |
| [`interruption_token`](/slides/python-net/pt/aspose.slides/iloadoptions/interruption_token/) | O token para monitorar solicitações de interrupção.<br/>            <br/>            Este token gerencia todo o tempo de vida da instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). Qualquer operação de longa duração, como carregamento ou salvamento de apresentação, será interrompida ao chamar o método [`IInterruptionTokenSource.interrupt`](/slides/python-net/pt/aspose.slides/iinterruptiontokensource/interrupt) do [`IInterruptionTokenSource`](/slides/python-net/pt/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/pt/aspose.slides/iloadoptions/resource_loading_callback/) | Retorna ou define a interface de callback que gerencia o carregamento de recursos externos.<br/>            Leitura/Escrita [`IResourceLoadingCallback`](/slides/python-net/pt/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/pt/aspose.slides/iloadoptions/spreadsheet_options/) | Representa opções que podem ser usadas para especificar comportamento adicional de planilhas. |
| [`default_text_language`](/slides/python-net/pt/aspose.slides/iloadoptions/default_text_language/) | Retorna ou define o idioma padrão para o texto da apresentação.<br/>             Leitura/Escrita **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/pt/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Determina se o Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação.<br/>            <br/>Os tipos de objetos binários incorporados:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/pt/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/pt/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Leitura/Escrita **bool**. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)