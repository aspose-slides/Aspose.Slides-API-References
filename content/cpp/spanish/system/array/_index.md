---
title: Array
second_title: Referencia de la API de Aspose.Slides para C++
description: "Clase que representa una estructura de datos de tipo array. Los objetos de esta clase solo deben asignarse mediante las funciones System::MakeArray() y System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni mediante el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 14
url: /es/system/array/
---
## Array clase

Clase que representa una estructura de datos de tipo array. Los objetos de esta clase solo deben asignarse usando las funciones [System::MakeArray()](../makearray/) y [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elementos de un array |

## Métodos

| Método | Descripción |
| --- | --- |
| void [Add](./add/)(const T&) override | No soportado porque el array representado por el objeto actual es de solo lectura. |
|  [Array](./array/)() | Construye un array vacío. |
|  [Array](./array/)(int, const T&) | Constructor de llenado. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Constructor de llenado. |
|  [Array](./array/)(int, const T) | Constructor de llenado. |
|  [Array](./array/)(**vector_t**\&&) | Constructor de movimiento. |
|  [Array](./array/)(const **vector_t**\&) | Constructor de copia. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Construye un objeto [Array](./) y lo llena con los valores copiados de un objeto std::vector cuyo tipo de valores es el mismo que **T**, pero diferente de **UnderlyingType**. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Construye un objeto [Array](./) y lo llena con los valores movidos de un objeto std::vector cuyo tipo de valores es el mismo que **T**, pero diferente de **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Construye un objeto [Array](./) y lo llena con los valores de la lista de inicialización especificada que contiene elementos de tipo **UnderlyingType**. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Construye un objeto [Array](./) y lo llena con los valores del array especificado que contiene elementos de tipo **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Construye un objeto [Array](./) y lo llena con los valores de la lista de inicialización especificada que contiene elementos de tipo bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Convierte el array a una colección de solo lectura. |
| [iterator](./iterator/) [begin](./begin/)() | Devuelve un iterador al primer elemento del contenedor. Si el contenedor está vacío, el iterador devuelto será igual a [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Devuelve un iterador al primer elemento del contenedor calificado como const. Si el contenedor está vacío, el iterador devuelto será igual a [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Realiza una búsqueda binaria en el array ordenado. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NO IMPLEMENTADO. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Devuelve un iterador al primer elemento calificado como const del contenedor. Si el contenedor está vacío, el iterador devuelto será igual a [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Devuelve un iterador al elemento que sigue al último elemento del contenedor. Este elemento actúa como marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| void [Clear](./clear/)() override | No soportado porque el array representado por el objeto actual es de solo lectura. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Reemplaza **count** valores a partir del índice **startIndex** en el array especificado con valores predeterminados. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Clona el array. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia un rango de elementos de un [System.Array](./) comenzando en la fuente especificada. |
| **bool** [Contains](./contains/)(const T\&) const override | Determina si el elemento especificado está en el array. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Construye un nuevo objeto [Array](./) y lo llena con los elementos del array especificado convertidos al tipo **OutputType** utilizando el delegado convertidor especificado. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Construye un nuevo objeto [Array](./) y lo llena con los elementos del array especificado convertidos al tipo **OutputType** mediante el objeto de función convertidora especificado. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia la cantidad especificada de elementos del array origen al array destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia la cantidad especificada de elementos de la vista del array fuente al array destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Copia la cantidad especificada de elementos del array origen a la vista del array destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Copia la cantidad especificada de elementos de la vista del array fuente a la vista del array destino. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia la cantidad especificada de elementos del array origen en la pila al array destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Copia la cantidad especificada de elementos del array origen al array destino en la pila. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Copia la cantidad especificada de elementos del array origen en la pila al array destino en la pila. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos del array origen comenzando en el índice especificado a la posición especificada en el array destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos de la vista del array fuente comenzando en el índice especificado a la posición especificada en el array destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos del array origen comenzando en el índice especificado a la posición especificada en la vista del array destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos de la vista del array fuente comenzando en el índice especificado a la posición especificada en la vista del array destino. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos del array origen en la pila comenzando en el índice especificado a la posición especificada en el array destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos del array origen comenzando en el índice especificado a la posición especificada en el array destino en la pila. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos del array origen en la pila comenzando en el índice especificado a la posición especificada en el array destino en la pila. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copia una cantidad especificada de elementos de la vista del array fuente comenzando en el índice especificado a la posición especificada en el array destino en la pila. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Copia todos los elementos del array actual al array destino especificado. Los elementos se insertan en el array destino a partir del índice especificado por el argumento arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Copia todos los elementos del array actual al array destino especificado. Los elementos se insertan en el array destino a partir del índice especificado por el argumento dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Copia todos los elementos del array actual a la vista del array destino especificada. Los elementos se insertan en la vista del array destino a partir del índice especificado por el argumento dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copia una cantidad especificada de elementos del array actual comenzando en la posición especificada al array destino especificado. Los elementos se insertan en el array destino a partir del índice especificado por el argumento dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copia una cantidad especificada de elementos del array actual comenzando en la posición especificada a la vista del array destino especificada. Los elementos se insertan en la vista del array destino a partir del índice especificado por el argumento dstIndex. |
| int [Count](./count/)() const | Devuelve un número que representa la cantidad total de todos los elementos en todas las dimensiones del array. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| **vector_t**\& [data](./data/)() | Devuelve una referencia a la estructura de datos interna utilizada para almacenar los elementos del array. |
| const **vector_t**\& [data](./data/)() const | Devuelve una referencia constante a la estructura de datos interna utilizada para almacenar los elementos del array. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Devuelve un puntero sin procesar al comienzo del búfer de memoria donde se almacenan los elementos del array. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Devuelve un puntero constante sin procesar al comienzo del búfer de memoria donde se almacenan los elementos del array. |
| [iterator](./iterator/) [end](./end/)() | Devuelve un iterador al elemento que sigue al último elemento del contenedor. Este elemento actúa como marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Devuelve un iterador al elemento que sigue al último elemento del contenedor calificado como const. Este elemento actúa como marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Determina si el objeto [Array](./) especificado contiene un elemento que satisface los requisitos del predicado especificado. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Recupera todos los elementos que coinciden con las condiciones definidas por el predicado especificado. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Ejecuta la acción especificada en cada elemento de la matriz especificada. |
| int [get_Count](./get_count/)() const override | Devuelve el tamaño de la matriz. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Comprueba si la colección tiene un tamaño fijo. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Indica si la matriz es de solo lectura. |
| **int32_t** [get_Length](./get_length/)() const override | Devuelve un entero de 32 bits que representa el número total de todos los elementos en todas las dimensiones de la matriz. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Devuelve un entero de 64 bits que representa el número total de todos los elementos en todas las dimensiones de la matriz. |
| **int32_t** [get_Rank](./get_rank/)() const | NO IMPLEMENTADO. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Obtiene el objeto a través del cual se sincroniza la colección. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Devuelve un puntero a un objeto **Enumerator** que proporciona la interfaz IEnumerator a los elementos de la matriz representada por el objeto actual. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../object/gethashcode/). Permite el hashing de objetos personalizados. |
| int [GetLength](./getlength/)(int) | Devuelve el número de elementos en la dimensión especificada. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Devuelve el número de elementos en la dimensión especificada como entero de 64 bits. |
| int [GetLowerBound](./getlowerbound/)(int) const | Devuelve el límite inferior de la dimensión especificada. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Devuelve una variable std::size_t que representa el número total de todos los elementos en todas las dimensiones de la matriz. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Devuelve el límite superior de la dimensión especificada. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Constructor predeterminado. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Constructor de copia. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Constructor de movimiento. |
| T [idx_get](./idx_get/)(int) const override | Devuelve el elemento en el índice especificado. |
| void [idx_set](./idx_set/)(int, T) override | Establece el valor especificado como el elemento de la matriz en el índice especificado. |
| int [IndexOf](./indexof/)(const T\&) const override | Determina el índice de la primera aparición del elemento especificado en la matriz. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Determina el índice de la primera aparición del elemento especificado en la matriz. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Determina el índice de la primera aparición del elemento especificado en la matriz a partir del índice especificado. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Determina el índice de la primera aparición del elemento especificado en un rango de elementos de la matriz definido por el índice de inicio y el número de elementos del rango. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Llena la matriz representada por el objeto actual con los valores de la matriz especificada. |
| void [Initialize](./initialize/)() | Llena la matriz con los objetos predeterminados construidos del tipo **T**. |
| void [Insert](./insert/)(int, const T\&) override | No soportado porque la matriz representada por el objeto actual es de solo lectura. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Determina el índice de la última aparición del elemento especificado en un rango de elementos de la matriz definido por el índice de inicio y el número de elementos del rango. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Determina el índice de la última aparición del elemento especificado en la matriz a partir del índice especificado. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Determina el índice de la última aparición del elemento especificado en la matriz. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Aplica una función acumuladora sobre una secuencia. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina si todos los elementos de una secuencia cumplen una condición. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina si una secuencia contiene algún elemento. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina si existe algún elemento de una secuencia o si satisface una condición. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Calcula el promedio de una secuencia de valores numéricos. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Calcula el promedio de una secuencia de valores obtenidos al invocar una función de transformación en cada elemento de la secuencia de entrada. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Convierte los elementos al tipo especificado. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatena dos secuencias. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Determina si una secuencia contiene un valor especificado. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Devuelve el número de elementos en la secuencia (calculado mediante recuento directo). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Devuelve el número de elementos en la secuencia que cumplen la condición especificada. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Devuelve el elemento en un índice especificado en una secuencia. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Devuelve el elemento en un índice especificado en una secuencia. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Devuelve el primer elemento de una secuencia. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Devuelve el primer elemento de una secuencia que cumple la condición especificada. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Devuelve el primer elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Devuelve el primer elemento de la secuencia que satisface una condición o un valor predeterminado si no se encuentra tal elemento. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Agrupa los elementos de una secuencia. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Agrupa los elementos de una secuencia. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Devuelve el último elemento de una secuencia. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Devuelve el último elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra los elementos de la secuencia según el tipo especificado. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Ordena los elementos de una secuencia en orden ascendente según los valores clave seleccionados por keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Ordena los elementos de una secuencia en orden descendente según los valores clave seleccionados por keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Invierte el orden de los elementos en una secuencia. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transforma los elementos de una secuencia. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de una secuencia en una nueva forma incorporando el índice del elemento. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una sola secuencia. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Omite un número especificado de elementos contiguos desde el inicio de una secuencia y devuelve el resto. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Devuelve un número especificado de elementos contiguos desde el inicio de una secuencia. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Crea una matriz a partir de una secuencia. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Crea una List<T> a partir de una secuencia. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una secuencia según el predicado especificado. |
| void [Lock](../object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto sentry [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Encuentra el elemento más grande en la matriz usando [operator<()](../operator_less/) para comparar los elementos. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite la clonación de tipos personalizados. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Encuentra el elemento más pequeño en la matriz usando [operator<()](../operator_less/) para comparar los elementos. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operador de asignación por movimiento. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operador de asignación por movimiento. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Devuelve un elemento en el índice especificado. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Devuelve un elemento en el índice especificado. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Devuelve un puntero al primer elemento de una matriz unidimensional. Para matrices multidimensionales el resultado es indefinido. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de string y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadenas. |
| **bool** [Remove](./remove/)(const T\&) override | No soportado porque el array representado por el objeto actual es de solo lectura. |
| void [RemoveAt](./removeat/)(int) override | No soportado porque el array representado por el objeto actual es de solo lectura. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Cambia el tamaño del array especificado al valor indicado o crea un nuevo array con el tamaño especificado. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Invierte los elementos del array especificado. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Invierte un rango de elementos en el array especificado. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Hace que el array trate los punteros almacenados como débiles (si es aplicable). |
| void [SetValue](./setvalue/)(const T\&, int) | Establece el valor del elemento en el índice especificado. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Ordena los elementos del array especificado utilizando el comparador predeterminado. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Ordena un rango de elementos del array especificado utilizando el comparador predeterminado. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Ordena los elementos del array especificado utilizando el comparador especificado. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NO IMPLEMENTADO. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Ordena los elementos del array especificado utilizando la comparación especificada. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Ordena dos arrays, uno que contiene claves y el otro los elementos correspondientes, basándose en los valores del array que contiene claves, cuyos elementos se comparan usando el operador <. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Ordena dos arrays, uno que contiene claves y el otro los elementos correspondientes, basándose en los valores del array que contiene claves, cuyos elementos se comparan usando el comparador predeterminado. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Análogo del método C# [Object.ToString()](../object/tostring/). Permite convertir objetos personalizados a string. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Determina si todos los elementos del array especificado cumplen las condiciones definidas por el predicado especificado. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del iterador const end para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del iterador end para el contenedor actual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [ValueType](./valuetype/) | Alias del tipo de los elementos del array. |
| [UnderlyingType](./underlyingtype/) | Alias del tipo usado para representar cada elemento del array. |
| [EnumerablePtr](./enumerableptr/) | Un alias para el tipo de puntero compartido que apunta a un objeto IEnumerable que contiene elementos del tipo **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Un alias para el tipo de puntero compartido que apunta a un objeto IEnumerator que contiene elementos del tipo **T**. |
| [iterator](./iterator/) | Tipo de iterador. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |

## Observaciones

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Crear y llenar el array.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Imprimir los elementos del array.
  Print(arrayPtr);

  // Ordenar los elementos del array en forma ascendente.
  Array<int32_t>::Sort(arrayPtr);

  // Imprimir los elementos del array.
  Print(arrayPtr);

  // Imprimir la cantidad de elementos del array.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Imprimir el índice del elemento que equivale a 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Redimensionar el array.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Imprimir los elementos del array.
  Print(arrayPtr);

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Véase también

* Clase [ArrayBase](../arraybase/)
* Clase [IList](../../system.collections.generic/ilist/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)