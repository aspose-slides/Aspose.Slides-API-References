---
title: TextFrameFormat
second_title: Aspose.Slides para C++ Referência da API
description: Contém as propriedades formatTextFrameFormatting do TextFrame.
type: docs
weight: 5461
url: /pt/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contém as propriedades formatTextFrameFormatting de [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara com o objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Retorna o texto de âncora vertical em um [TextFrame](../textframe/). Leia [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Retorna o modo de ajuste automático do texto. Leia [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Se [NullableBool::True](../nullablebool/) então o texto deve ser centralizado horizontalmente na caixa. Leia [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Retorna o número de colunas na área de texto. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Valor 0 significa valor indefinido. Leia **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Retorna o espaço entre colunas de texto na área de texto (em pontos). Isto deve ser aplicado apenas quando houver mais de 1 coluna presente. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Leia **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Obtém a manutenção do texto plano mesmo se um efeito de Rotação 3-D foi aplicado. Leia **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Retorna a margem inferior (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Retorna a margem esquerda (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Retorna a margem direita (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Retorna a margem superior (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retorna o objeto Parent_Immediate. Somente leitura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retorna o [IPresentationComponent](../ipresentationcomponent/) pai. Somente leitura [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então isto é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação aplicada ao texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leia **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Determina a orientação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Leia [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Retorna o objeto [ThreeDFormat](../threedformat/) que representa as propriedades de efeito 3D para um texto. Somente leitura [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Obtém a forma de quebra de texto. Leia [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** se o texto for quebrado nas margens de [TextFrame](../textframe/). Leia [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtém os dados de formatação efetiva da moldura de texto com a herança aplicada. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retorna o código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Define o texto de âncora vertical em um [TextFrame](../textframe/). Escreva [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Define o modo de ajuste automático do texto. Escreva [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Se [NullableBool::True](../nullablebool/) então o texto deve ser centralizado horizontalmente na caixa. Escreva [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Define o número de colunas na área de texto. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Valor 0 significa valor indefinido. Escreva **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Define o espaço entre colunas de texto na área de texto (em pontos). Isto deve ser aplicado somente quando houver mais de 1 coluna presente. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Escreva **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Define a manutenção do texto plano mesmo se um efeito de Rotação 3-D foi aplicado. Escreva **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Define a margem inferior (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Define a margem esquerda (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Define a margem direita (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Define a margem superior (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então isto é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação aplicada ao texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Escreva **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Determina a orientação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Escreva [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Define a forma de quebra de texto. Escreva [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** se o texto for quebrado nas margens de [TextFrame](../textframe/). Escreva [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [TextFrameFormat](./textframeformat/)() | Inicializa uma nova instância da classe [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [PVIObject](../pviobject/)
* Classe [ITextFrameFormat](../itextframeformat/)
* Classe [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)