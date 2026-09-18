---
title: LoadOptions class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/loadoptions/
---
## LoadOptions classe

Permite especificar opções adicionais (como formato ou fonte padrão) ao carregar uma apresentação.

O tipo LoadOptions expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/loadoptions/__init__/#) | Cria novas opções de carregamento padrão. |
| [`__init__(self, load_format)`](/slides/python-net/pt/aspose.slides/loadoptions/__init__/#loadformat) | Cria novas opções de carregamento. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`load_format`](/slides/python-net/pt/aspose.slides/loadoptions/load_format/) | Retorna ou define o formato de uma apresentação a ser carregada.<br/>            Read/write [`LoadFormat`](/slides/python-net/pt/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/pt/aspose.slides/loadoptions/default_regular_font/) | Retorna ou define a fonte Regular usada caso a fonte de origem não seja encontrada.<br/>            Read/write **str**. |
| [`default_symbol_font`](/slides/python-net/pt/aspose.slides/loadoptions/default_symbol_font/) | Retorna ou define a fonte Symbol usada caso a fonte de origem não seja encontrada.<br/>            Read/write **str**. |
| [`default_asian_font`](/slides/python-net/pt/aspose.slides/loadoptions/default_asian_font/) | Retorna ou define a fonte Asian usada caso a fonte de origem não seja encontrada.<br/>            Read/write **str**. |
| [`password`](/slides/python-net/pt/aspose.slides/loadoptions/password/) | Obtém ou define a senha.<br/>            Read/write **str**. |
| [`only_load_document_properties`](/slides/python-net/pt/aspose.slides/loadoptions/only_load_document_properties/) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha.<br/>            Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada.<br/>            Valor false significa que a apresentação inteira criptografada deve ser carregada usando a senha correta.<br/>            Se a apresentação não estiver criptografada, o valor da propriedade é sempre ignorado.<br/>            Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, então as propriedades do documento não podem ser carregadas e uma exceção será lançada.<br/>            Read/write **bool**. |
| [`warning_callback`](/slides/python-net/pt/aspose.slides/loadoptions/warning_callback/) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado.<br/>            Read/write [`IWarningCallback`](/slides/python-net/pt/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/pt/aspose.slides/loadoptions/blob_management_options/) | Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs),<br/>            como uso de arquivos temporários ou tamanho máximo de BLOBs em memória. Essas opções destinam-se a definir a melhor relação desempenho/consumo de memória para um ambiente ou requisitos específicos.<br/>            Um Binary Large Object (BLOB) é um dado binário armazenado como uma entidade única – ou seja, um BLOB pode ser um áudio, vídeo ou a própria apresentação. |
| [`document_level_font_sources`](/slides/python-net/pt/aspose.slides/loadoptions/document_level_font_sources/) | Especifica fontes externas a serem usadas pela apresentação.<br/>            Estas fontes estão disponíveis para a apresentação durante todo o seu tempo de vida e não são compartilhadas com outras apresentações |
| [`interruption_token`](/slides/python-net/pt/aspose.slides/loadoptions/interruption_token/) | O token para monitorar solicitações de interrupção.<br/>            <br/>            Este token gerencia todo o tempo de vida da instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). Qualquer operação de longa duração, como carregar<br/>            ou salvar a apresentação, será interrompida chamando o método [`InterruptionTokenSource.interrupt`](/slides/python-net/pt/aspose.slides/interruptiontokensource/interrupt) de<br/>            [`InterruptionTokenSource`](/slides/python-net/pt/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/pt/aspose.slides/loadoptions/resource_loading_callback/) | Retorna ou define a interface de callback que gerencia o carregamento de recursos externos.<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/pt/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/pt/aspose.slides/loadoptions/spreadsheet_options/) | Obtém opções para planilhas. Por exemplo, essas opções afetam o cálculo de fórmulas para gráficos. |
| [`default_text_language`](/slides/python-net/pt/aspose.slides/loadoptions/default_text_language/) | Retorna ou define o idioma padrão para o texto da apresentação.<br/>            Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/pt/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Determina se o Aspose.Slides excluirá todos os objetos binários incorporados ao carregar a apresentação.<br/>            <br/>Os tipos de objetos binários incorporados:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/pt/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/pt/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |

### Ver Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)