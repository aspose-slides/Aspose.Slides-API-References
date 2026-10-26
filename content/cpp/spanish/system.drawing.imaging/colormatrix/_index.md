---
title: ColorMatrix
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa una matriz 5x5 que contiene las coordenadas para el espacio de color RGBAW. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 27
url: /es/system.drawing.imaging/colormatrix/
---
## ColorMatrix clase


Representa una matriz 5x5 que contiene las coordenadas para el espacio de color RGBAW. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que resultará en errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class ColorMatrix : public System::Object
```

## Métodos

| Method | Description |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Construye una nueva instancia de la clase [ColorMatrix](./) y la inicializa con los valores de la matriz identidad. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Construye una nueva instancia de la clase [ColorMatrix](./) y la inicializa con los valores especificados. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **float** [get_Matrix00](./get_matrix00/)() const | Devuelve un valor en la fila 0 y la columna 0. |
| **float** [get_Matrix01](./get_matrix01/)() const | Devuelve un valor en la fila 0 y la columna 1. |
| **float** [get_Matrix02](./get_matrix02/)() const | Devuelve un valor en la fila 0 y la columna 2. |
| **float** [get_Matrix03](./get_matrix03/)() const | Devuelve un valor en la fila 0 y la columna 3. |
| **float** [get_Matrix04](./get_matrix04/)() const | Devuelve un valor en la fila 0 y la columna 4. |
| **float** [get_Matrix10](./get_matrix10/)() const | Devuelve un valor en la fila 1 y la columna 0. |
| **float** [get_Matrix11](./get_matrix11/)() const | Devuelve un valor en la fila 1 y la columna 1. |
| **float** [get_Matrix12](./get_matrix12/)() const | Devuelve un valor en la fila 1 y la columna 2. |
| **float** [get_Matrix13](./get_matrix13/)() const | Devuelve un valor en la fila 1 y la columna 3. |
| **float** [get_Matrix14](./get_matrix14/)() const | Devuelve un valor en la fila 1 y la columna 4. |
| **float** [get_Matrix20](./get_matrix20/)() const | Devuelve un valor en la fila 2 y la columna 0. |
| **float** [get_Matrix21](./get_matrix21/)() const | Devuelve un valor en la fila 2 y la columna 1. |
| **float** [get_Matrix22](./get_matrix22/)() const | Devuelve un valor en la fila 2 y la columna 2. |
| **float** [get_Matrix23](./get_matrix23/)() const | Devuelve un valor en la fila 2 y la columna 3. |
| **float** [get_Matrix24](./get_matrix24/)() const | Devuelve un valor en la fila 2 y la columna 4. |
| **float** [get_Matrix30](./get_matrix30/)() const | Devuelve un valor en la fila 3 y la columna 0. |
| **float** [get_Matrix31](./get_matrix31/)() const | Devuelve un valor en la fila 3 y la columna 1. |
| **float** [get_Matrix32](./get_matrix32/)() const | Devuelve un valor en la fila 3 y la columna 2. |
| **float** [get_Matrix33](./get_matrix33/)() const | Devuelve un valor en la fila 3 y la columna 3. |
| **float** [get_Matrix34](./get_matrix34/)() const | Devuelve un valor en la fila 3 y la columna 4. |
| **float** [get_Matrix40](./get_matrix40/)() const | Devuelve un valor en la fila 4 y la columna 0. |
| **float** [get_Matrix41](./get_matrix41/)() const | Devuelve un valor en la fila 4 y la columna 1. |
| **float** [get_Matrix42](./get_matrix42/)() const | Devuelve un valor en la fila 4 y la columna 2. |
| **float** [get_Matrix43](./get_matrix43/)() const | Devuelve un valor en la fila 4 y la columna 3. |
| **float** [get_Matrix44](./get_matrix44/)() const | Devuelve un valor en la fila 4 y la columna 4. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Devuelve un valor en la fila y columna especificadas. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Establece el valor especificado en la ubicación indicada de la matriz. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Establece un valor en la fila 0 y la columna 0. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Establece un valor en la fila 0 y la columna 1. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Establece un valor en la fila 0 y la columna 2. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Establece un valor en la fila 0 y la columna 3. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Establece un valor en la fila 0 y la columna 4. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Establece un valor en la fila 1 y la columna 0. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Establece un valor en la fila 1 y la columna 1. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Establece un valor en la fila 1 y la columna 2. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Establece un valor en la fila 1 y la columna 3. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Establece un valor en la fila 1 y la columna 4. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Establece un valor en la fila 2 y la columna 0. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Establece un valor en la fila 2 y la columna 1. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Establece un valor en la fila 2 y la columna 2. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Establece un valor en la fila 2 y la columna 3. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Establece un valor en la fila 2 y la columna 4. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Establece un valor en la fila 3 y la columna 0. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Establece un valor en la fila 3 y la columna 1. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Establece un valor en la fila 3 y la columna 2. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Establece un valor en la fila 3 y la columna 3. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Establece un valor en la fila 3 y la columna 4. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Establece un valor en la fila 4 y la columna 0. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Establece un valor en la fila 4 y la columna 1. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Establece un valor en la fila 4 y la columna 2. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Establece un valor en la fila 4 y la columna 3. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Establece un valor en la fila 4 y la columna 4. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)