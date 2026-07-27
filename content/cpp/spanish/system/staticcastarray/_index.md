---
title: StaticCastArray()
second_title: Referencia de la API de Aspose.Slides para C++
description: Realiza el casting de los elementos de la matriz especificada a un tipo diferente. Sobrescribe para los casos en los que From es un objeto SmartPtr.
type: docs
weight: 2978
url: /es/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) función


Realiza el casting de los elementos de la matriz especificada a un tipo diferente. Sobrescribe para los casos en los que From es [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se convierten los elementos de la matriz especificada |
| From | El tipo de los elementos de la matriz cuyos elementos se van a convertir |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Puntero compartido a la matriz que contiene los elementos a convertir |

### Valor devuelto

Un puntero a una nueva matriz que contiene elementos del tipo **To** equivalentes a los elementos de **from**

Deprecated
:   Added for backward compatibility. Use ExplicitCast instead.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) función


Realiza el casting de los elementos de la matriz especificada a un tipo diferente. Sobrescribe para los casos en los que From es Boxable y To es [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se convierten los elementos de la matriz especificada |
| From | El tipo de los elementos de la matriz cuyos elementos se van a convertir |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Puntero compartido a la matriz que contiene los elementos a convertir |

### Valor devuelto

Un puntero a una nueva matriz que contiene elementos del tipo **To** equivalentes a los elementos de **from**

Deprecated
:   Added for backward compatibility. Use ExplicitCast instead.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Clase [Array](../array/)
* Clase [Object](../object/)
* Estructura [IsSmartPtr](../issmartptr/)
* Estructura [IsBoxable](../isboxable/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)