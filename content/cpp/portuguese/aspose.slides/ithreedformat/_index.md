---
title: IThreeDFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa propriedades 3-D.
type: docs
weight: 4161
url: /pt/aspose.slides/ithreedformat/
---
## IThreeDFormat classe


Representa propriedades 3-D.

```cpp
class IThreeDFormat : public Aspose::Slides::IThreeDParamSource
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() | Retorna o tipo de um chanfro 3D inferior. Somente leitura [IShapeBevel](../ishapebevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() | Retorna o tipo de um chanfro 3D superior. Somente leitura [IShapeBevel](../ishapebevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() | Retorna as configurações de uma câmera. Somente leitura [ICamera](../icamera/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() | Retorna a cor de um contorno. Somente leitura [IColorFormat](../icolorformat/). |
| virtual **double** [get_ContourWidth](./get_contourwidth/)() | Retorna a largura de um contorno 3D. Leitura **double**. |
| virtual **double** [get_Depth](./get_depth/)() | Retorna a profundidade de uma forma 3D. Leitura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() | Retorna a cor de uma extrusão. Somente leitura [IColorFormat](../icolorformat/). |
| virtual **double** [get_ExtrusionHeight](./get_extrusionheight/)() | Retorna a altura de um efeito de extrusão. Leitura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() | Retorna o tipo de uma luz. Somente leitura [ILightRig](../ilightrig/). |
| virtual [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() | Retorna o tipo de um material. Leitura [MaterialPresetType](../materialpresettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtém os dados de formatação 3-D efetivos com a herança aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite construir cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite construir cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_ContourWidth](./set_contourwidth/)(**double**) | Define a largura de um contorno 3D. Escrita **double**. |
| virtual void [set_Depth](./set_depth/)(**double**) | Define a profundidade de uma forma 3D. Escrita **double**. |
| virtual void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) | Define a altura de um efeito de extrusão. Escrita **double**. |
| virtual void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) | Define o tipo de um material. Escrita [MaterialPresetType](../materialpresettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n'th argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [IThreeDParamSource](../ithreedparamsource/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)