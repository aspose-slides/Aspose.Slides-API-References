---
title: Comparison
second_title: Referência da API Aspose.Slides para C++
description: "Representa um ponteiro para o método que compara dois objetos do mesmo tipo. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 183
url: /pt/system/comparison/
---
## Classe Comparison

Representa um ponteiro para o método que compara dois objetos do mesmo tipo. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos desse tipo.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos objetos que o método compara |

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Invoca o objeto invocável apontado pelo objeto atual. |

## Observações

```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// A classe template que representa um array dinâmico.
template <typename T>
class MyArray
{
  // Usado para armazenar os dados do array.
  std::vector<T> m_data;

public:
  // Constrói uma nova instância do nosso array dinâmico.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Usado para ordenar os dados do array. Este método aceita uma instância da
  // classe template 'System::Comparison'.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Retorna o número de elementos que nosso array dinâmico armazena.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Usado para obter um elemento no índice especificado.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // Cria uma instância da classe MyArray com os elementos especificados.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Ordena pelos elementos em ordem crescente do array dinâmico.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Imprime os elementos do array dinâmico.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
a
b
c
d
e
*/
```

## Ver também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)