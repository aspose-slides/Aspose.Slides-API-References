---
title: Default()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a hivatkozást a kivétel típusú egyetlen alapértelmezett konstrukcióval létrehozott példányra.
type: docs
weight: 2224
url: /hu/system/default/
---
## System::Default() függvény

Visszaadja a hivatkozást a kivétel típusú egyetlen alapértelmezett konstrukcióval létrehozott példányra.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az a típus, amelynek példánya visszatér |

## System::Default() függvény

Visszaadja a hivatkozást a nem-kivétel típusú egyetlen alapértelmezett konstrukcióval létrehozott példányra.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az a típus, amelynek példánya visszatér |

## Lásd még

* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)