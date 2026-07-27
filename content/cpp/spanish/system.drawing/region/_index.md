---
title: Region
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa el interior de una forma gráfica. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 261
url: /es/system.drawing/region/
---
## Region clase

Representa el interior de una forma gráfica. Los objetos de esta clase sólo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class Region : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Devuelve una copia del objeto actual. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Reemplaza la región representada por el objeto actual con la porción de la región definida por el rectángulo especificado que no intersecta con esta región. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Reemplaza la región representada por el objeto actual con la porción de la región definida por el rectángulo especificado que no intersecta con esta región. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Reemplaza la región representada por el objeto actual con la porción de la región definida por la ruta especificada que no intersecta con esta región. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Reemplaza la región representada por el objeto actual con la porción de la región especificada que no intersecta con esta región. |
| void [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina si la región especificada es idéntica a la región representada por el objeto actual en la superficie de dibujo especificada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Reemplaza la región representada por el objeto actual con el resultado de excluir de ella la región definida por el rectángulo especificado. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Reemplaza la región representada por el objeto actual con el resultado de excluir de ella la región definida por el rectángulo especificado. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Reemplaza la región representada por el objeto actual con el resultado de excluir de ella la región definida por la ruta especificada. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Reemplaza la región representada por el objeto actual con el resultado de excluir de ella la región especificada. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Obtiene una estructura [RectangleF](../rectanglef/) que representa un rectángulo que delimita este [Region](./) en la superficie de dibujo de un objeto [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Devuelve un objeto RegionData que contiene datos que definen la región representada por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Devuelve una matriz de estructuras [RectangleF](../rectanglef/) que aproximan este [Region](./) después de aplicar la transformación matricial especificada. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y una región definida por el rectángulo especificado. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y una región definida por el rectángulo especificado. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y una región definida por la ruta especificada. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y la región especificada. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina si la región representada por el objeto actual tiene interior vacío en la superficie de dibujo especificada. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina si la región representada por el objeto actual tiene interior infinito en la superficie de dibujo especificada. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual usando los gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual usando los gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual usando los gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual usando los gráficos especificados. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual usando los gráficos especificados. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Inicializa el objeto actual con interior vacío. |
| void [MakeInfinite](./makeinfinite/)() | Inicializa este objeto región con interior infinito. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
|  [Region](./region/)() | Construye una nueva instancia de la clase [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por el rectángulo especificado. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por el rectángulo especificado. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por la ruta especificada. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por el objeto RegionData especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transforma esta región mediante la matriz especificada. |
| void [Transform](./transform/)(const SkMatrix\&) | Transforma esta región mediante la matriz especificada. |
| void [Translate](./translate/)(int, int) | Mueve las coordenadas de la región en la cantidad especificada. |
| void [Translate](./translate/)(**float**, **float**) | Mueve las coordenadas de la región en la cantidad especificada. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Reemplaza la región representada por el objeto actual con el resultado de la operación de unión de esta región y una región definida por el rectángulo especificado. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y una región definida por el rectángulo especificado. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y una región definida por la ruta especificada. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y la región especificada. |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por el rectángulo especificado que no intersectan. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por el rectángulo especificado que no intersectan. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por la ruta especificada que no intersectan. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región especificada que no intersectan. |
| virtual  [~Object](../../system/object/~object/)() | Destroye el objeto. Libera todas las estructuras de datos internas. |
| virtual  [~Region](./~region/)() | Destructor. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)