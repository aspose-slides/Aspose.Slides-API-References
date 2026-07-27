---
title: Dictionary
second_title: Referencia de la API de Aspose.Slides para C++
description: Declaración adelantada de la clase Dictionary.
type: docs
weight: 144
url: /es/system.collections.generic/dictionary/
---
## Clase Dictionary

Declaración adelantada de la clase [Dictionary](./).

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |

## Métodos

| Method | Description |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | Agrega un par clave-valor al contenedor. |
| virtual void [Add](../icollection/add/)(const T&) | Agrega un elemento a la colección. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. Este iterador no puede usarse para modificar el objeto referenciado porque [GetEnumerator()](../ienumerable/getenumerator/) devuelve una copia del objeto T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Obtiene un iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| virtual void [Clear](../icollection/clear/)() | Elimina todos los elementos de la colección. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | Comprueba si el elemento está presente en la colección. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | Comprueba si el contenedor contiene la clave. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | Copia el contenido del diccionario en elementos de una matriz existente. |
| [Dictionary](./dictionary/)() | Crea un diccionario vacío. |
| [Dictionary](./dictionary/)(const [map_t](./map_t/)&) | Copia datos del mapa. |
| [Dictionary](./dictionary/)(int) | Sobrecarga que corresponde a crear un diccionario pre-asignado; en realidad no realiza asignación. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&) | Constructor de copia. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../iequalitycomparer/)<TKey>>& ) | Constructor de copia. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../iequalitycomparer/)<TKey>>& ) | Crea un diccionario vacío. |
| [Dictionary](./dictionary/)(int, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../iequalitycomparer/)<TKey>>& ) | Crea un diccionario vacío. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. Este iterador no puede usarse para modificar el objeto referenciado porque [GetEnumerator()](../ienumerable/getenumerator/) devuelve una copia del objeto T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Solo para uso interno. |
| virtual int [get_Count](../icollection/get_count/)() const | Obtiene el número de elementos en la colección. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Comprueba si el tamaño de la colección es fijo. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Comprueba si la colección es de solo lectura. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Comprueba si el contenedor es seguro para subprocesos. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](../idictionary/get_keys/)() const | Accede a la colección de claves. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtiene el objeto a través del cual se sincroniza la colección. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](../idictionary/get_values/)() const | Accede a la colección de valores. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Crea un objeto enumerador. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | Devuelve el valor si se encuentra; o **Value()** en caso contrario. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Devuelve el valor si se encuentra; o **defaultValue** en caso contrario. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | Devuelve el valor si se encuentra; o **null** en caso contrario, solo tiene sentido para tipos de referencia. |
| [ICollection](../icollection/icollection/)() | Constructor predeterminado. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Constructor de copia. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Constructor de movimiento. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | Función getter. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | Función setter. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Aplica una función acumuladora sobre una secuencia. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Determina si todos los elementos de una secuencia cumplen una condición. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina si una secuencia contiene algún elemento. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Determina si existe algún elemento en la secuencia o cumple una condición. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcula el promedio de una secuencia de valores numéricos. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Calcula el promedio de una secuencia de valores obtenidos al invocar una función de transformación en cada elemento de la secuencia de entrada. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Convierte los elementos al tipo especificado. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> ) | Concatena dos secuencias. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina si una secuencia contiene un valor especificado. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Devuelve el número de elementos en la secuencia (calculado mediante conteo directo). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Devuelve el número de elementos en la secuencia que cumplen la condición especificada. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Devuelve el elemento en un índice especificado en una secuencia. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Devuelve el elemento en un índice especificado en una secuencia. |
| T [LINQ_First](../ienumerable/linq_first/)() | Devuelve el primer elemento de una secuencia. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Devuelve el primer elemento de una secuencia que cumple la condición especificada. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Devuelve el primer elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Devuelve el primer elemento de la secuencia que cumple una condición o un valor predeterminado si no se encuentra tal elemento. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Agrupa los elementos de una secuencia. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Agrupa los elementos de una secuencia. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Devuelve el último elemento de una secuencia. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Devuelve el último elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtra los elementos de la secuencia según el tipo especificado. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Ordena los elementos de una secuencia en orden ascendente según los valores de clave seleccionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Ordena los elementos de una secuencia en orden descendente según los valores de clave seleccionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Invierte el orden de los elementos en una secuencia. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Transforma los elementos de una secuencia. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Transforma cada elemento de una secuencia en una nueva forma incorporando el índice del elemento. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> & ) | Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una única secuencia. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> & ) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Omite un número especificado de elementos contiguos desde el inicio de una secuencia y devuelve el resto. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Devuelve un número especificado de elementos contiguos desde el inicio de una secuencia. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crea una matriz a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crea una List<T> a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Filtra una secuencia según el predicado especificado. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea un objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Operador de asignación por movimiento. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Operador de asignación por movimiento. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | Elimina la clave del contenedor. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | Elimina el elemento de la colección. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en los contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | Busca el valor y lo recupera si se encuentra. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Obtiene la implementación del iterador const begin para el contenedor actual. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Obtiene la implementación del iterador begin para el contenedor actual. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Obtiene la implementación del iterador const end para el contenedor actual. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Obtiene la implementación del iterador end para el contenedor actual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [KeyCollection](./keycollection/) | Colección de claves a extraer. |
| [ValueCollection](./valuecollection/) | Colección de valores a extraer. |
| [map_t](./map_t/) | Tipo de datos subyacente. |
| [Ptr](./ptr/) | Tipo de puntero. |
| [KVPair](./kvpair/) | Tipo de par clave-valor. |
| [IEnumerablePtr](./ienumerableptr/) | Puntero a la interfaz enumerable. |
| [IEnumeratorPtr](./ienumeratorptr/) | Puntero al enumerador. |

## Observaciones

[Dictionary](./) que asigna valores a claves. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crear la instancia de la clase Dictionary.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Llenar el diccionario.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Imprimir los elementos del diccionario.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
0 - Foo
1 - Bar
2 - Baz
*/
```

## Véase también

* Clase [BaseDictionary](../basedictionary/)
* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)