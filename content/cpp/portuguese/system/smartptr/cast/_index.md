---
title: Cast()
second_title: Referência da API Aspose.Slides para C++
description: Converte o ponteiro para o seu próprio tipo.
type: docs
weight: 287
url: /pt/system/smartptr/cast/
---
## SmartPtr::Cast() const método

Converte o ponteiro para o seu próprio tipo.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Y | Tipo alvo do objeto apontado. |
| Check | Bandeiras para lançar exceção se nenhuma conversão estiver disponível. |

### Valor de retorno

Ponteiro de tipo alterado que está sempre no modo compartilhado.

## SmartPtr::Cast() const método

Converte o ponteiro para o tipo base usando static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Y | Tipo alvo do objeto apontado. |
| Check | Bandeiras para lançar exceção se nenhuma conversão estiver disponível. |

### Valor de retorno

Ponteiro de tipo alterado que está sempre no modo compartilhado.

## SmartPtr::Cast() const método

Converte o ponteiro para o tipo derivado dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Y | Tipo alvo do objeto apontado. |
| Check | Bandeiras para lançar exceção se nenhuma conversão estiver disponível. |

### Valor de retorno

Ponteiro de tipo alterado que está sempre no modo compartilhado. Lança InvalidCastException se nenhuma conversão estiver disponível.

## SmartPtr::Cast() const método

Converte o ponteiro para o tipo derivado dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Y | Tipo alvo do objeto apontado. |
| Check | Bandeiras para lançar exceção se nenhuma conversão estiver disponível. |

### Valor de retorno

Ponteiro de tipo alterado que está sempre no modo compartilhado. Retorna nullptr se nenhuma conversão estiver disponível.

## Veja Também

* Classe [SmartPtr](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)