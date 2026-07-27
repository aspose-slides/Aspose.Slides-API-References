---
title: ILineFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa o formato de uma linha.
type: docs
weight: 2757
url: /pt/aspose.slides/ilineformat/
---
## classe ILineFormat


Representa o formato de uma linha.

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | Determina se duas instâncias de [LineFormat](../lineformat/) são iguais. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | Retorna o alinhamento da linha. Leia [LineAlignment](../linealignment/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | Retorna o comprimento da ponta da seta no início da linha. Leia [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | Retorna o estilo da ponta da seta no início da linha. Leia [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | Retorna a largura da ponta da seta no início da linha. Leia [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | Retorna o estilo de terminação da linha. Leia [LineCapStyle](../linecapstyle/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | Retorna o padrão de traços personalizado. Leia **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | Retorna o estilo de traço da linha. Leia [LineDashStyle](../linedashstyle/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | Retorna o comprimento da ponta da seta no final da linha. Leia [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | Retorna o estilo da ponta da seta no final da linha. Leia [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | Retorna a largura da ponta da seta no final da linha. Leia [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | Retorna o formato de preenchimento de uma linha. Somente leitura [ILineFillFormat](../ilinefillformat/). |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | Retorna **true** se o formato da linha não estiver definido (acabado de ser criado, padrão). Somente leitura **bool**. |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | Retorna o estilo de junção das linhas. Leia [LineJoinStyle](../linejoinstyle/). |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | Retorna o limite de mitra (miter) de uma linha. Leia **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | Retorna o formato de esboço de uma linha. Somente leitura [ISketchFormat](../isketchformat/). |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | Retorna o estilo da linha. Leia [LineStyle](../linestyle/). |
| virtual **double** [get_Width](./get_width/)() | Retorna a largura de uma linha. Leia **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtém os dados de formatação efetiva da linha com a herança aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia ao chamado C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | Define o alinhamento da linha. Escrita [LineAlignment](../linealignment/). |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | Define o comprimento da ponta da seta no início da linha. Escrita [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | Define o estilo da ponta da seta no início da linha. Escrita [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | Define a largura da ponta da seta no início da linha. Escrita [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | Define o estilo de terminação da linha. Escrita [LineCapStyle](../linecapstyle/). |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Define o padrão de traços personalizado. Escrita **float**[]. |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | Define o estilo de traço da linha. Escrita [LineDashStyle](../linedashstyle/). |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | Define o comprimento da ponta da seta no final da linha. Escrita [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | Define o estilo da ponta da seta no final da linha. Escrita [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | Define a largura da ponta da seta no final da linha. Escrita [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | Define o estilo de junção das linhas. Escrita [LineJoinStyle](../linejoinstyle/). |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | Define o limite de mitra de uma linha. Escrita **float**. |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | Define o estilo da linha. Escrita [LineStyle](../linestyle/). |
| virtual void [set_Width](./set_width/)(**double**) | Define a largura de uma linha. Escrita **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Diminui e devolve o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Diminui o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Class [ILineParamSource](../ilineparamsource/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)