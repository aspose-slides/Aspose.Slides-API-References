---
title: operator<()
second_title: Referência da API Aspose.Slides para C++
description: Fornece semântica de comparação menor para a classe SmartPtr.
type: docs
weight: 235
url: /pt/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const método

Fornece semântica de comparação menor para a classe [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| Y | Tipo de ponteiro para comparar o atual. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| p | Y * | Ponteiro para comparar o atual. |

### Valor de Retorno

Verdadeiro se o objeto referenciado por [SmartPtr](../) for 'menor' que p e falso caso contrário.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const método

Fornece semântica de comparação menor para a classe [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| Y | Tipo de ponteiro para comparar o atual. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Ponteiro para comparar o atual. |

### Valor de Retorno

Verdadeiro se o objeto referenciado por [SmartPtr](../) for 'menor' que x e falso caso contrário.

## Veja Também

* Classe [SmartPtr](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)