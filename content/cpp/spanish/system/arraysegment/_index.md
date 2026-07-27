---
title: ArraySegment
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un segmento de la matriz unidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 40
url: /es/system/arraysegment/
---
## ArraySegment clase

Representa un segmento de la matriz unidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use [System::SmartPtr](../smartptr/) clase para gestionar objetos de este tipo.

```cpp
template<typename T>class ArraySegment : public System::Object
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of the array segment elements. |
## Métodos

| Método | Descripción |
| --- | --- |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>) |  |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>, **int32_t**, **int32_t**) |  |
|  [ArraySegment](./arraysegment/)() |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([ArraySegment](./)\<T\>) |  |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::ArrayPtr](../arrayptr/)\<T\> [get_Array](./get_array/)() const |  |
| **int32_t** [get_Count](./get_count/)() const |  |
| **int32_t** [get_Offset](./get_offset/)() const |  |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| T\& [operator[]](./operator[]/)(**int32_t**) const |  |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [ArraySegment](./)\<T\> [Slice](./slice/)(**int32_t**, **int32_t**) |  |
| [System::ArrayPtr](../arrayptr/)\<T\> [ToArray](./toarray/)() const |  |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Análogo del método C# [Object.ToString()](../object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Observaciones

```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Crear y llenar la matriz.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Crear el segmento de matriz que contiene la matriz completa.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Imprimir los elementos del segmento de matriz.
  Print(fullArray);

  // Crear el segmento de matriz.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Imprimir los elementos del segmento de matriz.
  Print(segment);

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
First Second Third
Second Third
*/
```

## Ver también

* Clase [Object](../object/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)