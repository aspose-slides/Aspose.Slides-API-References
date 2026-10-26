---
title: BuildObject()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un objeto con propiedad compartida.
type: docs
weight: 2250
url: /es/system/buildobject/
---
## System::BuildObject(Args\&&...) función

Construir un objeto con propiedad compartida.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a construir |
| Args | Tipos de argumentos para la construcción del objeto |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos para reenviar al constructor del objeto |

### Valor de retorno

ObjectBuilder configurado para la construcción de punteros compartidos

## Observaciones

Crea un SharedPtr<T> y devuelve un generador para él  
[Object](../object/) la construcción debe finalizarse con la llamada [Get()](../get/)

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)