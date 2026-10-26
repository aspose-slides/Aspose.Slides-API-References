---
title: Handle()
second_title: Referencia de API de Aspose.Slides para C++
description: Invoca una función manejadora en cada excepción interna y vuelve a lanzar cualquier excepción no controlada.
type: docs
weight: 66
url: /es/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) method

Invoca una función manejadora en cada excepción interna y vuelve a lanzar cualquier excepción no controlada.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Una función que recibe una Exception y devuelve true si está manejada. |
## Observaciones

Si todas las excepciones están controladas, el método devuelve normalmente; de lo contrario, se lanza una nueva AggregateException que contiene las excepciones no controladas.

## Ver también

* Typedef [Exception](../../exception/)
* Clase [Func](../../func/)
* Clase [Details_AggregateException](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)