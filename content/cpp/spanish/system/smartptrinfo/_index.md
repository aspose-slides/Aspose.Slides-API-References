---
title: SmartPtrInfo
second_title: Referencia de la API de Aspose.Slides para C++
description: "Clase de servicio para probar y alterar los contenidos de SmartPtr sin conocer el tipo final. Se usa para recolección de basura y detección de referencias en bucles, etc. Piense en ella como un 'puntero a puntero'. No podemos usar el basetype de SmartPtr porque no tiene ninguno; en su lugar, usamos esta clase 'info'."
type: docs
weight: 1249
url: /es/system/smartptrinfo/
---
## SmartPtrInfo clase

Service clase para probar y alterar los contenidos de [SmartPtr](../smartptr/) sin conocer el tipo final. Se usa para recolección de basura y detección de referencias en bucle, etc. Piensa en ella como un "puntero a puntero". No podemos usar el basetype de [SmartPtr](../smartptr/) porque no tiene ninguno; en su lugar, usamos esta clase "info".

```cpp
class SmartPtrInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Obtiene el puntero crudo al objeto referenciado. |
| [Object](../object/) * [getObject](./getobject/)() const | Obtiene el objeto al que apunta el puntero referenciado. |
| [Object](../object/) * [getOwned](./getowned/)() const | Obtiene el puntero al objeto poseído. |
|  [operator bool](./operator_bool/)() const | Comprueba si el objeto info apunta a un puntero no nulo. |
| **bool** [operator!](./operator_not/)() const | Comprueba si el objeto info no apunta a un puntero no nulo. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Permite llamar a los métodos de [Object](../object/) apuntado por el puntero referenciado. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Compara menores los valores de los punteros referenciados por dos objetos info. |
|  [SmartPtrInfo](./smartptrinfo/)() | Crea un objeto [SmartPtrInfo](./) vacío. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Crea un objeto [SmartPtrInfo](./) con información sobre un puntero inteligente específico. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)