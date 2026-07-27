---
title: GeometryPath
second_title: Referência da API Aspose.Slides para C++
description: Representa o caminho de geometria de GeometryShape
type: docs
weight: 1067
url: /pt/aspose.slides/geometrypath/
---
## classe GeometryPath

Representa o caminho de geometria de [GeometryShape](../geometryshape/)

```cpp
class GeometryPath : public Aspose::Slides::IGeometryPath
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [ArcTo](./arcto/)(**float**, **float**, **float**, **float**) override | Appends the specified arc to the path. |
| void [CloseFigure](./closefigure/)() override | Closes the current figure of this path |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Adds cubic Bezier curve at the end the path |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**) override | Adds cubic Bezier curve at the end the path |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Adds cubic Bezier curve to the specified place of the path |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**, **uint32_t**) override | Adds cubic Bezier curve to the specified place of the path |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
|  [GeometryPath](./geometrypath/)() | Cria instância de [GeometryPath](./) |
| [PathFillModeType](../pathfillmodetype/) [get_FillMode](./get_fillmode/)() override | Define o modo de preenchimento |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPathSegment](../ipathsegment/)\>\> [get_PathData](./get_pathdata/)() override | Retorna o caminho de geometria de [GeometryShape](../geometryshape/) como uma matriz de segmentos de caminho. |
| **bool** [get_Stroke](./get_stroke/)() override | Define a aparência do traço |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de contagem de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analog of C# 'is' operator. |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Adds line to the end of the path |
| void [LineTo](./lineto/)(**float**, **float**) override | Adds line to the end of the path |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Adds line to the specified place of the path |
| void [LineTo](./lineto/)(**float**, **float**, **uint32_t**) override | Adds line to the specified place of the path |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| void [MoveTo](./moveto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Sets next point position. |
| void [MoveTo](./moveto/)(**float**, **float**) override | Define a posição do próximo ponto. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a copia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a copia de subclasses. |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Adds quadratic Bezier curve at the end the path |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**) override | Adds quadratic Bezier curve at the end the path |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Adds quadratic Bezier curve to the specified place of the path |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**, **uint32_t**) override | Adds quadratic Bezier curve to the specified place of the path |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Remove segmento no índice especificado do caminho de geometria. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada pelo valor especificado. |
| void [set_FillMode](./set_fillmode/)([PathFillModeType](../pathfillmodetype/)) override | Define o modo de preenchimento |
| void [set_Stroke](./set_stroke/)(**bool**) override | Define a aparência do traço |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa a contagem de referência compartilhada. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna a contagem de referência compartilhada. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa a contagem de referência fraca. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa a contagem de referência fraca. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IGeometryPath](../igeometrypath/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)