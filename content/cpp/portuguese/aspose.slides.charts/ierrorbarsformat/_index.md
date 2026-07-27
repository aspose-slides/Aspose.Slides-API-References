---
title: IErrorBarsFormat
second_title: Referência da API Aspose.Slides para C++
description: "Representa barras de erro de séries de gráfico. Os valores personalizados de ErrorBars estão em IChartDataPointCollection (na propriedade IChartDataPoint::get_ErrorBarsCustomValues())."
type: docs
weight: 1028
url: /pt/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat classe


Representa barras de erro de séries de gráfico. Os valores personalizados de ErrorBars estão em [IChartDataPointCollection](../ichartdatapointcollection/) (na propriedade [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)).

```cpp
class IErrorBarsFormat : public Aspose::Slides::Charts::IChartComponent
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Representa o formato das barras de erro. Leitura [IFormat](../iformat/). |
| virtual **bool** [get_HasEndCap](./get_hasendcap/)() | Especifica que uma tampa final não é desenhada nas barras de erro. Leitura **bool**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Obtém a visibilidade das barras de erro. Leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() | Obtém o tipo das barras de erro. Leitura [ErrorBarType](../errorbartype/). |
| virtual **float** [get_Value](./get_value/)() | Obtém o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Leitura **float**. |
| virtual [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() | Representa as possíveis maneiras de determinar o comprimento das barras de erro. No caso de tipo de valor personalizado, para especificar o valor use a propriedade [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) do ponto de dados específico na coleção DataPoints da série.\n\nLeitura [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Representa o formato das barras de erro. Grava [IFormat](../iformat/). |
| virtual void [set_HasEndCap](./set_hasendcap/)(**bool**) | Especifica que uma tampa final não é desenhada nas barras de erro. Grava **bool**. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Define a visibilidade das barras de erro. Grava **bool**. |
| virtual void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) | Define o tipo das barras de erro. Grava [ErrorBarType](../errorbartype/). |
| virtual void [set_Value](./set_value/)(**float**) | Define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Grava **float**. |
| virtual void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) | Representa as possíveis maneiras de determinar o comprimento das barras de erro. No caso de tipo de valor personalizado, para especificar o valor use a propriedade [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) do ponto de dados específico na coleção DataPoints da série.\n\nGrava [ErrorBarValueType](../errorbarvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Ver Também

* Classe [IChartComponent](../ichartcomponent/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)