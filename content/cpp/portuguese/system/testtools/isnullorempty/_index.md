---
title: IsNullOrEmpty()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a coleção é nula ou vazia.
type: docs
weight: 27
url: /pt/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) método

Verifica se a coleção é nula ou vazia.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo da coleção. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Coleção a ser verificada. |

### Valor de retorno

True se a coleção for nula ou tiver contagem de elementos zero, false caso contrário.

## TestTools::IsNullOrEmpty(const System::String\&) método

Verifica se a string é nula ou vazia.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) para verificação. |

### Valor de retorno

True se a string for nula ou tiver comprimento zero, false caso contrário.

## Veja também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)