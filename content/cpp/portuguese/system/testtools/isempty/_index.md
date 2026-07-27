---
title: IsEmpty()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a string está vazia.
type: docs
weight: 14
url: /pt/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) método

Verifica se a string está vazia.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) to check for being empty. |

### Valor de Retorno

True se a string estiver vazia (null-length), false caso contrário.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) método

Verifica se a coleção está vazia.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Collection type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collection to check. |

### Valor de Retorno

True se a coleção tiver contagem de elementos zero, false caso contrário.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Estrutura [TestTools](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)