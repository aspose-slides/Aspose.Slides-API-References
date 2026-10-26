---
title: IChartTextBlockFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa as propriedades de formatação para elementos de texto de gráfico.
type: docs
weight: 885
url: /pt/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat classe


Representa as propriedades de formatação para elementos de texto de gráfico.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Retorna o texto de âncora vertical em um [TextFrame](../../aspose.slides/textframe/). Leia [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Retorna o modo de ajuste automático do texto. Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leia [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | Se [NullableBool::True](../../aspose.slides/nullablebool/) o texto deve ser centralizado horizontalmente na caixa. Leia [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Retorna a margem inferior (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leia **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Retorna a margem esquerda (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leia **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Retorna a margem direita (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leia **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Retorna a margem superior (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leia **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Especifica a rotação personalizada aplicada ao texto dentro da caixa delimitadora. Se não for especificada, a rotação da forma associada é usada. Se for especificada, então é aplicada independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação do próprio texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leia **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Determina a orientação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo customizado na propriedade RotationAngle. Leia [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** se o texto for ajustado nas margens de [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2007/2013). Leia [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita o hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, realmente, apenas inicializa um novo objeto e habilita a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, realmente, apenas inicializa um novo objeto e habilita a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Define o texto de âncora vertical em um [TextFrame](../../aspose.slides/textframe/). Escreva [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Define o modo de ajuste automático do texto. Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Escreva [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | Se [NullableBool::True](../../aspose.slides/nullablebool/) o texto deve ser centralizado horizontalmente na caixa. Escreva [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Define a margem inferior (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Escreva **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Define a margem esquerda (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Escreva **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Define a margem direita (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Escreva **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Define a margem superior (pontos) em um [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Escreva **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Especifica a rotação personalizada aplicada ao texto dentro da caixa delimitadora. Se não for especificada, a rotação da forma associada é usada. Se for especificada, então é aplicada independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação do próprio texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Escreva **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Determina a orientação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo customizado na propriedade RotationAngle. Escreva [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** se o texto for ajustado nas margens de [TextFrame](../../aspose.slides/textframe/). Alterar esta propriedade pode produzir certa influência apenas para estas partes do gráfico: [DataLabel](../datalabel/) e [DataLabelFormat](../datalabelformat/) (suporte total no PowerPoint 2007/2013). Escreva [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (ao invés de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Ver também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)