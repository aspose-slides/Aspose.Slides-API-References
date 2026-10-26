---
title: Region
second_title: Referência da API Aspose.Slides para C++
description: "Representa o interior de uma forma gráfica. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 261
url: /pt/system.drawing/region/
---
## Region classe

Representa o interior de uma forma gráfica. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class Region : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Retorna uma cópia do objeto atual. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Substitui a região representada pelo objeto atual pela porção da região definida pelo retângulo especificado que não intersecta com esta região. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Substitui a região representada pelo objeto atual pela porção da região definida pelo retângulo especificado que não intersecta com esta região. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Substitui a região representada pelo objeto atual pela porção da região definida pelo caminho especificado que não intersecta com esta região. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Substitui a região representada pelo objeto atual pela porção da região especificada que não intersecta com esta região. |
| void [Dispose](./dispose/)() | Libera todos os recursos do sistema operacional adquiridos pelo objeto atual. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina se a região especificada é idêntica à região representada pelo objeto atual na superfície de desenho especificada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Substitui a região representada pelo objeto atual pelo resultado da exclusão da região definida pelo retângulo especificado. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Substitui a região representada pelo objeto atual pelo resultado da exclusão da região definida pelo retângulo especificado. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Substitui a região representada pelo objeto atual pelo resultado da exclusão da região definida pelo caminho especificado. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Substitui a região representada pelo objeto atual pelo resultado da exclusão da região especificada. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Obtém uma estrutura [RectangleF](../rectanglef/) que representa um retângulo que delimita este [Region](./) na superfície de desenho de um objeto [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite o hash de objetos personalizados. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Retorna um objeto RegionData contendo dados que definem a região representada pelo objeto atual. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Retorna um array de estruturas [RectangleF](../rectanglef/) que aproximam este [Region](./) após a aplicação da transformação matricial especificada. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Substitui a região representada pelo objeto atual pelo resultado da interseção desta região com a região definida pelo retângulo especificado. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Substitui a região representada pelo objeto atual pelo resultado da interseção desta região com a região definida pelo retângulo especificado. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Substitui a região representada pelo objeto atual pelo resultado da interseção desta região com a região definida pelo caminho especificado. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Substitui a região representada pelo objeto atual pelo resultado da interseção desta região com a região especificada. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se a região representada pelo objeto atual tem interior vazio na superfície de desenho especificada. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se a região representada pelo objeto atual tem interior infinito na superfície de desenho especificada. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Determina se o ponto especificado está contido dentro da região representada pelo objeto atual. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Determina se o ponto especificado está contido dentro da região representada pelo objeto atual. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Determina se alguma parte do retângulo especificado está contida dentro da região representada pelo objeto atual. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Determina se alguma parte do retângulo especificado está contida dentro da região representada pelo objeto atual. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se o ponto especificado está contido dentro da região representada pelo objeto atual usando os gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se o ponto especificado está contido dentro da região representada pelo objeto atual usando os gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina se alguma parte do retângulo especificado está contida dentro da região representada pelo objeto atual usando os gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina se alguma parte do retângulo especificado está contida dentro da região representada pelo objeto atual usando os gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Determina se o ponto especificado está contido dentro da região representada pelo objeto atual. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se o ponto especificado está contido dentro da região representada pelo objeto atual usando os gráficos especificados. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Inicializa o objeto atual com interior vazio. |
| void [MakeInfinite](./makeinfinite/)() | Inicializa este objeto região com interior infinito. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
|  [Region](./region/)() | Constrói uma nova instância da classe [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Constrói uma nova instância da classe [Region](./) que representa uma região definida pelo retângulo especificado. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Constrói uma nova instância da classe [Region](./) que representa uma região definida pelo retângulo especificado. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Constrói uma nova instância da classe [Region](./) que representa uma região definida pelo caminho especificado. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Constrói uma nova instância da classe [Region](./) que representa uma região definida pelo objeto RegionData especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transforma esta região pela matriz especificada. |
| void [Transform](./transform/)(const SkMatrix\&) | Transforma esta região pela matriz especificada. |
| void [Translate](./translate/)(int, int) | Move as coordenadas da região pela quantidade especificada. |
| void [Translate](./translate/)(**float**, **float**) | Move as coordenadas da região pela quantidade especificada. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Substitui a região representada pelo objeto atual pelo resultado da operação de união desta região com uma região definida pelo retângulo especificado. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Substitui a região representada pelo objeto atual pelo resultado da operação de união desta região com uma região definida pelo retângulo especificado. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Substitui a região representada pelo objeto atual pelo resultado da operação de união desta região com uma região definida pelo caminho especificado. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Substitui a região representada pelo objeto atual pelo resultado da operação de união desta região com a região especificada. |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Substitui a região representada pelo objeto atual pelas porções desta região e da região definida pelo retângulo especificado que não intersectam. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Substitui a região representada pelo objeto atual pelas porções desta região e da região definida pelo retângulo especificado que não intersectam. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Substitui a região representada pelo objeto atual pelas porções desta região e da região definida pelo caminho especificado que não intersectam. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Substitui a região representada pelo objeto atual pelas porções desta região e da região especificada que não intersectam. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
| virtual  [~Region](./~region/)() | Destrutor. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)