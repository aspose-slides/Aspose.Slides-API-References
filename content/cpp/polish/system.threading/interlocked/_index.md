---
title: Interlocked
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Udostępnia interfejs API dla operacji bezpiecznych wątkowo. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 131
url: /pl/system.threading/interlocked/
---
## Klasa Interlocked

Udostępnia interfejs API dla operacji bezpiecznych wątkowo. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.

```cpp
class Interlocked
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Zwiększa wartość atomowo. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Zwiększa wartość atomowo. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Porównuje i wymienia wartość zmiennej: sprawdza, czy zmienna jest równa określonej wartości i zapisuje nową wartość tylko wtedy, gdy bieżąca wartość pasuje do oczekiwanej. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Porównuje i wymienia wartość zmiennej: sprawdza, czy zmienna jest równa określonej wartości i zapisuje nową wartość tylko wtedy, gdy bieżąca wartość pasuje do oczekiwanej. Nie zaimplementowano. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Porównuje i wymienia wartość zmiennej: sprawdza, czy zmienna jest równa określonej wartości i zapisuje nową wartość tylko wtedy, gdy bieżąca wartość pasuje do oczekiwanej. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Zmniejsza wartość atomowo. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Zmniejsza wartość atomowo. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Wymienia wartość zmiennej: zapisuje nową wartość i zwraca wartość zmiennej, którą miała natychmiast przed zapisem. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Wymienia wartość zmiennej: zapisuje nową wartość i zwraca wartość zmiennej, którą miała natychmiast przed zapisem. Nie zaimplementowano. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Zwiększa wartość atomowo przy użyciu procedury wymiany-dodawania. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Zwiększa wartość atomowo przy użyciu procedury wymiany-dodawania. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Zwiększa wartość atomowo. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Zwiększa wartość atomowo. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Zwraca 64-bitową wartość, wczytaną jako operacja atomowa. |

## Zobacz także

* Przestrzeń nazw [System::Threading](../)
* Biblioteka [Aspose.Slides](../../)