---
title: GetEnvironmentVariable()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor da variável de ambiente especificada associada ao processo atual.
type: docs
weight: 287
url: /pt/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) método


Retorna o valor da variável de ambiente especificada associada ao processo atual.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| variable | const [String](../../string/)\& | A string que contém o nome da variável a ser recuperada |

### Valor de Retorno

O valor da variável especificada

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) método


Retorna o valor da variável de ambiente especificada a partir da localização especificada.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| variable | const [String](../../string/)\& | A string que contém o nome da variável a ser recuperada |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | A localização da variável |

### Valor de Retorno

O valor da variável especificada

## Veja Também

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Classe [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)