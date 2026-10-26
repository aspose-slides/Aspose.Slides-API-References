---
title: SmartPtrInfo
second_title: Aspose.Slides para C++ Referência da API
description: Classe de serviço para testar e alterar o conteúdo do SmartPtr sem conhecer o tipo final. Usada para coleta de lixo e detecção de referências em loop, etc. Pense nisso como um 'ponteiro para ponteiro'. Não podemos usar o tipo base do SmartPtr pois ele não tem nenhum; ao invés disso, usamos esta classe 'info'.
type: docs
weight: 1249
url: /pt/system/smartptrinfo/
---
## SmartPtrInfo classe

Classe de serviço para testar e alterar o conteúdo de [SmartPtr](../smartptr/) sem conhecer o tipo final. Usada para coleta de lixo e detecção de referências em loop, etc. Pense nisso como um 'ponteiro para ponteiro'. Não podemos usar o tipo base de [SmartPtr](../smartptr/) pois ele não tem nenhum; ao invés disso, usamos esta classe 'info'.

```cpp
class SmartPtrInfo
```

## Métodos

| Method | Description |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Obtém o objeto bruto ao qual o ponteiro referenciado aponta. |
| [Object](../object/) * [getObject](./getobject/)() const | Obtém o objeto ao qual o ponteiro referenciado aponta. |
| [Object](../object/) * [getOwned](./getowned/)() const | Obtém o ponteiro proprietário do objeto. |
|  [operator bool](./operator_bool/)() const | Verifica se o objeto info aponta para um ponteiro não nulo. |
| **bool** [operator!](./operator_not/)() const | Verifica se o objeto info não aponta para um ponteiro não nulo. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Permite chamar métodos de [Object](../object/) apontado pelo ponteiro referenciado. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Compara menores os valores dos ponteiros referenciados por dois objetos info. |
|  [SmartPtrInfo](./smartptrinfo/)() | Cria um objeto [SmartPtrInfo](./) vazio. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Cria um objeto [SmartPtrInfo](./) com informações sobre um ponteiro inteligente específico. |
## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)