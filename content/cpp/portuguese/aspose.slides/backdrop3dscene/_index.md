---
title: Backdrop3DScene
second_title: Referência da API Aspose.Slides para C++
description: Define um plano no qual efeitos, como brilho e sombra, são aplicados em relação à forma à qual são aplicados.
type: docs
weight: 92
url: /pt/aspose.slides/backdrop3dscene/
---
## Backdrop3DScene classe

Define um plano no qual efeitos, como brilho e sombra, são aplicados em relação à forma à qual são aplicados.

```cpp
class Backdrop3DScene : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IBackdrop3DScene
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara com o objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() override | Retorna um ponto no espaço 3D. Este ponto é o ponto no espaço que ancorar o plano de fundo. Ponto 3D representado por um array de 3 valores **float** que definem as coordenadas X, Y e Z. Leitura **float**[]. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() override | Retorna um vetor normal. Para ser mais preciso, este atributo define um vetor normal à face do plano de fundo. Vetor representado por um array de 3 valores **float** que definem as coordenadas X, Y e Z. Leitura **float**[]. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retorna o objeto Parent_Immediate. Somente leitura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retorna o pai [IPresentationComponent](../ipresentationcomponent/). Somente leitura [IPresentationComponent](../ipresentationcomponent/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() override | Retorna um vetor que representa a direção para cima. Para ser mais preciso, este atributo define um vetor que representa a direção para cima em relação à face do plano de fundo. Vetor representado por um array de 3 valores **float** que definem as coordenadas X, Y e Z. Leitura **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retorna o código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Define um ponto no espaço 3D. Este ponto é o ponto no espaço que ancorar o plano de fundo. Ponto 3D representado por um array de 3 valores **float** que definem as coordenadas X, Y e Z. Escrita **float**[]. |
| void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Define um vetor normal. Para ser mais preciso, este atributo define um vetor normal à face do plano de fundo. Vetor representado por um array de 3 valores **float** que definem as coordenadas X, Y e Z. Escrita **float**[]. |
| void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Define um vetor que representa a direção para cima. Para ser mais preciso, este atributo define um vetor que representa a direção para cima em relação à face do plano de fundo. Vetor representado por um array de 3 valores **float** que definem as coordenadas X, Y e Z. Escrita **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [PVIObject](../pviobject/)
* Classe [IBackdrop3DScene](../ibackdrop3dscene/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)