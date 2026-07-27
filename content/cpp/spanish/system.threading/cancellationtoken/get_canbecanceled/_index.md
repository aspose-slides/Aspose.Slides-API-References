---
title: get_CanBeCanceled()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene si este token es capaz de estar en el estado cancelado.
type: docs
weight: 27
url: /es/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled() const método


Obtiene si este token es capaz de estar en estado cancelado.

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```


### Valor de retorno

true si este token es capaz de estar en estado cancelado; de lo contrario, false.
## Observaciones



Los tokens creados a partir de [CancellationTokenSource](../../cancellationtokensource/) devolverán true, mientras que el token None siempre devolverá false. 

## Ver también

* Clase [CancellationToken](../)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)