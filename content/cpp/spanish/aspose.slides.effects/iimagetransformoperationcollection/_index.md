---
title: IImageTransformOperationCollection
second_title: Referencia de API de Aspose.Slides para C++
description: Representa una colección de efectos aplicados a una imagen.
type: docs
weight: 742
url: /es/aspose.slides.effects/iimagetransformoperationcollection/
---
## IImageTransformOperationCollection clase

Representa una colección de efectos aplicados a una imagen.

```cpp
class IImageTransformOperationCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Aspose::Slides::Effects::IImageTransformOperation>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual void [Add](../../system.collections.generic/icollection/add/)(const T\&) | Agrega un elemento a la colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaBiLevel](../ialphabilevel/)\> [AddAlphaBiLevelEffect](./addalphabileveleffect/)(**float**) | Agrega el nuevo efecto Alpha Bi-Level al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaCeiling](../ialphaceiling/)\> [AddAlphaCeilingEffect](./addalphaceilingeffect/)() | Agrega el nuevo efecto Alpha Ceiling al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaFloor](../ialphafloor/)\> [AddAlphaFloorEffect](./addalphaflooreffect/)() | Agrega el nuevo efecto Alpha Floor al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaInverse](../ialphainverse/)\> [AddAlphaInverseEffect](./addalphainverseeffect/)() | Agrega el nuevo efecto Alpha Inverse al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulate](../ialphamodulate/)\> [AddAlphaModulateEffect](./addalphamodulateeffect/)() | Agrega el nuevo efecto Alpha Modulate al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixed](../ialphamodulatefixed/)\> [AddAlphaModulateFixedEffect](./addalphamodulatefixedeffect/)(**float**) | Agrega el nuevo efecto Alpha Modulate Fixed al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaReplace](../ialphareplace/)\> [AddAlphaReplaceEffect](./addalphareplaceeffect/)(**float**) | Agrega el nuevo efecto Alpha Replace al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBiLevel](../ibilevel/)\> [AddBiLevelEffect](./addbileveleffect/)(**float**) | Agrega el nuevo efecto Bi-Level (blanco/negro) al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlur](../iblur/)\> [AddBlurEffect](./addblureffect/)(**double**, **bool**) | Agrega el nuevo efecto [Blur](../blur/) al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBrightnessContrast](../ibrightnesscontrast/)\> [AddBrightnessContrastEffect](./addbrightnesscontrasteffect/)(**float**, **float**) | Agrega el nuevo efecto [BrightnessContrast](../brightnesscontrast/) al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorChange](../icolorchange/)\> [AddColorChangeEffect](./addcolorchangeeffect/)() | Agrega el nuevo efecto Color Change al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorReplace](../icolorreplace/)\> [AddColorReplaceEffect](./addcolorreplaceeffect/)() | Agrega el nuevo efecto Color Replacement al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDuotone](../iduotone/)\> [AddDuotoneEffect](./addduotoneeffect/)() | Agrega el nuevo efecto [Duotone](../duotone/) al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlay](../ifilloverlay/)\> [AddFillOverlayEffect](./addfilloverlayeffect/)() | Agrega el nuevo efecto Fill Overlay al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGrayScale](../igrayscale/)\> [AddGrayScaleEffect](./addgrayscaleeffect/)() | Agrega el nuevo efecto Gray Scale al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHSL](../ihsl/)\> [AddHSLEffect](./addhsleffect/)(**float**, **float**, **float**) | Agrega el nuevo efecto Hue/Saturation/Luminance al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILuminance](../iluminance/)\> [AddLuminanceEffect](./addluminanceeffect/)(**float**, **float**) | Agrega el nuevo efecto [Luminance](../luminance/) al final de una colección. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITint](../itint/)\> [AddTintEffect](./addtinteffect/)(**float**, **float**) | Agrega el nuevo efecto [Tint](../tint/) al final de una colección. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Obtiene el iterador que apunta al primer elemento (si lo hay) de la colección. Este iterador no puede usarse para cambiar un objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) devuelve un objeto copia de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Obtiene el iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Obtiene el iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Obtiene el iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| virtual void [Clear](../../system.collections.generic/icollection/clear/)() | Elimina todos los elementos de la colección. |
| virtual **bool** [Contains](../../system.collections.generic/icollection/contains/)(const T\&) const | Verifica si el elemento está presente en la colección. |
| virtual void [CopyTo](../../system.collections.generic/icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Copia todos los elementos de la colección a elementos de una matriz existente. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Obtiene el iterador que apunta justo después del último elemento (si lo hay) de la colección. Este iterador no puede usarse para cambiar un objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) devuelve un objeto copia de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Obtiene el iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual int [get_Count](../../system.collections.generic/icollection/get_count/)() const | Obtiene el número de elementos en la colección. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Verifica si la colección es de solo lectura. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Obtiene el objeto a través del cual se sincroniza la colección. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../../system.collections.generic/ienumerable/getenumerator/)() | Obtiene el enumerador. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Constructor predeterminado. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Constructor de copia. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Constructor de movimiento. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImageTransformOperation](../iimagetransformoperation/)\> [idx_get](./idx_get/)(**int32_t**) | Devuelve un [IImageTransformOperation](../iimagetransformoperation/) de la colección por su índice. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica una función acumuladora sobre una secuencia. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina si todos los elementos de una secuencia cumplen una condición. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina si una secuencia contiene algún elemento. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina si existe algún elemento en la secuencia o si cumple una condición. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Calcula el promedio de una secuencia de valores numéricos. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcula el promedio de una secuencia de valores obtenidos invocando una función de transformación en cada elemento de la secuencia de entrada. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Convierte los elementos al tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatena dos secuencias. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Determina si una secuencia contiene un valor especificado. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Devuelve el número de elementos en la secuencia (calculado mediante recuento directo). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Devuelve el número de elementos en la secuencia que cumplen la condición especificada. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Devuelve el elemento en un índice especificado de una secuencia. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Devuelve el elemento en un índice especificado de una secuencia. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Devuelve el primer elemento de una secuencia. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Devuelve el primer elemento de una secuencia que cumple la condición especificada. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Devuelve el primer elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Devuelve el primer elemento de la secuencia que cumple una condición o un valor predeterminado si no se encuentra tal elemento. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Agrupa los elementos de una secuencia. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Agrupa los elementos de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Devuelve el último elemento de una secuencia. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Devuelve el último elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra los elementos de la secuencia según el tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena los elementos de una secuencia en orden ascendente según los valores de clave seleccionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena los elementos de una secuencia en orden descendente según los valores de clave seleccionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Invierte el orden de los elementos en una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforma los elementos de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de una secuencia en una nueva forma incorporando el índice del elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una sola secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Omite un número especificado de elementos contiguos desde el inicio de una secuencia y devuelve el resto. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Devuelve un número especificado de elementos contiguos desde el inicio de una secuencia. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Crea una matriz a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Crea una List<T> a partir de una secuencia. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una secuencia según el predicado especificado. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operador de asignación por movimiento. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operador de asignación por movimiento. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| virtual **bool** [Remove](../../system.collections.generic/icollection/remove/)(const T\&) | Elimina el elemento de la colección. |
| virtual void [RemoveAt](./removeat/)(**int32_t**) | Elimina un efecto de imagen de una colección en el índice especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Obtiene la implementación del iterador begin const para el contenedor actual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Obtiene la implementación del iterador begin para el contenedor actual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Obtiene la implementación del iterador end const para el contenedor actual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Obtiene la implementación del iterador end para el contenedor actual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [ICollection](../../system.collections.generic/icollection/)
* Espacio de nombres [Aspose::Slides::Effects](../)
* Biblioteca [Aspose.Slides](../../)