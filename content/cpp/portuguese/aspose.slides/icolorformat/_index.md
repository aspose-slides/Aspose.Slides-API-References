---
title: IColorFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa uma cor usada em uma apresentação.
type: docs
weight: 1691
url: /pt/aspose.slides/icolorformat/
---
## IColorFormat classe

Representa uma cor usada em uma apresentação.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Copia o formato de cor de "color". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual **uint8_t** [get_B](./get_b/)() | Retorna o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Leitura [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Retorna a operação de transformação de cor aplicada à cor no índice especificado. Leitura/escrita [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Retorna a coleção de transformações de cor aplicadas a uma cor. Somente leitura [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Retorna o método de definição de cor. Leitura [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Retorna o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Retorna o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Retorna o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Retorna o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Retorna o componente matiz de uma cor em representação HSL. Todas as transformações de cor são ignoradas. Leitura **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Retorna o componente luminância de uma cor em representação HSL. Todas as transformações de cor são ignoradas. Leitura **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Retorna a predefinição de cor. Leitura [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Retorna o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Retorna o componente saturação de uma cor em representação HSL. Todas as transformações de cor são ignoradas. Leitura **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Retorna a cor identificada por um esquema de cores. Leitura [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Retorna a cor identificada pela tabela de cores do sistema. Leitura [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Escrita **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Escrita [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Define a operação de transformação de cor aplicada à cor no índice especificado. Leitura/escrita [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Define o método de definição de cor. Escrita [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Escrita **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Escrita **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Escrita **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Escrita **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Define o componente matiz de uma cor em representação HSL. Todas as transformações de cor são ignoradas. Escrita **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Define o componente luminância de uma cor em representação HSL. Todas as transformações de cor são ignoradas. Escrita **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Define a predefinição de cor. Escrita [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Escrita **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Define o componente saturação de uma cor em representação HSL. Todas as transformações de cor são ignoradas. Escrita **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Define a cor identificada por um esquema de cores. Escrita [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Define a cor identificada pela tabela de cores do sistema. Escrita [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Retorna um [System::String](../../system/string/) que representa o formato de cor atual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IFillParamSource](../ifillparamsource/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)