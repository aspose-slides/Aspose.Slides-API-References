---
title: AdjustableArrowCap
second_title: Referência da API Aspose.Slides para C++
description: "Representa um cap de linha em forma de seta ajustável. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 1
url: /pt/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap classe

Representa um cap de linha em forma de seta ajustável. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | Constrói uma nova instância de [AdjustableArrowCap](./) com a largura e altura especificadas. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | Retorna uma cópia do objeto atual. |
|  [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | Constrói uma nova instância da classe [CustomLineCap](../customlinecap/) que representa um cap de linha definido pelo usuário com as propriedades especificadas. |
| void [Dispose](../customlinecap/dispose/)() | Libera todos os recursos do sistema operacional adquiridos pelo objeto atual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | Retorna o cap de linha base a partir do qual este cap personalizado é criado. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | Retorna a distância entre a linha e o cap. |
| **bool** [get_Filled](./get_filled/)() const | Retorna um valor que indica se a seta representada pelo objeto atual está preenchida. |
| **float** [get_Height](./get_height/)() const | Retorna a altura da seta representada pelo objeto atual. |
| **float** [get_MiddleInset](./get_middleinset/)() const | Define a distância entre a linha e o cap representado pelo objeto atual. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | Retorna o valor LineJoin que determina como as linhas deste cap personalizado são unidas. |
| **float** [get_Width](./get_width/)() const | Retorna a largura da seta representada pelo objeto atual. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | Retorna a escala deste cap personalizado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hashing de objetos personalizados. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | Obtém os caps de linha inicial e final do cap personalizado representado pelo objeto atual. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | Define o valor do cap de linha base para este cap personalizado. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | Define a distância entre a linha e o cap. |
| void [set_Filled](./set_filled/)(**bool**) | Define um valor que especifica se a seta representada pelo objeto atual está preenchida. |
| void [set_Height](./set_height/)(**float**) | Define a altura da seta representada pelo objeto atual. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | Define a distância entre a linha e o cap representado pelo objeto atual. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | Define o valor LineJoin que determina como as linhas deste cap personalizado são unidas. |
| void [set_Width](./set_width/)(**float**) | Define a largura da seta representada pelo objeto atual. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | Define o valor de escala deste cap personalizado. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | Define os caps de linha inicial e final do cap personalizado representado pelo objeto atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [CustomLineCap](../customlinecap/)
* Espaço de nomes [System::Drawing::Drawing2D](../)
* Biblioteca [Aspose.Slides](../../)