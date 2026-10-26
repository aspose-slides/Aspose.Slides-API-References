---
title: setter_wrap()
second_title: Referência da API Aspose.Slides para C++
description: Sobrecarga para funções setter estáticas com conversão de tipo.
type: docs
weight: 2822
url: /pt/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) função

Sobrecarga para funções setter estáticas com conversão de tipo.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor. |
| T2 | Tipo esperado pela função setter. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pSetter | void(*)(T2) | Referência de função setter estática. |
| value | T | Valor a definir. |

### Valor de Retorno

Define o valor.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) função

Sobrecarga para funções setter de instância com conversão de tipo.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor. |
| T2 | Tipo esperado pela função setter. |
| Host | Tipo de instância. |
| HostSet | - O próprio Host, ou seu tipo base, onde o setter da propriedade está definido. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | Host *const | [Object](../object/) para chamar a função setter. |
| pSetter | void(HostSet::*)(T2) | Referência de função setter. |
| value | T | Valor a definir. |

### Valor de Retorno

Define o valor.

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)