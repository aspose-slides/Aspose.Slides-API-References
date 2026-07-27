---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides para C++ Referência da API
description: O tradutor converte expressões de pós-decremento do C# que visam a propriedade de uma classe que possui setter e getter definidos, em uma invocação desta função.
type: docs
weight: 2874
url: /pt/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) função


O tradutor traduz expressões de pós-decremento do C# que visam a propriedade de uma classe que possui setter e getter definidos, em uma invocação desta função.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pGetter | T(*)() | Ponteiro de função apontando para a função livre getter da propriedade |
| pSetter | void(*)(T) | Ponteiro de função apontando para a função livre setter da propriedade |

### Valor de Retorno

O valor da propriedade antes de ser incrementado

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) função


O tradutor traduz expressões de pós-decremento do C# que visam a propriedade de uma instância que possui setter e getter definidos, em uma invocação desta função (sobrecarga para getter não const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade. |
| Host | - classe da instância a ser modificada |
| HostGet | - O próprio Host ou seu tipo base, onde o getter da propriedade está definido |
| HostSet | - O próprio Host ou seu tipo base, onde o setter da propriedade está definido |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | Host *const | Instância para a qual chamar getters e setters. |
| pGetter | T(HostGet::*)() | Ponteiro de função apontando para a função getter da propriedade |
| pSetter | void(HostSet::*)(T) | Ponteiro de função apontando para a função setter da propriedade |

### Valor de Retorno

O valor da propriedade antes de ser incrementado

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) função


O tradutor traduz expressões de pós-decremento do C# que visam a propriedade de uma instância que possui setter e getter definidos, em uma invocação desta função (sobrecarga para getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade. |
| Host | - classe da instância a ser modificada |
| HostConstGet | - O próprio Host ou seu tipo base, onde o getter da propriedade está definido |
| HostSet | - O próprio Host ou seu tipo base, onde o setter da propriedade está definido |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | Host *const | Instância para a qual chamar getters e setters. |
| pGetter | T(HostConstGet::*)() const | Ponteiro de função apontando para a função getter da propriedade |
| pSetter | void(HostSet::*)(T) | Ponteiro de função apontando para a função setter da propriedade |

### Valor de Retorno

O valor da propriedade antes de ser incrementado

## Veja Também

* Namespace [System](../)
* Library [Aspose.Slides](../../)