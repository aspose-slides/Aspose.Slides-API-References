---
title: CastEnumerableTo()
second_title: Aspose.Slides para C++ Referência da API
description: Realiza a conversão explícita dos elementos do objeto enumerable especificado para um tipo diferente.
type: docs
weight: 2965
url: /pt/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) função


Realiza a conversão explícita dos elementos do objeto enumerable especificado para um tipo diferente.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| To | O tipo ao qual os elementos do objeto enumerable devem ser convertidos estaticamente |
| From | O tipo do objeto enumerable |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| enumerable | const From\& | Objeto enumerable contendo os elementos a serem convertidos |

### Valor de retorno

Um ponteiro para uma nova coleção contendo elementos do tipo **To** equivalentes aos elementos de **enumerable**


## System::CastEnumerableTo(const From\&) função


Realiza a conversão explícita dos elementos do objeto enumerable especificado para um tipo diferente.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| To | O tipo ao qual os elementos do objeto enumerable devem ser convertidos estaticamente |
| From | O tipo do objeto enumerable |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| enumerable | const From\& | é um herdeiro de objeto Enumerable com método get_Count definido e contendo os elementos a serem convertidos |

### Valor de retorno

Um ponteiro para uma nova coleção contendo elementos do tipo **To** equivalentes aos elementos de **enumerable**


## Veja também

* Classe [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)