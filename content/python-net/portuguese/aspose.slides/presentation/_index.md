---
title: Presentation class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/presentation/
---
## Presentation classe

Representa uma apresentação do Microsoft PowerPoint.

O tipo Presentation expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/presentation/__init__/#) | Este construtor cria uma nova apresentação do zero.<br/>            A apresentação criada tem um slide vazio. |
| [`__init__(self, load_options)`](/slides/python-net/pt/aspose.slides/presentation/__init__/#loadoptions) | Este construtor cria uma nova apresentação do zero.<br/>            A apresentação criada tem um slide vazio. |
| [`__init__(self, stream)`](/slides/python-net/pt/aspose.slides/presentation/__init__/#iorawiobase) | Este construtor é o mecanismo principal para ler uma Presentation existente. |
| [`__init__(self, stream, load_options)`](/slides/python-net/pt/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Este construtor é o mecanismo principal para ler uma Presentation existente. |
| [`__init__(self, file)`](/slides/python-net/pt/aspose.slides/presentation/__init__/#str) | Este construtor obtém o caminho do arquivo fonte a partir do qual<br/>             o conteúdo da Presentation é lido. |
| [`__init__(self, file, load_options)`](/slides/python-net/pt/aspose.slides/presentation/__init__/#str-loadoptions) | Este construtor obtém o caminho do arquivo fonte a partir do qual<br/>            o conteúdo da Presentation é lido. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`current_date_time`](/slides/python-net/pt/aspose.slides/presentation/current_date_time/) | Retorna ou define a data e hora que substituirá o conteúdo dos campos datetime.<br/>            Hora de criação deste objeto Presentation por padrão.<br/>            Leitura/gravação **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/presentation/header_footer_manager/) | Retorna o gerenciador HeaderFooter atual.<br/>            Somente leitura [`IPresentationHeaderFooterManager`](/slides/python-net/pt/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/pt/aspose.slides/presentation/protection_manager/) | Obtém o gerenciador das permissões desta apresentação.<br/>            Somente leitura [`IProtectionManager`](/slides/python-net/pt/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/pt/aspose.slides/presentation/slides/) | Retorna uma lista de todos os slides definidos na apresentação.<br/pt/>            Somente leitura [`ISlideCollection`](/slides/python-net/pt/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/pt/aspose.slides/presentation/sections/) | Retorna uma lista de todas as seções de slides definidas na apresentação.<br/>            Somente leitura [`ISectionCollection`](/slides/python-net/pt/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/pt/aspose.slides/presentation/slide_size/) | Retorna o objeto de tamanho do slide.<br/>            Somente leitura [`ISlideSize`](/slides/python-net/pt/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/pt/aspose.slides/presentation/notes_size/) | Retorna o objeto de tamanho do slide de notas.<br/>            Somente leitura [`INotesSize`](/slides/python-net/pt/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/pt/aspose.slides/presentation/layout_slides/) | Retorna uma lista de todos os slides de layout definidos na apresentação.<br/>            Somente leitura [`IGlobalLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/pt/aspose.slides/presentation/masters/) | Retorna uma lista de todos os slides mestre definidos na apresentação.<br/>            Somente leitura [`IMasterSlideCollection`](/slides/python-net/pt/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/pt/aspose.slides/presentation/master_notes_slide_manager/) | Retorna o gerenciador mestre de notas.<br/>            Somente leitura [`IMasterNotesSlideManager`](/slides/python-net/pt/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/pt/aspose.slides/presentation/master_handout_slide_manager/) | Retorna o gerenciador mestre de folhetos.<br/>            Somente leitura [`IMasterHandoutSlideManager`](/slides/python-net/pt/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/pt/aspose.slides/presentation/fonts_manager/) | Retorna o gerenciador de fontes.<br/>            Somente leitura [`IFontsManager`](/slides/python-net/pt/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/pt/aspose.slides/presentation/default_text_style/) | Retorna o estilo de texto padrão para formas.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/pt/aspose.slides/presentation/comment_authors/) | Retorna a coleção de autores de comentários.<br/>            Somente leitura [`ICommentAuthorCollection`](/slides/python-net/pt/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/pt/aspose.slides/presentation/document_properties/) | Retorna o objeto DocumentProperties que contém propriedades padrão e personalizadas do documento.<br/>            Somente leitura [`IDocumentProperties`](/slides/python-net/pt/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/pt/aspose.slides/presentation/images/) | Retorna a coleção de todas as imagens na apresentação.<br/>            Somente leitura [`IImageCollection`](/slides/python-net/pt/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/pt/aspose.slides/presentation/audios/) | Retorna a coleção de todos os arquivos de áudio incorporados na apresentação.<br/>            Somente leitura [`IAudioCollection`](/slides/python-net/pt/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/pt/aspose.slides/presentation/videos/) | Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação.<br/>            Somente leitura [`IVideoCollection`](/slides/python-net/pt/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/pt/aspose.slides/presentation/slide_show_settings/) | Retorna as configurações de apresentação de slides para a apresentação. |
| [`digital_signatures`](/slides/python-net/pt/aspose.slides/presentation/digital_signatures/) | Retorna a coleção de assinaturas usadas para assinar a apresentação.<br/>            Somente leitura [`IDigitalSignatureCollection`](/slides/python-net/pt/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/presentation/custom_data/) | Retorna os dados personalizados da apresentação.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/pt/aspose.slides/presentation/all_custom_xml_parts/) | Retorna todas as partes de dados personalizados na apresentação.<br/>            Somente leitura [`ICustomXmlPart`](/slides/python-net/pt/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/pt/aspose.slides/presentation/vba_project/) | Obtém ou define o projeto VBA com macros da apresentação.<br/>            Leitura/gravação [`IVbaProject`](/slides/python-net/pt/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/presentation/hyperlink_queries/) | Fornece acesso fácil a todos os hyperlinks contidos em todos os slides da apresentação (não nos slides mestre, de layout ou de notas).<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/pt/aspose.slides/presentation/view_properties/) | Obtém as propriedades de visualização da apresentação.<br/>            Somente leitura [`IViewProperties`](/slides/python-net/pt/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/pt/aspose.slides/presentation/first_slide_number/) | Representa o número do primeiro slide na apresentação |
| [`sensitivity_labels`](/slides/python-net/pt/aspose.slides/presentation/sensitivity_labels/) | Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação.<br/>            Somente leitura [`ISensitivityLabelCollection`](/slides/python-net/pt/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/pt/aspose.slides/presentation/source_format/) | Retorna informações sobre de qual formato a apresentação foi carregada.<br/>            Somente leitura [`SourceFormat`](/slides/python-net/pt/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/pt/aspose.slides/presentation/master_theme/) | Retorna o tema mestre.<br/>            Somente leitura [`IMasterTheme`](/slides/python-net/pt/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/pt/aspose.slides/presentation/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/pt/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado. |
| [`save(self, stream, format)`](/slides/python-net/pt/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Salva todos os slides de uma apresentação em um fluxo no formato especificado. |
| [`save(self, fname, format, options)`](/slides/python-net/pt/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/pt/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais. |
| [`save(self, options)`](/slides/python-net/pt/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Salva todos os slides de uma apresentação em um conjunto de arquivos representando a marcação XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/pt/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Salva os slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/pt/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva os slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página. |
| [`save(self, stream, slides, format)`](/slides/python-net/pt/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Salva os slides especificados de uma apresentação em um fluxo no formato especificado mantendo o número da página. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/pt/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva os slides especificados de uma apresentação em um fluxo no formato especificado mantendo o número da página. |
| [`get_images(self, options)`](/slides/python-net/pt/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Retorna objetos Image para todos os slides de uma apresentação. |
| [`get_images(self, options, slides)`](/slides/python-net/pt/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Retorna objetos Thumbnail Image para os slides especificados de uma apresentação. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Retorna objetos Thumbnail Image para todos os slides de uma apresentação com dimensionamento personalizado. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Retorna objetos Thumbnail Image para os slides especificados de uma apresentação com dimensionamento personalizado. |
| [`get_images(self, options, image_size)`](/slides/python-net/pt/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Retorna objetos Thumbnail Image para todos os slides de uma apresentação com tamanho especificado. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/pt/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Retorna objetos Thumbnail Image para os slides especificados de uma apresentação com tamanho especificado. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/pt/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Realça todas as correspondências do texto de amostra com a cor especificada. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/pt/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Realça todas as correspondências do texto de amostra com a cor especificada. |
| [`get_slide_by_id(self, id)`](/slides/python-net/pt/aspose.slides/presentation/get_slide_by_id/#int) | Retorna um Slide, MasterSlide ou LayoutSlide por Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/presentation/join_portions_with_same_formatting/#) | Une sequências com a mesma formatação em todos os parágrafos em todas as formas aceitáveis em todos os slides. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/pt/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Realça todas as correspondências da expressão regular com a cor especificada. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/pt/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/pt/aspose.slides/presentation/replace_regex/#str-str) | Substitui todas as correspondências da expressão regular pela string especificada. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)