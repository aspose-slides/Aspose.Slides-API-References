---
title: With()
second_title: Referência da API Aspose.Slides para C++
description: Clona o registro de referência e aplica o functor inicializador a ele.
type: docs
weight: 2614
url: /pt/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) função

Clona o registro de referência e aplica o functor inicializador a ele.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Tipo de registro a ser clonado. |
| A | Tipo do functor de inicialização. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Ponteiro compartilhado para o objeto a ser clonado e inicializado. |
| initializer | const A\& | Functor de inicialização aplicado ao clone do registro. |

### Valor de retorno

Ponteiro compartilhado para o registro clonado.

## System::With(const T\&, const A\&) função

Copia o registro da struct e aplica o functor inicializador a ele.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Tipo de registro a ser copiado. |
| A | Tipo do functor de inicialização. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| record | const T\& | Registro a ser copiado e inicializado. |
| initializer | const A\& | Functor de inicialização aplicado à cópia do registro. |

### Valor de retorno

Registro copiado.

## Veja Também

* Typedef [SharedPtr](../sharedptr/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)