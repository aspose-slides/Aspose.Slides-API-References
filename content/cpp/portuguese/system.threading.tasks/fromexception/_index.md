---
title: FromException()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma tarefa que foi concluída com uma exceção especificada.
type: docs
weight: 131
url: /pt/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) function

Cria uma tarefa que foi concluída com uma exceção especificada.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | A exceção com a qual a tarefa será concluída. |

### Valor de Retorno

Uma tarefa com falha.

## System::Threading::Tasks::FromException(const Exception\&) function

Cria uma tarefa que foi concluída com uma exceção especificada e tipo de resultado.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| TResult | O tipo do resultado da tarefa. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | A exceção com a qual a tarefa será concluída. |

### Valor de Retorno

Uma tarefa com falha com o tipo de resultado especificado.

## Ver Também

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)