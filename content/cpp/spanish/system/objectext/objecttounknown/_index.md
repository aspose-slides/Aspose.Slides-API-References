---
title: ObjectToUnknown()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte Object a tipo desconocido, manejando tanto el tipo de puntero inteligente como situaciones de valor empaquetado.
type: docs
weight: 131
url: /es/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) método

Convierte [Object](../../object/) a tipo desconocido, manejando tanto el tipo de puntero inteligente como situaciones de valor empaquetado.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que convertir [Object](../../object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) a convertir. |

### Valor de retorno

Ya sea un valor sin empaquetar o un puntero convertido.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) método

Convierte [Object](../../object/) a tipo desconocido, manejando tanto el tipo de puntero inteligente como situaciones de valor empaquetado.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que convertir [Object](../../object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) a convertir. |

### Valor de retorno

Ya sea un valor sin empaquetar o un puntero convertido.

## Ver también

* Clase [SmartPtr](../../smartptr/)
* Clase [Object](../../object/)
* Clase [ObjectExt](../)
* Estructura [IsSmartPtr](../../issmartptr/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)