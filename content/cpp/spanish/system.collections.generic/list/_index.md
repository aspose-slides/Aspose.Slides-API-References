---
title: List
second_title: Referencia de API de Aspose.Slides para C++
description: Declaración adelantada de List.
type: docs
weight: 430
url: /es/system.collections.generic/list/
---
## Clase List


[List](./) declaración anticipada.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Específico de C++. |
| void [Add](./add/)(const T\&) override | Agrega un elemento al final de la lista. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Agrega elementos a la lista; se utiliza al traducir inicializadores. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Agrega todos los elementos de la colección (o de sí mismo) al final de la lista actual. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Obtiene una referencia de solo lectura a esta colección. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Obtiene un iterador al primer elemento de la colección. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Obtiene un iterador al primer elemento de la colección con calificador const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Busca un elemento en una lista ordenada. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Busca un elemento en una lista ordenada. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Busca un elemento en una lista ordenada. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Obtiene un iterador al primer elemento con calificador const de la colección. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Obtiene un iterador para un elemento const inexistente detrás del final de la colección. |
| void [Clear](./clear/)() override | Elimina todos los elementos. |
| **bool** [Contains](./contains/)(const T\&) const override | Comprueba si el elemento está presente en la lista. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Crea una lista de elementos convertidos a un tipo diferente. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copia los elementos de la lista en elementos de una matriz existente. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copia todos los elementos en elementos de una matriz existente. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copia los elementos a partir del índice especificado en elementos de una matriz existente. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Obtiene un iterador inverso al último elemento const de la colección (el primero en reversa). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Obtiene un iterador inverso para un elemento const inexistente antes del inicio de la colección. |
| [vector_t](./vector_t/)\& [data](./data/)() | Función de acceso a la estructura de datos subyacente. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Función de acceso a la estructura de datos subyacente. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Obtiene un iterador para un elemento inexistente detrás del final de la colección. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Obtiene un iterador para un elemento inexistente detrás del final de la colección con calificador const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Comprueba si existe un elemento que cumpla un predicado específico en la lista. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Busca un elemento que cumpla un predicado específico. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Busca elementos que cumplan un predicado específico. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Busca un elemento que cumpla un predicado específico. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Busca un elemento que cumpla un predicado específico. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Busca un elemento que cumpla un predicado específico. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Busca el último elemento que cumpla un predicado específico. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Aplica una acción a todos los elementos de la lista. |
| int [get_Capacity](./get_capacity/)() const | Obtiene la capacidad actual de la lista. |
| int [get_Count](./get_count/)() const override | Obtiene el número de elementos en la lista actual. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Comprueba si la colección tiene un tamaño fijo. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Comprueba si la colección es de solo lectura. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtiene el objeto a través del cual la colección está sincronizada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Obtiene un enumerador para iterar a través de los elementos de la lista. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Crea una porción de la lista. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Constructor por defecto. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Constructor de copia. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Constructor de movimiento. |
| T [idx_get](./idx_get/)(int) const override | Obtiene el elemento en una posición específica. |
| void [idx_set](./idx_set/)(int, T) override | Establece el elemento en una posición específica. |
| int [IndexOf](./indexof/)(const T\&) const override | Obtiene el primer índice del elemento específico. |
| int [IndexOf](./indexof/)(const T\&, int) const | Busca un elemento específico en la lista. |
| void [Insert](./insert/)(int, const T\&) override | Inserta un elemento en la posición especificada. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Inserta un rango de datos en la posición específica. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro de toda la lista. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en el [List](./) que se extiende desde el primer elemento hasta el índice especificado. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en el [List](./) que contiene el número especificado de elementos y termina en el índice especificado. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica una función acumuladora sobre una secuencia. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina si todos los elementos de una secuencia cumplen una condición. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina si una secuencia contiene algún elemento. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina si existe algún elemento en la secuencia o cumple una condición. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcula el promedio de una secuencia de valores numéricos. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcula el promedio de una secuencia de valores obtenidos invocando una función de transformación en cada elemento de la secuencia de entrada. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Convierte los elementos al tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatena dos secuencias. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina si una secuencia contiene un valor especificado. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Devuelve el número de elementos en la secuencia (calculado mediante conteo directo). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Devuelve el número de elementos en la secuencia que cumplen la condición especificada. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Devuelve el elemento en un índice especificado de una secuencia. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Devuelve el elemento en un índice especificado de una secuencia. |
| T [LINQ_First](../ienumerable/linq_first/)() | Devuelve el primer elemento de una secuencia. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Devuelve el primer elemento de una secuencia que cumple la condición especificada. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Devuelve el primer elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Devuelve el primer elemento de la secuencia que satisface una condición o un valor predeterminado si no se encuentra tal elemento. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Agrupa los elementos de una secuencia. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Agrupa los elementos de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Devuelve el último elemento de una secuencia. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Devuelve el último elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtra los elementos de la secuencia según el tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena los elementos de una secuencia en orden ascendente según los valores de clave seleccionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena los elementos de una secuencia en orden descendente según los valores de clave seleccionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Invierte el orden de los elementos en una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforma los elementos de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de una secuencia en una nueva forma incorporando el índice del elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una sola secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Omite un número especificado de elementos contiguos desde el inicio de una secuencia y devuelve el resto. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Devuelve un número especificado de elementos contiguos desde el inicio de una secuencia. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crea una matriz a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crea una List<T> a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una secuencia según el predicado especificado. |
|  [List](./list/)() | Crea una lista vacía. |
|  [List](./list/)(int) | Crea una lista con capacidad predefinida. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Constructor de copia. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operador de asignación por movimiento. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operador de asignación por movimiento. |
| vector_t::reference [operator[]](./operator[]/)(int) | Función de acceso. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Función de acceso. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Obtiene un iterador inverso al último elemento de la colección (el primero en reversa). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Obtiene un iterador inverso al último elemento de la colección con calificador const (el primero en reversa). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| **bool** [Remove](./remove/)(const T\&) override | Elimina la primera instancia del elemento específico de la lista. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Elimina todos los elementos que coinciden con un predicado específico. |
| void [RemoveAt](./removeat/)(int) override | Elimina el elemento en la posición especificada. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [RemoveRange](./removerange/)(int, int) | Elimina una porción de la lista. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección con calificador const. |
| void [Reverse](./reverse/)() | Invierte el orden de los elementos de toda la lista. |
| void [Reverse](./reverse/)(int, int) | Invierte el orden de los elementos de la porción de la lista. |
| void [set_Capacity](./set_capacity/)(int) | Establece la capacidad de la lista. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Ordena los elementos en la lista. |
| void [Sort](./sort/)() | Ordena los elementos en la lista usando el comparador predeterminado. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Ordena los elementos en la porción de la lista. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ordena los elementos en la lista. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Convierte la lista a una matriz. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| void [TrimExcess](./trimexcess/)() | Ajusta la capacidad de la lista a su tamaño. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determina si todos los elementos de la colección cumplen las condiciones definidas por el predicado especificado. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del iterador const end para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del iterador end para el contenedor actual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Definiciones de tipos

| Definición | Descripción |
| --- | --- |
| [ValueType](./valuetype/) | Este tipo. |
| [BaseType](./basetype/) | Tipo de interfaz. |
| [vector_t](./vector_t/) | Tipo de datos subyacente. |
| [iterator](./iterator/) | Tipo de iterador. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |
| [IEnumerablePtr](./ienumerableptr/) | Contenedor que contiene elementos del mismo tipo que este. |
| [IEnumeratorPtr](./ienumeratorptr/) | Tipo **Enumerator**. |
## Observaciones


[List](./) - envoltorio alrededor de std::vector para ser usado en código traducido. Requiere que el operador == esté implementado para el tipo de elemento. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.


```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crea la primera lista.
  auto list1 = MakeObject<List<int>>();

  // Llena la primera lista.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Ordena la primera lista.
  // Los elementos de la primera lista serán: {-5, 1, 3, 8}
  list1->Sort();

  // Elimina el elemento en el índice 2.
  // Los elementos de la primera lista serán: {-5, 1, 8}
  list1->RemoveAt(2);

  // Inserta el elemento en el índice 1.
  // Los elementos de la primera lista serán: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Crea la segunda lista.
  auto list2 = MakeObject<List<int>>();

  // Llena la segunda lista.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Añade los elementos de la segunda lista a la primera.
  list1->AddRange(list2);

  // Imprime los elementos de la primera lista.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
- 5 15 1 8 10 20 30
*/
```

## Ver también

* Clase [Object](../../system/object/)
* Clase [IList](../ilist/)
* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)