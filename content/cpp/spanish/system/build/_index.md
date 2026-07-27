---
title: Build()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un objeto con propiedad directa.
type: docs
weight: 2289
url: /es/system/build/
---
## System::Build(Args\&&...) function


Construye un objeto con propiedad directa.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a construir |
| Args | Tipos de argumentos para la construcción del objeto |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos que se reenviarán al constructor del objeto |

### Valor de retorno

ObjectBuilder configurado para la construcción directa de objetos
## Observaciones



[Object](../object/) la construcción debe finalizarse con la llamada [Get()](../get/) 

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)