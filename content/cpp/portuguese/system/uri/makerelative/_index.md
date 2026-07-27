---
title: MakeRelative()
second_title: Aspose.Slides para C++ Referência da API
description: Determina a diferença entre duas instâncias de Uri.
type: docs
weight: 365
url: /pt/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) método


Determina a diferença entre duas instâncias de [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI a ser comparado com o URI atual |

### Valor de retorno

Se o nome do host e o esquema dos URIs representados pelo objeto atual e **toUri** forem os mesmos, então este método retorna um [String](../../string/) que representa um [Uri](../) relativo, quando anexado à instância de URI atual, produz **toUri**. Se o nome do host ou o esquema forem diferentes, então este método retorna um [String](../../string/) que representa o parâmetro **uri**.

## Veja também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)