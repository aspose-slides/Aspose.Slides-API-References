---
title: MemoryStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase MemoryStream con capacidad inicial igual a 0.
type: docs
weight: 1
url: /es/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() constructor


Construye una nueva instancia de la **clase** [MemoryStream](../) con capacidad inicial igual a 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) constructor


Construye una nueva instancia de la **clase** [MemoryStream](../) que representa un flujo basado en un búfer de memoria del tamaño especificado.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capacity_ | int | El tamaño en bytes de un búfer de memoria asociado al flujo representado por el objeto que se está creando |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) constructor


Construye una nueva instancia de la **clase** [MemoryStream](../) que representa un flujo de memoria conectado al búfer de memoria especificado. Un parámetro indica si el flujo es modificable.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Una matriz de bytes que se usará como búfer de memoria sobre el cual se basará el flujo representado por el objeto que se está creando |
| writable | **bool** | Indica si el flujo debe ser modificable |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) constructor


Construye una nueva instancia de la **clase** [MemoryStream](../) que representa un flujo de memoria conectado a un segmento del búfer de memoria especificado que comienza en el índice indicado e incluye el número especificado de elementos. Los parámetros indican si el flujo es modificable y si se puede llamar al método GetBytes().

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Una matriz de bytes cuyo segmento se usará como búfer de memoria sobre el cual se basará el flujo representado por el objeto que se está creando |
| index | int | Un índice basado en cero del elemento en **content** donde comienza el segmento |
| count | int | El número de elementos de **content** incluidos en el segmento |
| writable | **bool** | Indica si el flujo debe ser modificable |
| publiclyVisible | **bool** | Indica si el búfer de memoria subyacente debe ponerse a disposición del llamador del método GetByte() |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [MemoryStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)