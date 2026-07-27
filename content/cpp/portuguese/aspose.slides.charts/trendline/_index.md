---
title: Trendline
second_title: Referência da API Aspose.Slides para C++
description: Classe representa a linha de tendência da série de gráfico
type: docs
weight: 1366
url: /pt/aspose.slides.charts/trendline/
---
## Classe Trendline

Classe representa a linha de tendência da série de gráfico

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Métodos

| Método | Descrição |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializa TextFrameForOverriding com o texto no parâmetro \"text\". Se TextFrameForOverriding já estiver inicializado, então simplesmente altera seu texto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **double** [get_Backward](./get_backward/)() override | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo trendada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Leitura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retorna o gráfico pai. Somente leitura [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Leitura **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Representa o formato da linha de tendência. Leitura [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo trendada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Leitura **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Especifica o valor onde a linha de tendência deve cruzar o eixo y. Esta propriedade deve ser suportada apenas quando o tipo de linha de tendência é exp, linear ou poly. Leitura **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Especifica a ordem da linha de tendência polinomial. É ignorado para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Leitura **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes de linha de tendência. O valor deve estar entre 2 e 255. Leitura **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Representa a entrada da legenda relacionada a esta linha de tendência. Somente leitura [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Retorna o formato de texto. Somente leitura [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Pode conter um texto formatado rico. Se esta propriedade não for nula, então este valor de texto formatado sobrescreve o texto gerado automaticamente do rótulo de dados. Texto gerado automaticamente do rótulo de dados significa texto que é controlado pelas propriedades ShowSeriesName, ShowValue, ... e é formatado com a propriedade TextFormatManager.TextFormat. Somente leitura [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Obtém o nome da linha de tendência. Leitura [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Obtém o tipo da linha de tendência. Leitura [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, realmente, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, realmente, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Backward](./set_backward/)(**double**) override | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo trendada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Escrita **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Escrita **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Escrita **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Representa o formato da linha de tendência. Escrita [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo trendada. Em gráficos de dispersão e não dispersão, o valor deve ser qualquer valor não negativo. Escrita **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Especifica o valor onde a linha de tendência deve cruzar o eixo y. Esta propriedade deve ser suportada apenas quando o tipo de linha de tendência é exp, linear ou poly. Escrita **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Especifica a ordem da linha de tendência polinomial. É ignorado para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Escrita **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes de linha de tendência. O valor deve estar entre 2 e 255. Escrita **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Define o nome da linha de tendência. Escrita [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Define o tipo da linha de tendência. Escrita [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [ITrendline](../itrendline/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)