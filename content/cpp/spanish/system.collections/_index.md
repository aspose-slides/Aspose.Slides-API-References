---
title: "System::Collections"
second_title: "Referencia de la API de Aspose.Slides para C++"
description: 
type: docs
weight: 300
url: /es/system.collections/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) de bits que pueden ser accedidos por índice. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que resultará en errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [BitArrayPtr](./bitarrayptr/) | Puntero a [BitArray](./bitarray/). Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante. |
| [CollectionBase](./collectionbase/) | Proporciona una clase base abstracta para una colección fuertemente tipada. |
| [ICollection](./icollection/) | Define una interfaz de colección no genérica. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) es la interfaz base para todas las colecciones no genéricas que pueden enumerarse. |
| [IEnumerator](./ienumerator/) | Interfaz de enumerador que puede usarse para iterar a través de algunos elementos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que resultará en errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Envoltorio que crea una implementación no genérica [IEnumerator](./ienumerator/) sobre el Iterator genérico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - envoltorio para los tipos de referencia. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Envoltorio que crea una implementación no genérica [IEnumerator](./ienumerator/) sobre el Iterator genérico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - envoltorio para los tipos de valor. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Representa una colección no genérica de objetos que pueden ser accedidos individualmente por índice. |
| [IListImplRefType](./ilistimplreftype/) | Código de prueba que implementa la interfaz [System::Collections::IList](./ilist/) en el objeto [System::Collections::Generic::List](../system.collections.generic/list/) Implementación para tipos de referencia. |
| [IListImplValueType](./ilistimplvaluetype/) | Código de prueba que implementa la interfaz [System::Collections::IList](./ilist/) en el objeto [System::Collections::Generic::List](../system.collections.generic/list/) Implementación para tipos de valor. |
| [IListWrapper](./ilistwrapper/) | Interfaz para soportar la conversión de una colección genérica a una no genérica. |
| [Invalidatable](./invalidatable/) | Clase que permite rastrear el estado de sus descendientes mediante objetos [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Clase que implementa rastreadores de objetos [Invalidatable](./invalidatable/). |