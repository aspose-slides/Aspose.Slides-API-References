---
title: ColorFormat
second_title: Aspose.Slides para C++ Referência da API
description: Representa uma cor usada em uma apresentação.
type: docs
weight: 339
url: /pt/aspose.slides/colorformat/
---
## ColorFormat classe

Representa uma cor usada em uma apresentação.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Copia o formato de cor de \"color\". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Verifica a igualdade com o objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais apesar de, segundo IEC 60559:1989, NaN não ser igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **uint8_t** [get_B](./get_b/)() override | Retorna o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Leitura [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Retorna a operação de transformação de cor aplicada à cor no índice especificado. Leitura/escrita [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Retorna a coleção de transformações de cor aplicadas a uma cor. Somente leitura [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Retorna o método de definição de cor. Leitura [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Retorna o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Retorna o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Retorna o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura **float**. |
| **uint8_t** [get_G](./get_g/)() override | Retorna o componente verde de uma cor. Todas as transformações de cor são ignoradas. |
| **float** [get_Hue](./get_hue/)() override | Retorna o componente tonal de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Retorna o componente de luminância de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retorna o objeto Parent_Immediate. Somente leitura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retorna o pai [IPresentationComponent](../ipresentationcomponent/). Somente leitura [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Retorna o preset de cor. Leitura [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Retorna o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Retorna o componente de saturação de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Retorna a cor identificada por um esquema de cores. Leitura [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Retorna a cor identificada pela tabela de cores do sistema. Leitura [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Retorna o código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [set_B](./set_b/)(**uint8_t**) override | Define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Escreve **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Escreve [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Define a operação de transformação de cor aplicada à cor no índice especificado. Leitura/escrita [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Define o método de definição de cor. Escreve [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Escreve **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Escreve **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Escreve **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Define o componente verde de uma cor. Todas as transformações de cor são ignoradas. |
| void [set_Hue](./set_hue/)(**float**) override | Define o componente tonal de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Escreve **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Define o componente de luminância de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Escreve **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Define o preset de cor. Escreve [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Escreve **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Define o componente de saturação de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Escreve **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Define a cor identificada por um esquema de cores. Escreve [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Define a cor identificada pela tabela de cores do sistema. Escreve [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Retorna um [System::String](../../system/string/) que representa o formato de cor atual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Ver Também

* Classe [PVIObject](../pviobject/)
* Classe [IColorFormat](../icolorformat/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)