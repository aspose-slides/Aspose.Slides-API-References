---
title: PropertyEffect
second_title: Referência de API Aspose.Slides para C++
description: Representa o comportamento do efeito de propriedade.
type: docs
weight: 521
url: /pt/aspose.slides.animation/propertyeffect/
---
## PropertyEffect classe


Representa o comportamento do efeito de propriedade.

```cpp
class PropertyEffect : public Aspose::Slides::Animation::Behavior,
                       public Aspose::Slides::Animation::IPropertyEffect
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | Representa se os comportamentos de animação são acumulados. Leia [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | Representa se o comportamento de animação atual é combinado com outras animações em execução. Leia [BehaviorAdditiveType](../behavioradditivetype/). |
| [System::String](../../system/string/) [get_By](./get_by/)() override | Especifica um valor de deslocamento relativo para a animação em relação à sua posição antes do início da animação. Leia [System::String](../../system/string/). |
| [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() override | Especifica o modo de interpolação para a animação. Leia [PropertyCalcModeType](../propertycalcmodetype/). |
| [System::String](../../system/string/) [get_From](./get_from/)() override | Especifica o valor inicial da animação. Leia [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) override | Retorna um ponto da animação no índice especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() override | Especifica os pontos da animação. Leia [IPointCollection](../ipointcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | Representa as propriedades do comportamento. Somente leitura [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | Representa as propriedades de temporização para o comportamento do efeito. Leia [ITiming](../itiming/). |
| [System::String](../../system/string/) [get_To](./get_to/)() override | Especifica o valor final da animação. Leia [System::String](../../system/string/). |
| [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() override | Especifica o tipo de um valor de propriedade. Leia [PropertyValueType](../propertyvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
|  [PropertyEffect](./propertyeffect/)() |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | Representa se os comportamentos de animação são acumulados. Grava [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | Representa se o comportamento de animação atual é combinado com outras animações em execução. Grava [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_By](./set_by/)([System::String](../../system/string/)) override | Especifica um valor de deslocamento relativo para a animação em relação à sua posição antes do início da animação. Grava [System::String](../../system/string/). |
| void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) override | Especifica o modo de interpolação para a animação. Grava [PropertyCalcModeType](../propertycalcmodetype/). |
| void [set_From](./set_from/)([System::String](../../system/string/)) override | Especifica o valor inicial da animação. Grava [System::String](../../system/string/). |
| void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) override | Especifica os pontos da animação. Grava [IPointCollection](../ipointcollection/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Representa as propriedades de temporização para o comportamento do efeito. Grava [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::String](../../system/string/)) override | Especifica o valor final da animação. Grava [System::String](../../system/string/). |
| void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) override | Especifica o tipo de um valor de propriedade. Grava [PropertyValueType](../propertyvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas. |

## Ver também

* Classe [Behavior](../behavior/)
* Classe [IPropertyEffect](../ipropertyeffect/)
* Espaço de nomes [Aspose::Slides::Animation](../)
* Biblioteca [Aspose.Slides](../../)