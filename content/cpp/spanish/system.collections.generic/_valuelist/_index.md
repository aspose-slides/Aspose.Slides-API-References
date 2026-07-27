---
title: _ValueList
second_title: Referencia de la API de Aspose.Slides para C++
description: "Implementa una lista de valores del diccionario. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 40
url: /es/system.collections.generic/_valuelist/
---
## _ValueList clase

Implementa una lista de valores del diccionario. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) tipo. |

## Métodos

| Método | Descripción |
| --- | --- |
| [_ValueCollection](../_valuecollection/_valuecollection/)(const typename Dict::Ptr\&) | Inicializa la colección que referencia al diccionario especificado. |
| [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | Inicializa la colección que referencia al diccionario especificado. |
| void [Add](../ikvcollection/add/)(const T\&) override | Añade un elemento al contenedor. |
| [BaseKVCollection](../basekvcollection/basekvcollection/)(const typename Dict::Ptr\&) | Crea la colección. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Obtiene un iterador que apunta al primer elemento (si existe) de la colección. Este iterador no puede usarse para cambiar un objeto referenciado porque [GetEnumerator()](../ienumerable/getenumerator/) devuelve una copia del objeto T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Obtiene un iterador que apunta al primer elemento (si existe) de la instancia de la colección calificada como const. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si existe) de la colección. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si existe) de la colección. |
| void [Clear](../ikvcollection/clear/)() override | Elimina todos los elementos del contenedor. |
| **bool** [Contains](../_valuecollection/contains/)(const [TValue](../_valuecollection/tvalue/)\&) const override | Comprueba si el elemento está presente en el contenedor. |
| void [CopyTo](../basekvcollection/copyto/)([ArrayPtr](../../system/arrayptr/)\<KV\>, int) override | Copia datos a los elementos existentes del array. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Obtiene un iterador que apunta justo después del último elemento (si existe) de la colección. Este iterador no puede usarse para cambiar un objeto referenciado porque [GetEnumerator()](../ienumerable/getenumerator/) devuelve una copia del objeto T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Obtiene un iterador que apunta justo después del último elemento (si existe) de la instancia de la colección calificada como const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| int [get_Count](../basekvcollection/get_count/)() const override | Obtiene el número de elementos. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Comprueba si la colección tiene tamaño fijo. |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | Comprueba si el contenedor es de solo lectura. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtiene el objeto mediante el cual se sincroniza la colección. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[TValue](../_valuecollection/tvalue/)\>\> [GetEnumerator](../_valuecollection/getenumerator/)() override | Obtiene el enumerador que itera a través de los valores. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](../icollection/icollection/)() | Constructor predeterminado. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Constructor de copiado. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Constructor de movimiento. |
| virtual [TValue](../_valuecollection/tvalue/) [idx_get](./idx_get/)(int) const | Obtiene el valor en la posición especificada. |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | Función setter. |
| int [IndexOf](../ikvcollection/indexof/)(const T\&) const override | Obtiene el índice del elemento en el contenedor. |
| void [Insert](../ikvcollection/insert/)(int, const T\&) override | Inserta el elemento en la posición especificada. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica una función acumuladora sobre una secuencia. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina si todos los elementos de una secuencia cumplen una condición. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina si una secuencia contiene algún elemento. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina si existe algún elemento en una secuencia o si cumple una condición. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcula el promedio de una secuencia de valores numéricos. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcula el promedio de una secuencia de valores obtenidos invocando una función de transformación en cada elemento de la secuencia de entrada. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Convierte los elementos al tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatena dos secuencias. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina si una secuencia contiene un valor especificado. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Devuelve el número de elementos en la secuencia (calculado mediante recuento directo). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Devuelve el número de elementos en la secuencia que cumplen la condición especificada. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Devuelve el elemento en el índice especificado de una secuencia. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Devuelve el elemento en el índice especificado de una secuencia. |
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
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crea un array a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crea una List<T> a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una secuencia según el predicado especificado. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copiado. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operador de asignación de movimiento. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operador de asignación de movimiento. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de string y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de strings. |
| **bool** [Remove](../ikvcollection/remove/)(const T\&) override | Elimina el elemento del contenedor. |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | Elimina el elemento en la posición especificada. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [SetTemplateWeakPtr](../basekvcollection/settemplateweakptr/)(**uint32_t**) override | Permite la compilación, pero en realidad no hace nada ya que esta estructura no posee datos. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeBeginConstIterator](../_valuecollection/virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeBeginIterator](../_valuecollection/virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeEndConstIterator](../_valuecollection/virtualizeendconstiterator/)() const override | Obtiene la implementación del iterador const end para el contenedor actual. |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeEndIterator](../_valuecollection/virtualizeenditerator/)() override | Obtiene la implementación del iterador end para el contenedor actual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [TValue](./tvalue/) | Tipo de valor. |

## Ver también

* Class [_ValueCollection](../_valuecollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)