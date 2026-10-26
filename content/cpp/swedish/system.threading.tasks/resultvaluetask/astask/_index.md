---
title: AsTask()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar detta ResultValueTask till en delad pekare till ResultTask<T>.
type: docs
weight: 79
url: /sv/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const metod


Konverterar detta [ResultValueTask](../) till en delad pekare till ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Returvärde

RTaskPtr<T> En delad pekare till en ResultTask<T> som representerar denna operation.
## Anmärkningar



Om [ResultValueTask](../) innehåller ett direkt resultat, skapar ett slutfört uppdrag med det resultatet. Om det innehåller ett uppdrag, returnerar en delad pekare till den uppgiften. 

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klass [ResultValueTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)