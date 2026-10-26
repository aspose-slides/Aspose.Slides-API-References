---
title: ITrendline
second_title: Aspose.Slides para C++ Referência da API
description: Classe representa linha de tendência da série de gráfico
type: docs
weight: 1223
url: /pt/aspose.slides.charts/itrendline/
---
## ITrendline classe

Classe representa linha de tendência da série de gráfico

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializa TextFrameForOverriding com o texto no parâmetro \"text\". Se TextFrameForOverriding já estiver inicializado, então simplesmente altera seu texto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual **double** [get_Backward](./get_backward/)() | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo analisada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Leitura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Leitura **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Representa o formato da linha de tendência. Leitura [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo analisada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Leitura **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Especifica o valor onde a linha de tendência cruza o eixo y. Esta propriedade deve ser suportada somente quando o tipo de linha de tendência é exp, linear ou poly. Leitura **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Especifica a ordem da linha de tendência polinomial. É ignorado para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Leitura **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes da linha de tendência. O valor deve estar entre 2 e 255. Leitura **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Representa a entrada da legenda relacionada a esta linha de tendência. Somente leitura [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retorna o formato de texto do gráfico. Somente leitura [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Pode conter um texto formatado rico. Se esta propriedade não for nula, então este valor de texto formatado substitui o texto gerado automaticamente. O texto gerado automaticamente é uma propriedade implícita do rótulo de dados, do rótulo da unidade de exibição do eixo de valores, do título do eixo, do título do gráfico, do rótulo da linha de tendência. O texto gerado automaticamente é formatado com a propriedade [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Somente leitura [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Obtém o nome da linha de tendência. Leitura [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Obtém o tipo da linha de tendência. Leitura [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_Backward](./set_backward/)(**double**) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo analisada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Grava **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Grava **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Grava **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Representa o formato da linha de tendência. Grava [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo analisada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Grava **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Especifica o valor onde a linha de tendência cruza o eixo y. Esta propriedade deve ser suportada somente quando o tipo de linha de tendência é exp, linear ou poly. Grava **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Especifica a ordem da linha de tendência polinomial. É ignorado para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Grava **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes da linha de tendência. O valor deve estar entre 2 e 255. Grava **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Define o nome da linha de tendência. Grava [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Define o tipo da linha de tendência. Grava [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IOverridableText](../ioverridabletext/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)