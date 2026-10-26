---
title: GraphicsPath
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un conjunto de líneas y curvas conectadas. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 66
url: /es/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath clase


Representa un conjunto de líneas y curvas conectadas. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class GraphicsPath : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Agrega una secuencia de curvas cúbicas de Bézier conectadas a la figura actual. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Agrega una secuencia de curvas cúbicas de Bézier conectadas a la figura actual. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Agrega la curva cerrada especificada a la ruta representada por el objeto actual. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Agrega la curva cerrada especificada a la ruta representada por el objeto actual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| void [AddLine](./addline/)(int, int, int, int) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Agrega la serie especificada de segmentos de línea conectados a la ruta representada por el objeto actual. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Agrega la serie especificada de segmentos de línea conectados a la ruta representada por el objeto actual. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Agrega la ruta especificada a la ruta representada por el objeto actual. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Agrega el polígono especificado a la ruta representada por el objeto actual. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Agrega el polígono especificado a la ruta representada por el objeto actual. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Agrega el rectángulo especificado a la ruta representada por el objeto actual. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Agrega el rectángulo especificado a la ruta representada por el objeto actual. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Agrega la serie especificada de rectángulos a la ruta representada por el objeto actual. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Agrega la serie especificada de rectángulos a la ruta representada por el objeto actual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Crea una copia del objeto actual. |
| void [CloseAllFigures](./closeallfigures/)() | Cierra todas las figuras abiertas y comienza una nueva. |
| void [CloseFigure](./closefigure/)() | Cierra la figura actual y comienza una nueva. |
| void [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para uso interno. |
| void [Flatten](./flatten/)() | Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. Se usa un valor de planitud de 0,25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. Se usa un valor de planitud de 0,25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Devuelve el modo de relleno del objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Devuelve un objeto [PathData](../pathdata/) que contiene los puntos que forman una ruta representada por el objeto actual y sus tipos. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Devuelve una matriz que contiene los puntos que forman una ruta representada por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Devuelve una matriz que contiene valores que indican los tipos de los puntos que forman una ruta representada por el objeto actual. |
| int [get_PointCount](./get_pointcount/)() const | Devuelve el número de puntos en la ruta representada por el objeto actual. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Devuelve un objeto [RectangleF](../../system.drawing/rectanglef/) que representa un rectángulo que delimita la ruta representada por el objeto actual cuando se transforma con la matriz especificada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Devuelve un valor que es una combinación bit a bit de los valores Detail::FigureType que indica qué tipos de figuras están contenidas dentro de la ruta representada por el objeto actual. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Devuelve un objeto [PointF](../../system.drawing/pointf/) que representa el último punto de la ruta. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Construye una nueva instancia de la clase [GraphicsPath](./) con el modo de relleno especificado. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Construye una nueva instancia del objeto [GraphicsPath](./) que representa la ruta especificada. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Construye una nueva instancia del objeto [GraphicsPath](./) que representa la ruta especificada. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Indica si el punto especificado está contenido dentro (bajo) el contorno de este [GraphicsPath](./) cuando se dibuja con el [Pen](../../system.drawing/pen/) especificado. NO IMPLEMENTADO. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Determina si el punto especificado está contenido dentro de la ruta representada por el objeto actual. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Determina si el punto especificado está contenido dentro de la ruta representada por el objeto actual. |
| void [Lock](../../system/object/lock/)() | Implementa la sentencia C# lock() bloqueando. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [Reset](./reset/)() | Vacía la ruta eliminando todos sus puntos. |
| void [Reverse](./reverse/)() | Invierte el orden de los puntos en la matriz PathPoints de este [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Establece el modo de relleno del objeto actual. |
| void [SetMarkers](./setmarkers/)() | NO IMPLEMENTADO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [StartFigure](./startfigure/)() | Inicia una nueva figura. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transforma la ruta representada por el objeto actual aplicando la matriz de transformación especificada. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la sentencia C# lock() desbloqueando. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; use punños inteligentes o ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Sustituye esta ruta por un contorno alrededor de la ruta original. |
|  [~GraphicsPath](./~graphicspath/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)