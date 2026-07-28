---
title: With()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Klonuje rekord referencyjny i stosuje funktor inicjalizatora do niego.
type: docs
weight: 2614
url: /pl/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) funkcja


Klonuje rekord referencyjny i stosuje funktor inicjalizatora do niego.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ rekordu do sklonowania. |
| A | Typ funktora inicjalizatora. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Wskaźnik współdzielony na obiekt do sklonowania i inicjalizacji. |
| initializer | const A\& | Funktor inicjalizatora stosowany do klonu rekordu. |

### Wartość zwracana

Wskaźnik współdzielony do sklonowanego rekordu.

## System::With(const T\&, const A\&) funkcja


Kopiuje rekord struktury i stosuje funktor inicjalizatora do niego.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ rekordu do skopiowania. |
| A | Typ funktora inicjalizatora. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| record | const T\& | Rekord do skopiowania i inicjalizacji. |
| initializer | const A\& | Funktor inicjalizatora stosowany do kopii rekordu. |

### Wartość zwracana

Skopiowany rekord.

## Zobacz także

* Definicja typu [SharedPtr](../sharedptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)