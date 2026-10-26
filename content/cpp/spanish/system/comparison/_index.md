---
title: Comparison
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un puntero al método que compara dos objetos del mismo tipo. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 183
url: /es/system/comparison/
---
## Comparison clase


Representa un puntero al método que compara dos objetos del mismo tipo. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use [System::SmartPtr](../smartptr/) clase.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los objetos que el método compara |
## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Invoca el objeto invocable al que apunta el objeto actual. |
## Observaciones



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// La clase plantilla que representa una matriz dinámica.
template <typename T>
class MyArray
{
  // Utilizado para almacenar los datos de la matriz.
  std::vector<T> m_data;

public:
  // Construye una nueva instancia de nuestra matriz dinámica.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Utilizado para ordenar los datos de la matriz. Este método acepta una instancia de la
  // clase plantilla 'System::Comparison'.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Devuelve el número de elementos que almacena nuestra matriz dinámica.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Utilizado para obtener un elemento en el índice especificado.
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
  // Crea una instancia de la clase MyArray con los elementos especificados.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Ordena por elementos ascendentes de la matriz dinámica.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Imprime los elementos de la matriz dinámica.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
a
b
c
d
e
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)