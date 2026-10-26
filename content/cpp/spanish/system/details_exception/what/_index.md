---
title: what()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Implementa el método what() que es llamado por la clase ExceptionWrapper. A pesar de que esta clase no hereda de std::exception, las clases derivadas pueden usar miembros protected/private para implementar su lógica. Mover la implementación de este método a ExceptionWrapper puede romper esa lógica."
type: docs
weight: 105
url: /es/system/details_exception/what/
---
## Details_Exception::what() const método


Implementa el método [what()](./) que es llamado por la clase [ExceptionWrapper](../../exceptionwrapper/). A pesar de que esta clase no hereda de std::exception, las clases derivadas pueden usar miembros protected/private para implementar su lógica. Mover la implementación de este método al [ExceptionWrapper](../../exceptionwrapper/) puede romper esa lógica.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### Valor devuelto

La descripción de la excepción.

## Ver también

* Clase [Details_Exception](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)