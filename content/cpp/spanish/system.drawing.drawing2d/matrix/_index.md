---
title: Matrix
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa una matriz 3x3 que define operaciones de transformación. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 118
url: /es/system.drawing.drawing2d/matrix/
---
## Clase Matrix


Representa una matriz 3x3 que define operaciones de transformación. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Matrix : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Crea una copia del objeto actual. |
| void [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Comprueba si el objeto especificado es un [Matrix](./) y es idéntico a este objeto. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Devuelve una matriz que contiene los elementos de la matriz en el siguiente orden: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Determina si la matriz representada por el objeto actual es una matriz identidad. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Determina si la matriz representada por el objeto actual es invertible. |
| **float** [get_OffsetX](./get_offsetx/)() const | Devuelve el valor de traslación X de la matriz representada por el objeto actual. |
| **float** [get_OffsetY](./get_offsety/)() const | Devuelve el valor de traslación Y de la matriz representada por el objeto actual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Invierte la matriz representada por el objeto actual. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
|  [Matrix](./matrix/)() | Construye una nueva instancia de la clase [Matrix](./) que representa una matriz identidad. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Construye una nueva instancia de la clase [Matrix](./) y la inicializa con los valores especificados. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Construye una nueva instancia de la clase [Matrix](./) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Construye una nueva instancia de la clase [Matrix](./) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Multiplica la matriz representada por el objeto actual por la matriz especificada. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Multiplica la matriz representada por el objeto actual por la matriz especificada. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia al construir subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia al construir subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [Reset](./reset/)() | Restablece la matriz representada por el objeto actual para que se convierta en una matriz identidad. |
| void [Rotate](./rotate/)(**float**) | Rota la matriz representada por el objeto actual en sentido horario por el ángulo especificado. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Rota la matriz representada por el objeto actual en sentido horario alrededor del origen por el ángulo especificado. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Rota la matriz representada por el objeto actual en sentido horario alrededor del punto especificado por el ángulo especificado. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Rota la matriz representada por el objeto actual en sentido horario alrededor del punto especificado por el ángulo especificado. |
| void [Scale](./scale/)(**float**, **float**) | Aplica el vector de escala especificado a la matriz representada por el objeto actual. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplica el vector de escala especificado a la matriz representada por el objeto actual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Aplica el vector de cizallamiento especificado a la matriz representada por el objeto actual. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplica el vector de cizallamiento especificado a la matriz representada por el objeto actual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| void [Translate](./translate/)(**float**, **float**) | Aplica el vector de traslación especificado a la matriz representada por el objeto actual. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplica el vector de traslación especificado a la matriz representada por el objeto actual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Multiplica cada vector en una matriz por la matriz representada por el objeto actual. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Multiplica cada vector en una matriz por la matriz representada por el objeto actual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Drawing::Drawing2D](../)
* Biblioteca [Aspose.Slides](../../)