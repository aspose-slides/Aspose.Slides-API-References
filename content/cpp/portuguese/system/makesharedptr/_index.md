---
title: MakeSharedPtr()
second_title: Referência da API Aspose.Slides para C++
description: Converte ponteiro bruto em ponteiro inteligente.
type: docs
weight: 2900
url: /pt/system/makesharedptr/
---
## System::MakeSharedPtr(X *) função


Converte ponteiro bruto em ponteiro inteligente.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | Tipo do objeto apontado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| p | X * | Ponteiro bruto para o objeto. |

### Valor de Retorno

Ponteiro inteligente compartilhado para o objeto.

## System::MakeSharedPtr(const X *) função


Converte ponteiro bruto em ponteiro inteligente. Sobrecarga para ponteiros const. Útil, por exemplo, ao usar a variável 'this' em métodos C# traduzidos como const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | Tipo do objeto apontado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| p | const X * | Ponteiro bruto para o objeto. |

### Valor de Retorno

Ponteiro inteligente compartilhado para o objeto.

## Veja Também

* Classe [SmartPtr](../smartptr/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)