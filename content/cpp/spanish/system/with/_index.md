---
title: With()
second_title: Referencia de API de Aspose.Slides para C++
description: Clona el registro de referencia y le aplica el functor de inicialización.
type: docs
weight: 2614
url: /es/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) function

Clona el registro de referencia y aplica el functor de inicialización.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de registro a clonar. |
| A | Tipo de functor de inicialización. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Puntero compartido al objeto a clonar e inicializar. |
| initializer | const A\& | Functor de inicialización aplicado al clon del registro. |

### Valor de retorno

Puntero compartido al registro clonado.

## System::With(const T\&, const A\&) function

Copia el registro de estructura y aplica el functor de inicialización.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de registro a copiar. |
| A | Tipo de functor de inicialización. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | const T\& | Registro a copiar e inicializar. |
| initializer | const A\& | Functor de inicialización aplicado a la copia del registro. |

### Valor de retorno

Registro copiado.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Espacio de nombres [System](../)
* Library [Aspose.Slides](../../)