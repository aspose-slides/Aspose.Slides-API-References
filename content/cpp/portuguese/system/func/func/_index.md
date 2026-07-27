---
title: Func()
second_title: Referência da API Aspose.Slides para C++
description: Construtor padrão que cria null-Func.
type: docs
weight: 1
url: /pt/system/func/func/
---
## Func::Func() construtor

Construtor padrão que cria null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) construtor

Construtor que cria o objeto [Func](../) e atribui um valor (ou o callback real ou nullptr) a ele.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de argumento. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arg | T\&& | Argumento. |

## Func::Func(const Func\&) construtor

Construtor de cópia.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) para copiar dados de. |

## Func::Func(Func\&&) construtor

Construtor de movimentação.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) para mover dados de. |

## Veja Também

* Classe [Func](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)