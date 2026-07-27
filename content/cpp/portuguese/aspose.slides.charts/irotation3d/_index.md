---
title: IRotation3D
second_title: Referência da API Aspose.Slides para C++
description: Representa a rotação 3D de um gráfico.
type: docs
weight: 1171
url: /pt/aspose.slides.charts/irotation3d/
---
## IRotation3D classe

Representa a rotação 3D de um gráfico.

```cpp
class IRotation3D : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 o NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 o NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Retorna a profundidade de um gráfico 3D como uma porcentagem da largura do gráfico (entre 20 e 2000 por cento). Leitura **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Especifica a altura de um gráfico 3D como uma porcentagem da largura do gráfico (entre 5 e 500 por cento). Leitura **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Retorna o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 100). Ignorado se o valor da propriedade RightAngleAxes for true. Leitura **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. Em outras palavras, determina se os ângulos dos eixos do gráfico são independentes da rotação ou elevação do gráfico. Leitura **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Retorna o grau de rotação em torno do eixo X, ou seja, na direção Y para gráficos 3D (entre -90 e 90 graus). A propriedade corresponde ao item 21.2.2.157 rotX (Rotação X) no ECMA-376 e à opção "Y Rotation" no PowerPoint 2007+. Leitura **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Retorna o grau de rotação em torno do eixo Y, ou seja, na direção X para gráficos 3D (entre 0 e 360 graus). A propriedade corresponde ao item 21.2.2.158 rotY (Rotação Y) no ECMA-376 e à opção "X Rotation" no PowerPoint 2007+. Leitura **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite gerar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Define a profundidade de um gráfico 3D como uma porcentagem da largura do gráfico (entre 20 e 2000 por cento). Grava **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Especifica a altura de um gráfico 3D como uma porcentagem da largura do gráfico (entre 5 e 500 por cento). Grava **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 100). Ignorado se o valor da propriedade RightAngleAxes for true. Grava **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. Em outras palavras, determina se os ângulos dos eixos do gráfico são independentes da rotação ou elevação do gráfico. Grava **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Define o grau de rotação em torno do eixo X, ou seja, na direção Y para gráficos 3D (entre -90 e 90 graus). A propriedade corresponde ao item 21.2.2.157 rotX (Rotação X) no ECMA-376 e à opção "Y Rotation" no PowerPoint 2007+. Grava **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Define o grau de rotação em torno do eixo Y, ou seja, na direção X para gráficos 3D (entre 0 e 360 graus). A propriedade corresponde ao item 21.2.2.158 rotY (Rotação Y) no ECMA-376 e à opção "X Rotation" no PowerPoint 2007+. Grava **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)