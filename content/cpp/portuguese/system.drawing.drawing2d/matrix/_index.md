---
title: Matrix
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma matriz 3x3 que define operações de transformação. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 118
url: /pt/system.drawing.drawing2d/matrix/
---
## Classe Matrix

Representa uma matriz 3x3 que define operações de transformação. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class Matrix : public System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Cria uma cópia do objeto atual. |
| void [Dispose](./dispose/)() | Libera todos os recursos do sistema operacional adquiridos pelo objeto atual. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Testa se o objeto especificado é um [Matrix](./) e é idêntico a este objeto. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Retorna um array contendo os elementos da matriz na seguinte ordem: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Determina se a matriz representada pelo objeto atual é uma matriz identidade. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Determina se a matriz representada pelo objeto atual é invertível. |
| **float** [get_OffsetX](./get_offsetx/)() const | Retorna o valor de translação X da matriz representada pelo objeto atual. |
| **float** [get_OffsetY](./get_offsety/)() const | Retorna o valor de translação Y da matriz representada pelo objeto atual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Inverte a matriz representada pelo objeto atual. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
|  [Matrix](./matrix/)() | Constrói uma nova instância da classe [Matrix](./) que representa uma matriz identidade. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Constrói uma nova instância da classe [Matrix](./) e a inicializa com os valores especificados. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Constrói uma nova instância da classe [Matrix](./) para a transformação geométrica definida pelo retângulo especificado e array de pontos. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Constrói uma nova instância da classe [Matrix](./) para a transformação geométrica definida pelo retângulo especificado e array de pontos. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Multiplica a matriz representada pelo objeto atual pela matriz especificada. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Multiplica a matriz representada pelo objeto atual pela matriz especificada. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [Reset](./reset/)() | Redefine a matriz representada pelo objeto atual para que se torne uma matriz identidade. |
| void [Rotate](./rotate/)(**float**) | Rotaciona a matriz representada pelo objeto atual no sentido horário pelo ângulo especificado. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Rotaciona a matriz representada pelo objeto atual no sentido horário ao redor da origem pelo ângulo especificado. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Rotaciona a matriz representada pelo objeto atual no sentido horário ao redor do ponto especificado pelo ângulo especificado. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Rotaciona a matriz representada pelo objeto atual no sentido horário ao redor do ponto especificado pelo ângulo especificado. |
| void [Scale](./scale/)(**float**, **float**) | Aplica o vetor de escala especificado à matriz representada pelo objeto atual. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplica o vetor de escala especificado à matriz representada pelo objeto atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Aplica o vetor de cisalhamento especificado à matriz representada pelo objeto atual. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplica o vetor de cisalhamento especificado à matriz representada pelo objeto atual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aplica a transformação geométrica definida pela matriz representada pelo objeto atual aos pontos especificados. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Aplica a transformação geométrica definida pela matriz representada pelo objeto atual aos pontos especificados. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica a transformação geométrica definida pela matriz representada pelo objeto atual aos pontos especificados. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica a transformação geométrica definida pela matriz representada pelo objeto atual aos pontos especificados. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aplica somente os componentes de escala e rotação da matriz representada pelo objeto atual aos pontos especificados. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Aplica somente os componentes de escala e rotação da matriz representada pelo objeto atual aos pontos especificados. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica somente os componentes de escala e rotação da matriz representada pelo objeto atual aos pontos especificados. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica somente os componentes de escala e rotação da matriz representada pelo objeto atual aos pontos especificados. |
| void [Translate](./translate/)(**float**, **float**) | Aplica o vetor de translação especificado à matriz representada pelo objeto atual. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplica o vetor de translação especificado à matriz representada pelo objeto atual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construtor C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Multiplica cada vetor em um array pela matriz representada pelo objeto atual. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Multiplica cada vetor em um array pela matriz representada pelo objeto atual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destrutor. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Drawing::Drawing2D](../)
* Biblioteca [Aspose.Slides](../../)