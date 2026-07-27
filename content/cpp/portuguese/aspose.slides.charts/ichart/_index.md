---
title: IChart
second_title: Referência da API Aspose.Slides para C++
description: Representa um gráfico em um slide.
type: docs
weight: 573
url: /pt/aspose.slides.charts/ichart/
---
## IChart classe

Representa um gráfico em um slide.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Retorna um tema efetivo para este objeto temável. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Retorna o texto alternativo associado a uma forma. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Retorna o título do texto alternativo associado a uma forma. Leia [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | Fornece acesso aos eixos do gráfico. Somente leitura [IAxesManager](../iaxesmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | Retorna um objeto que permite alterar o formato da parede traseira de um gráfico 3D. Somente leitura [IChartWall](../ichartwall/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leia [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Somente leitura [IChart](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | Retorna informações sobre os dados vinculados ou incorporados associados a um gráfico. Somente leitura [IChartData](../ichartdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | Retorna uma tabela de dados de um gráfico. Somente leitura [IDataTable](../idatatable/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | Retorna o título do gráfico. Somente leitura [IChartTitle](../icharttitle/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Retorna o número de pontos de conexão na forma. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Retorna os dados personalizados da forma. Somente leitura [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | Retorna a forma de plotar células vazias em um gráfico. Leia [DisplayBlanksAsType](../displayblanksastype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Retorna o objeto [EffectFormat](../../aspose.slides/effectformat/) que contém efeitos de pixel aplicados a uma forma. Somente leitura [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Retorna o objeto [FillFormat](../../aspose.slides/fillformat/) que contém propriedades de formatação de preenchimento para uma forma. Somente leitura [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | Retorna um objeto que permite alterar o formato do piso de um gráfico 3D. Somente leitura [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Retorna as propriedades da moldura da forma. Leia [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Retorna os bloqueios da forma. Somente leitura [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | Determina se um gráfico tem uma tabela de dados. Leia **bool**. |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | Determina se um gráfico tem uma legenda. Leia **bool**. |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | Especifica que a área do gráfico deve ter cantos arredondados. Leia **bool**. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Determina se um gráfico tem um título visível. Leia **bool**. |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Obtém a altura da forma, medida em pontos. Leia **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Determina se a forma está oculta. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Retorna o hyperlink definido para clique do mouse. Leia [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Gerenciador de hyperlinks. Somente leitura [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Retorna o hyperlink definido para passar o mouse sobre. Leia [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | Obtém a opção 'Marcar como decorativo'. Leia/grava **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Determina se a forma está agrupada. Somente leitura **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Determina se a forma é TextHolder. Somente leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | Retorna uma legenda para um gráfico. Somente leitura [ILegend](../ilegend/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Retorna o objeto [LineFormat](../../aspose.slides/lineformat/) que contém propriedades de formatação de linha para uma forma. Somente leitura [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Retorna o nome de uma forma. Leia [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Retorna um identificador único com escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código de interop referencie a forma de forma confiável a partir de qualquer lugar do documento. Somente leitura **uint32_t**. Veja também [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Retorna o objeto pai [GroupShape](../../aspose.slides/groupshape/) se a forma estiver agrupada. Caso contrário, retorna nulo. Somente leitura [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Retorna o placeholder para uma forma. Somente leitura [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | Representa a área de plotagem de um gráfico. Somente leitura [IChartPlotArea](../ichartplotarea/). |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | Determina se apenas as células visíveis são plotadas. Falso para plotar tanto células visíveis quanto ocultas. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Retorna as propriedades brutas da moldura da forma. Leia [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Retorna o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leia **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | Retorna uma rotação 3D de um gráfico. Somente leitura [IRotation3D](../irotation3d/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Retorna os bloqueios da forma. Somente leitura [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | Retorna um objeto que permite alterar o formato da parede lateral de um gráfico 3D. Somente leitura [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | Retorna o estilo do gráfico. Leia [StyleType](../styletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retorna o formato de texto do gráfico. Somente leitura [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | Retorna o gerenciador de tema de substituição. Somente leitura [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Retorna o objeto [ThreeDFormat](../../aspose.slides/threedformat/) que contém propriedades de formatação de linha para uma forma. Somente leitura [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | Retorna o tipo de gráfico. Leia [ChartType](../charttype/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Retorna um identificador interno com escopo de apresentação destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura **uint32_t**. Veja também [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | Especifica as formas desenhadas sobre o gráfico. Somente leitura [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Obtém a largura da forma, medida em pontos. Leia **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Obtém a coordenada x do canto superior esquerdo da forma, medida em pontos. Leia **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Obtém a coordenada y do canto superior esquerdo da forma, medida em pontos. Leia **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Retorna a posição de uma forma na ordem Z. Shapes[0] retorna a forma no fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem Z. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual herda). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hashing de objetos personalizados. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Retorna a miniatura da forma. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) tipo de limites da miniatura da forma é usado por padrão. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Retorna a miniatura da forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Define que esta forma não é um placeholder. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Define o texto alternativo associado a uma forma. Escreva [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Define o título do texto alternativo associado a uma forma. Escreva [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Escreva [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | Define a forma de plotar células vazias em um gráfico. Escreva [DisplayBlanksAsType](../displayblanksastype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Define as propriedades da moldura da forma. Escreva [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | Determina se um gráfico tem uma tabela de dados. Escreva **bool**. |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | Determina se um gráfico tem uma legenda. Escreva **bool**. |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | Especifica que a área do gráfico deve ter cantos arredondados. Escreva **bool**. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Determina se um gráfico tem um título visível. Escreva **bool**. |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Define a altura da forma, medida em pontos. Escreva **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Determina se a forma está oculta. Escreva **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Define o hyperlink definido para clique do mouse. Escreva [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Define o hyperlink definido para passar o mouse sobre. Escreva [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | Define a opção 'Marcar como decorativo'. Leia/grava **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Define o nome de uma forma. Escreva [System::String](../../system/string/). |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | Determina se apenas as células visíveis são plotadas. Falso para plotar tanto células visíveis quanto ocultas. Escreva **bool**. |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Define as propriedades brutas da moldura da forma. Escreva [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Escreva **float**. |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. Escreva **bool**. |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | Define o estilo do gráfico. Escreva [StyleType](../styletype/). |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | Define o tipo de gráfico. Escreva [ChartType](../charttype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Define a largura da forma, medida em pontos. Escreva **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Define a coordenada x do canto superior esquerdo da forma, medida em pontos. Escreva **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Define a coordenada y do canto superior esquerdo da forma, medida em pontos. Escreva **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | Calcula os valores reais dos elementos do gráfico. Os valores reais incluem a posição dos elementos que implementam a interface [IActualLayout](../iactuallayout/) ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) e os valores reais dos eixos ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Salva o conteúdo de [Shape](../../aspose.slides/shape/) como arquivo SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Salva o conteúdo de [Shape](../../aspose.slides/shape/) como arquivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Classe [IFormattedTextContainer](../iformattedtextcontainer/)
* Classe [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)