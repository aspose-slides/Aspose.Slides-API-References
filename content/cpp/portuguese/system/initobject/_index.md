---
title: InitObject()
second_title: Referência da API do Aspose.Slides para C++
description: Inicia a inicialização de um objeto com propriedade compartilhada.
type: docs
weight: 2263
url: /pt/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) função


Inicia a inicialização de um objeto com propriedade compartilhada.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do objeto a ser inicializado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) a ser inicializado |

### Valor de retorno

ObjectBuilder configurado para construção de ponteiro compartilhado
## Observações



[Object](../object/) inicialização deve ser concluída com chamada [Get()](../get/)

## Veja Também

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)