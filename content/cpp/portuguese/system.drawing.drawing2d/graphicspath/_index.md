---
title: GraphicsPath
second_title: Referência da API Aspose.Slides para C++
description: "Representa um conjunto de linhas e curvas conectadas. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 66
url: /pt/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath classe

Representa um conjunto de linhas e curvas conectadas. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class GraphicsPath : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Adiciona a curva cúbica de Bézier especificada ao caminho representado pelo objeto atual. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Adiciona a curva cúbica de Bézier especificada ao caminho representado pelo objeto atual. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Adiciona a curva cúbica de Bézier especificada ao caminho representado pelo objeto atual. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Adiciona a curva cúbica de Bézier especificada ao caminho representado pelo objeto atual. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Adiciona uma sequência de curvas cúbicas de Bézier conectadas à figura atual. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Adiciona uma sequência de curvas cúbicas de Bézier conectadas à figura atual. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Adiciona a curva fechada especificada ao caminho representado pelo objeto atual. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Adiciona a curva fechada especificada ao caminho representado pelo objeto atual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Adiciona a curva especificada ao caminho representado pelo objeto atual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Adiciona a curva especificada ao caminho representado pelo objeto atual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Adiciona a curva especificada ao caminho representado pelo objeto atual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Adiciona a curva especificada ao caminho representado pelo objeto atual. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Adiciona a elipse especificada ao caminho representado pelo objeto atual. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Adiciona a elipse especificada ao caminho representado pelo objeto atual. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Adiciona a elipse especificada ao caminho representado pelo objeto atual. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Adiciona a elipse especificada ao caminho representado pelo objeto atual. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Adiciona a linha especificada ao caminho representado pelo objeto atual. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Adiciona a linha especificada ao caminho representado pelo objeto atual. |
| void [AddLine](./addline/)(int, int, int, int) | Adiciona a linha especificada ao caminho representado pelo objeto atual. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Adiciona a linha especificada ao caminho representado pelo objeto atual. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Adiciona a série de segmentos de linha conectados especificada ao caminho representado pelo objeto atual. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Adiciona a série de segmentos de linha conectados especificada ao caminho representado pelo objeto atual. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Adiciona o caminho especificado ao caminho representado pelo objeto atual. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Adiciona o contorno da forma de pizza especificado ao caminho representado pelo objeto atual. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Adiciona o contorno da forma de pizza especificado ao caminho representado pelo objeto atual. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Adiciona o contorno da forma de pizza especificado ao caminho representado pelo objeto atual. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Adiciona o polígono especificado ao caminho representado pelo objeto atual. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Adiciona o polígono especificado ao caminho representado pelo objeto atual. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Adiciona o retângulo especificado ao caminho representado pelo objeto atual. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Adiciona o retângulo especificado ao caminho representado pelo objeto atual. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Adiciona a série de retângulos especificada ao caminho representado pelo objeto atual. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Adiciona a série de retângulos especificada ao caminho representado pelo objeto atual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adiciona uma string de texto ao caminho representado pelo objeto atual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adiciona uma string de texto ao caminho representado pelo objeto atual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adiciona uma string de texto ao caminho representado pelo objeto atual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Adiciona uma string de texto ao caminho representado pelo objeto atual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Cria uma cópia do objeto atual. |
| void [CloseAllFigures](./closeallfigures/)() | Fecha todas as figuras abertas e inicia uma nova. |
| void [CloseFigure](./closefigure/)() | Fecha a figura atual e inicia uma nova. |
| void [Dispose](./dispose/)() | Libera todos os recursos do sistema operacional adquiridos pelo objeto atual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| void [Flatten](./flatten/)() | Achata cada curva no caminho convertendo-as em uma sequência de linhas conectadas. O valor de planicidade usado é 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Achata cada curva no caminho convertendo-as em uma sequência de linhas conectadas. O valor de planicidade usado é 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Achata cada curva no caminho convertendo-as em uma sequência de linhas conectadas. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Retorna o modo de preenchimento do objeto atual. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Retorna um objeto [PathData](../pathdata/) contendo os pontos que compõem um caminho representado pelo objeto atual e seus tipos. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Retorna um array que contém os pontos que compõem um caminho representado pelo objeto atual. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Retorna um array que contém valores que indicam os tipos dos pontos que compõem um caminho representado pelo objeto atual. |
| int [get_PointCount](./get_pointcount/)() const | Retorna o número de pontos no caminho representado pelo objeto atual. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Retorna um objeto [RectangleF](../../system.drawing/rectanglef/) que representa um retângulo que delimita o caminho representado pelo objeto atual quando este é transformado pela matriz especificada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Retorna um valor que é uma combinação bitwise de valores Detail::FigureType indicando quais tipos de figuras estão contidos no caminho representado pelo objeto atual. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Retorna um objeto [PointF](../../system.drawing/pointf/) que representa o último ponto no caminho. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Constrói uma nova instância da classe [GraphicsPath](./) com o modo de preenchimento especificado. |
| [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Constrói uma nova instância do objeto [GraphicsPath](./) que representa o caminho especificado. |
| [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Constrói uma nova instância do objeto [GraphicsPath](./) que representa o caminho especificado. |
| [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Indica se o ponto especificado está contido (sob) o contorno deste [GraphicsPath](./) quando desenhado com o [Pen](../../system.drawing/pen/) especificado. NÃO IMPLEMENTADO. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Determina se o ponto especificado está contido no caminho representado pelo objeto atual. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Determina se o ponto especificado está contido no caminho representado pelo objeto atual. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [Reset](./reset/)() | Esvazia o caminho removendo todos os pontos dele. |
| void [Reverse](./reverse/)() | Inverte a ordem dos pontos no array PathPoints deste [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Define o modo de preenchimento do objeto atual. |
| void [SetMarkers](./setmarkers/)() | NÃO IMPLEMENTADO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [StartFigure](./startfigure/)() | Inicia uma nova figura. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transforma o caminho representado pelo objeto atual aplicando a matriz de transformação especificada. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Substitui este caminho por um contorno ao redor do caminho original. |
| [~GraphicsPath](./~graphicspath/)() | Destrutor. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Drawing::Drawing2D](../)
* Biblioteca [Aspose.Slides](../../)