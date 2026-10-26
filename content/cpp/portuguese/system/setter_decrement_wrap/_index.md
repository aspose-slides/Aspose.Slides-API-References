---
title: setter_decrement_wrap()
second_title: Referência da API Aspose.Slides para C++
description: O Tradutor traduz expressões de pré-decremento do C# direcionadas à propriedade da classe que tem setter e getter definidos, em invocação desta função.
type: docs
weight: 2861
url: /pt/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) função


O Tradutor traduz expressões de pré-decremento do C# direcionadas à propriedade de classe que possui setter e getter definidos, em invocação desta função.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Parâmetros de Template

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pGetter | T(*)() | Ponteiro de função apontando para a função livre getter da propriedade |
| pSetter | void(*)(T) | Ponteiro de função apontando para a função livre setter da propriedade |

### Valor de Retorno

O valor da propriedade antes de decrementá-la

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) função


O Tradutor traduz expressões de pré-decremento do C# direcionadas à propriedade da instância que possui setter e getter definidos, em invocação desta função (sobrecarga para getter não const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Parâmetros de Template

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade. |
| Host | - classe da instância a ser modificada |
| HostGet | - Host em si, ou seu tipo base, onde o getter da propriedade está definido |
| HostSet | - Host em si, ou seu tipo base, onde o setter da propriedade está definido |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | Host *const | Instância para a qual chamar getters e setters. |
| pGetter | T(HostGet::*)() | Ponteiro de função apontando para a função getter da propriedade |
| pSetter | void(HostSet::*)(T) | Ponteiro de função apontando para a função setter da propriedade |

### Valor de Retorno

O valor da propriedade antes de decrementá-la

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) função


O Tradutor traduz expressões de pré-decremento do C# direcionadas à propriedade da instância que possui setter e getter definidos, em invocação desta função (sobrecarga para getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Parâmetros de Template

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade. |
| Host | - classe da instância a ser modificada |
| HostConstGet | - Host em si, ou seu tipo base, onde o getter da propriedade está definido |
| HostSet | - Host em si, ou seu tipo base, onde o setter da propriedade está definido |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | Host *const | Instância para a qual chamar getters e setters. |
| pGetter | T(HostConstGet::*)() const | Ponteiro de função apontando para a função getter da propriedade |
| pSetter | void(HostSet::*)(T) | Ponteiro de função apontando para a função setter da propriedade |

### Valor de Retorno

O valor da propriedade antes de decrementá-la

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)