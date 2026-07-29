---
title: get_Result()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar resultatet av den slutförda uppgiften.
type: docs
weight: 66
url: /sv/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() metod

Hämtar resultatet av den slutförda uppgiften.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Returvärde

T Resultatvärdet.

## Anmärkningar

Om uppgiften stöds av en ResultTask<T>, kommer denna metod att vänta på resultatet och cacha det. Efterföljande anrop kommer att returnera det cachade värdet utan att vänta.

## Se även

* Klass [ResultValueTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)