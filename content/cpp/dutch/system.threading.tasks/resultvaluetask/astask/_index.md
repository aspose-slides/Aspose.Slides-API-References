---
title: AsTask()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert dit ResultValueTask naar een gedeelde pointer naar ResultTask<T>.
type: docs
weight: 79
url: /nl/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const methode


Converteert deze [ResultValueTask](../) naar een gedeelde pointer naar ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Retourwaarde

RTaskPtr<T> Een gedeelde pointer naar ResultTask<T> die deze bewerking vertegenwoordigt.
## Opmerkingen



Als de [ResultValueTask](../) een direct resultaat bevat, maakt een voltooide taak aan met dat resultaat. Als het een taak bevat, retourneert een gedeelde pointer naar die taak. 

## Zie ook

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasse [ResultValueTask](../)
* Naamruimte [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)