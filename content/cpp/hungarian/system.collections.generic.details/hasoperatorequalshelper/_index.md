---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides C++ API hivatkozás
description: Segédfüggvény annak meghatározására, hogy egy adott osztálynak van-e operator ==.
type: docs
weight: 235
url: /hu/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) függvény

Segédfüggvény annak meghatározására, hogy egy adott osztálynak van-e operator ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A vizsgálandó típus. |
| Dummy | Kitalált argumentum az SFINAE varázslathoz. |

### Visszatérési érték

std::true_type érték, ha az operator == jelen van, egyébként false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) függvény

Segédfüggvény annak meghatározására, hogy egy adott osztálynak van-e operator ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Visszatérési érték

std::true_type érték, ha az operator == jelen van, egyébként false.

## Lásd még

* Névterület [System::Collections::Generic::Details](../)
* Könyvtár [Aspose.Slides](../../)