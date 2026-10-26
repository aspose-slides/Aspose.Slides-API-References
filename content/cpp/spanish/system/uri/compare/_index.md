---
title: Compare()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara los objetos Uri especificados usando las reglas de comparación especificadas.
type: docs
weight: 521
url: /es/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) método


Compara los objetos [Uri](../) especificados usando las reglas de comparación especificadas.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El primer comparando |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El segundo comparando |
| partsToCompare | [UriComponents](../../uricomponents/) | Especifica las partes de **uri1** y **uri2** a comparar |
| compareFormat | [UriFormat](../../uriformat/) | Especifica el escape de caracteres usado cuando se comparan los componentes de URIs |
| comparisonType | [StringComparison](../../stringcomparison/) | Uno de los valores de StringComparison |

### Valor de retorno

Un valor negativo si **uri1** es menor que **uri2**; 0 si uri1 y uri2 son iguales; un valor positivo si **uri1** es mayor que **uri2**

## Ver también

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [Uri](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)