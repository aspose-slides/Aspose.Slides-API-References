---
title: setter_increment_wrap()
second_title: Referência da API Aspose.Slides para C++
description: O tradutor converte expressões de incremento do C# que visam a propriedade de uma classe que possui setter e getter definidos, em uma invocação desta função.
type: docs
weight: 2835
url: /pt/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) função

O tradutor traduz expressões de incremento do C# que visam a propriedade de uma classe que tem setter e getter definidos, em uma chamada desta função.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pGetter | T(*)() | Ponteiro de função que aponta para a função livre getter da propriedade |
| pSetter | void(*)(T) | Ponteiro de função que aponta para a função livre setter da propriedade |

### Valor de retorno

O valor incrementado da propriedade

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) função

O tradutor traduz expressões de incremento do C# que visam a propriedade de uma classe que tem setter e getter definidos, em uma chamada desta função.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo da propriedade |
| Host | - classe da instância a ser modificada |
| HostGet | - Host em si, ou seu tipo base, onde o getter da propriedade está definido |
| HostSet | - Host em si, ou seu tipo base, onde o setter da propriedade está definido |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | Host *const | Um ponteiro para um objeto cuja propriedade será incrementada |
| pGetter | T(HostGet::*)() | Ponteiro de função que aponta para o método getter da propriedade |
| pSetter | void(HostSet::*)(T) | Ponteiro de função que aponta para o método setter da propriedade |

### Valor de retorno

O valor incrementado da propriedade

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)