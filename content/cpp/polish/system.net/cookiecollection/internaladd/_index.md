---
title: InternalAdd()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje określony plik cookie do kolekcji.
type: docs
weight: 118
url: /pl/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) metoda

Dodaje określony plik cookie do kolekcji.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Plik cookie do dodania. |
| isStrict | **bool** | True, gdy określony plik cookie musi zastąpić poprzedni, w przeciwnym razie false. |

### Wartość zwracana

0, gdy określony plik cookie zastąpił poprzedni, w przeciwnym razie 1.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Cookie](../../cookie/)
* Klasa [CookieCollection](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)