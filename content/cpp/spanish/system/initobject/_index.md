---
title: InitObject()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicia la inicialización de un objeto con propiedad compartida.
type: docs
weight: 2263
url: /es/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) función

Inicia la inicialización de un objeto con propiedad compartida.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a inicializar |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) para inicializar |

### Valor devuelto

ObjectBuilder configurado para la construcción de punteros compartidos

## Observaciones

[Object](../object/) la inicialización debe terminarse con la llamada [Get()](../get/)

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)