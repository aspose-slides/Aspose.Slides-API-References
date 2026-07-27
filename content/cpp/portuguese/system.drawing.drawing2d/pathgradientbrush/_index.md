---
title: PathGradientBrush
second_title: Referência da API Aspose.Slides para C++
description: "Representa um pincel que preenche o interior de um objeto GraphicsPath com um gradiente. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro ao passá-lo como argumento para funções."
type: docs
weight: 144
url: /pt/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush classe

Representa um pincel que preenche o interior de um objeto [GraphicsPath](../graphicspath/) com um gradiente. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Métodos

| Método | Descrição |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Cria uma cópia do objeto atual. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Não faz nada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | NÃO IMPLEMENTADO. |
| [Color](../../system.drawing/color/) [get_CenterColor](./get_centercolor/)() const | Retorna uma cor que está no centro do caminho preenchido pelo objeto atual. |
| [PointF](../../system.drawing/pointf/) [get_CenterPoint](./get_centerpoint/)() const | Obtém o ponto central do gradiente. |
| [PointF](../../system.drawing/pointf/) [get_FocusScales](./get_focusscales/)() const | Obtém o ponto focal para o declínio do gradiente. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | Retorna um valor que define um gradiente linear multicolorido. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | NÃO IMPLEMENTADO. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_SurroundColors](./get_surroundcolors/)() const | Retorna cores que correspondem aos pontos no caminho que este [PathGradientBrush](./) preenche. |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | Retorna uma cópia de um objeto [Matrix](../matrix/) que especifica as transformações geométricas para o pincel representado pelo objeto atual. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | Retorna o modo de wrap. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite o hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | Multiplica a matriz de transformação do objeto atual pela matriz especificada. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, [WrapMode](../wrapmode/)) | Constrói uma nova instância da classe [PathGradientBrush](./). |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, [WrapMode](../wrapmode/)) | Constrói uma nova instância da classe [PathGradientBrush](./). |
|  [PathGradientBrush](./pathgradientbrush/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&) | Constrói uma nova instância da classe [PathGradientBrush](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [ResetTransform](./resettransform/)() | Redefine a matriz de transformação do objeto atual para que se torne uma matriz identidade. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Rotaciona a transformação geométrica local pelo ângulo especificado na ordem especificada. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Escala a transformação geométrica local pelos fatores especificados na ordem especificada. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | Define uma mescla que especifica fatores e posições das cores base para este pincel. |
| void [set_CenterColor](./set_centercolor/)([Color](../../system.drawing/color/)) | Define uma cor que está no centro do caminho preenchido pelo objeto atual. |
| void [set_CenterPoint](./set_centerpoint/)(const [PointF](../../system.drawing/pointf/)\&) | Define o ponto central do gradiente. |
| void [set_FocusScales](./set_focusscales/)(const [PointF](../../system.drawing/pointf/)\&) | Define o ponto focal para o declínio do gradiente. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | Define um valor que define um gradiente linear multicolorido. |
| void [set_SurroundColors](./set_surroundcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | Define cores que correspondem aos pontos no caminho que este [PathGradientBrush](./) preenche. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | Define um objeto [Matrix](../matrix/) que especifica as transformações geométricas para o pincel representado pelo objeto atual. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | Define o modo de wrap. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | NÃO IMPLEMENTADO. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | NÃO IMPLEMENTADO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Translada a transformação geométrica local pelas dimensões especificadas na ordem especificada. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o constructo C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Biblioteca [Aspose.Slides](../../)