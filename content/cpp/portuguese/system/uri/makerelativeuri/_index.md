---
title: MakeRelativeUri()
second_title: Aspose.Slides para C++ Referência da API
description: Determina a diferença entre os URIs representados pelo objeto atual e pelos objetos Uri especificados.
type: docs
weight: 352
url: /pt/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) method


Determina a diferença entre os URIs representados pelo objeto atual e pelos objetos [Uri](../) especificados.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O comparando |

### Valor de Retorno

Se o nome do host e o esquema dos URIs representados pelo objeto atual e **toUri** forem os mesmos, este método retorna um [Uri](../) relativo que, ao ser anexado à instância de URI atual, produz **toUri**. Se o nome do host ou o esquema forem diferentes, este método retorna um objeto [Uri](../) que representa o parâmetro **uri**.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Uri](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)