---
title: MakeRelativeUri()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina la diferencia entre los URIs representados por el objeto actual y los objetos Uri especificados.
type: docs
weight: 352
url: /es/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) método

Determina la diferencia entre los URIs representados por el objeto actual y los objetos [Uri](../) especificados.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El comparando |

### Valor devuelto

Si el nombre de host y el esquema de los URIs representados por el objeto actual y **toUri** son los mismos, entonces este método devuelve un [Uri](../) relativo que, al añadirse a la instancia actual de URI, produce **toUri**. Si el nombre de host o el esquema son diferentes, entonces este método devuelve un objeto [Uri](../) que representa el parámetro **uri**.

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Uri](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)