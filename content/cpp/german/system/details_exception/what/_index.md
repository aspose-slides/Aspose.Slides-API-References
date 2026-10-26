---
title: what()
second_title: Aspose.Slides für C++ API-Referenz
description: "Implementiert die what() Methode, die von der Klasse ExceptionWrapper aufgerufen wird. Trotz der Tatsache, dass diese Klasse nicht von std::exception erbt, können abgeleitete Klassen geschützte/privatrechte Member verwenden, um ihre Logik zu implementieren. Das Verschieben dieser Methodenimplementierung zur ExceptionWrapper kann diese Logik brechen."
type: docs
weight: 105
url: /de/system/details_exception/what/
---
## Details_Exception::what() const Methode

Implementiert [what()](./) Methode, die von [ExceptionWrapper](../../exceptionwrapper/) Klasse aufgerufen wird. Trotz der Tatsache, dass diese Klasse nicht von std::exception geerbt ist, können abgeleitet Klassen protected/private Member verwenden, um ihre Logik zu implementieren. Das Verschieben dieser Methodenimplementierung zu [ExceptionWrapper](../../exceptionwrapper/) kann diese Logik brechen.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### Rückgabewert

Die Beschreibung der Ausnahme.

## Siehe auch

* Klasse [Details_Exception](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)