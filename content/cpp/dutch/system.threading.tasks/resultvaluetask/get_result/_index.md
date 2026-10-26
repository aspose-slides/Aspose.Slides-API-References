---
title: get_Result()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt het resultaat van de voltooide taak op.
type: docs
weight: 66
url: /nl/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() methode


Haalt het resultaat van de voltooide taak op.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```


### Retourwaarde

T De resultaatwaarde.
## Opmerkingen



Als de taak wordt ondersteund door een ResultTask<T>, zal deze methode wachten op het resultaat en dit cachen. Volgende aanroepen retourneren de gecachte waarde zonder te wachten. 

## Zie ook

* Klasse [ResultValueTask](../)
* Naamruimte [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)