---
title: Add()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje ciasteczko do kolekcji.
type: docs
weight: 105
url: /pl/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) metoda

Dodaje ciasteczko do kolekcji.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Ciasteczko do dodania. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) metoda

Dodaje ciasteczko do kolekcji.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Ciasteczko do dodania. |
| throwOnError | **bool** | Wartość wskazująca, czy przy wystąpieniu błędu zostanie wyrzucony wyjątek. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) metoda

Kopiuje ciasteczka z określonej kolekcji do bieżącej.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Kolekcja, z której ciasteczka zostaną skopiowane. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) metoda

Dodaje ciasteczko dla określonego URI.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ciasteczka. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Ciasteczko do dodania. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) metoda

Kopiuje ciasteczka z określonej kolekcji dla podanego URI do bieżącej kolekcji.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ciasteczka. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Kolekcja ciasteczek, z której należy skopiować. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Cookie](../../cookie/)
* Klasa [CookieContainer](../)
* Klasa [CookieCollection](../../cookiecollection/)
* Klasa [Uri](../../../system/uri/)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)