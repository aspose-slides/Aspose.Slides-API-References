---
title: idx_get()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca ciasteczko z kolekcji ciasteczek w określonym indeksie.
type: docs
weight: 40
url: /pl/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) metoda

Zwraca ciasteczko z kolekcji ciasteczek w podanym indeksie.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks ciasteczka, które ma zostać zwrócone. |

### Wartość zwracana

Ciasteczko w podanym indeksie.

## CookieCollection::idx_get(String) metoda

Zwraca ciasteczko z kolekcji ciasteczek o podanej nazwie.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa ciasteczka, które ma zostać zwrócone. |

### Wartość zwracana

Ciasteczko z kolekcji ciasteczek o podanej nazwie, jeśli zostanie znalezione; w przeciwnym razie nullptr.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)