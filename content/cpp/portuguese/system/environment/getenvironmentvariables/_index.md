---
title: GetEnvironmentVariables()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um dicionário contendo todos os nomes das variáveis de ambiente e seus valores associados ao processo atual.
type: docs
weight: 326
url: /pt/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() método


Retorna um dicionário contendo todos os nomes das variáveis de ambiente e seus valores associados ao processo atual.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) método


Retorna um dicionário contendo todos os nomes das variáveis de ambiente e seus valores a partir do local especificado.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | O local das variáveis |

### Valor de Retorno

Um dicionário contendo todos os nomes das variáveis de ambiente e seus valores a partir do local especificado

## Veja Também

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Classe [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Classe [String](../../string/)
* Struct [Environment](../)
* namespace [System](../../)
* Library [Aspose.Slides](../../../)