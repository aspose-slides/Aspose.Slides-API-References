---
title: operator==()
second_title: Referência da API Aspose.Slides para C++
description: Operador de igualdade para ResultValueTask.
type: docs
weight: 131
url: /pt/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const método

Operador de igualdade para [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | O outro [ResultValueTask](../) para comparar com esta instância. |

### Valor de Retorno

bool True se ambas as tarefas têm o mesmo valor de resultado ou referenciam a mesma tarefa subjacente; caso contrário, false.

## Observações

Se alguma das instâncias contiver um valor de resultado direto, compara os resultados diretamente. Caso contrário, compara os ponteiros da tarefa subjacente. 

## Veja Também

* Classe [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)