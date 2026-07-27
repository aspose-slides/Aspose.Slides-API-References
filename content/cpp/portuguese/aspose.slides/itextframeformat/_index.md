---
title: ITextFrameFormat
second_title: Referência da API Aspose.Slides para C++
description: Contém as propriedades de formatação do TextFrame.
type: docs
weight: 4083
url: /pt/aspose.slides/itextframeformat/
---
## ITextFrameFormat classe

Contém as propriedades de formatação do [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Retorna o texto de âncora vertical em um [TextFrame](../textframe/). Leia [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Retorna o modo de ajuste automático do texto. Leia [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Se [NullableBool::True](../nullablebool/) então o texto deve ser centralizado horizontalmente na caixa. Leia [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Retorna o número de colunas na área de texto. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Valor 0 significa valor indefinido. Leia **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Retorna o espaçamento entre colunas de texto na área de texto (em pontos). Isso só se aplica quando há mais de 1 coluna presente. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Leia **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Retorna ou define a manutenção do texto fora da cena 3D completamente. Leia **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Retorna a margem inferior (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Retorna a margem esquerda (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Retorna a margem direita (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Retorna a margem superior (pontos) em um [TextFrame](../textframe/). Leia **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Especifica a rotação personalizada aplicada ao texto dentro da caixa delimitadora. Se não for especificada, usa-se a rotação da forma associada. Se for especificada, é aplicada independentemente da forma. Ou seja, a forma pode ter rotação adicional à rotação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leia **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Retorna o estilo do texto. Somente leitura [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Determina a orientação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Leia [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Retorna o objeto [ThreeDFormat](../threedformat/) que representa as propriedades de efeito 3D para um texto. Somente leitura [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Obtém a forma de contorno do texto. Leia [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** se o texto estiver contornado nas margens de [TextFrame](../textframe/). Leia [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtém os dados de formatação eficaz do quadro de texto com a herança aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Define o texto de âncora vertical em um [TextFrame](../textframe/). Escreva [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Define o modo de ajuste automático do texto. Escreva [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Se [NullableBool::True](../nullablebool/) então o texto deve ser centralizado horizontalmente na caixa. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Define o número de colunas na área de texto. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Valor 0 significa valor indefinido. Escreva **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Define o espaçamento entre colunas de texto na área de texto (em pontos). Isso só se aplica quando há mais de 1 coluna presente. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Escreva **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Retorna ou define a manutenção do texto fora da cena 3D completamente. Escreva **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Define a margem inferior (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Define a margem esquerda (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Define a margem direita (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Define a margem superior (pontos) em um [TextFrame](../textframe/). Escreva **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Especifica a rotação personalizada aplicada ao texto dentro da caixa delimitadora. Se não for especificada, usa-se a rotação da forma associada. Se for especificada, é aplicada independentemente da forma. Ou seja, a forma pode ter rotação adicional à rotação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Escreva **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Determina a orientação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Escreva [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Define a forma de contorno do texto. Escreva [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** se o texto estiver contornado nas margens de [TextFrame](../textframe/). Escreva [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Habilita conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)