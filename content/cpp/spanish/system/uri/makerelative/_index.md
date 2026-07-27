---
title: MakeRelative()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina la diferencia entre dos instancias de Uri.
type: docs
weight: 365
url: /es/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) método

Determina la diferencia entre dos instancias de [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI a comparar con el URI actual |

### Valor devuelto

Si el nombre de host y el esquema de los URI representados por el objeto actual y **toUri** son los mismos, entonces este método devuelve un [String](../../string/) que representa un [Uri](../) relativo, que al agregarse a la instancia de URI actual produce **toUri**. Si el nombre de host o el esquema son diferentes, entonces este método devuelve un [String](../../string/) que representa el parámetro **uri**.

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Uri](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)