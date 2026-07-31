---
title: DoTryFinally()
second_title: Referensi API Aspose.Slides untuk C++
description: Fungsi tunggal yang meniru perilaku pernyataan try[-catch]-finally milik C#. Selama penerjemahan pernyataan try[-catch]-finally C# dengan opsi translator finally_statement_as_lambda disetel ke true, pernyataan tersebut diterjemahkan menjadi pemanggilan metode ini.
type: docs
weight: 2445
url: /id/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) fungsi


Fungsi tunggal yang meniru perilaku pernyataan try[-catch]-finally milik C#. Selama penerjemahan pernyataan try[-catch]-finally C# dengan opsi translator finally_statement_as_lambda disetel ke true, pernyataan tersebut diterjemahkan menjadi pemanggilan metode ini.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of the function object that implements the try[-catch] part of the try[-catch]-finally statement being emulated |
| F | The type of the function object that implements the finally part of the try[-catch]-finally statement being emulated |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tryBlock | T\&& | The function object whose body contains the implementation of the try[-catch] part of the try[-catch]-finally statemet being emulated |
| finallyBlock | F\&& | The function object whose body contains the implementation of the finally part of the try[-catch]-finally statement being emulated |

## System::DoTryFinally(T\&&, F\&&) fungsi


Fungsi tunggal yang meniru perilaku pernyataan try[-catch]-finally milik C#. Selama penerjemahan pernyataan try[-catch]-finally C# dengan opsi translator finally_statement_as_lambda disetel ke true, pernyataan tersebut diterjemahkan menjadi pemanggilan metode ini. Overload ini menangani kasus di mana nilai kembali dari objek fungsi yang mengimplementasikan bagian try[-catch] dari pernyataan try[-catch]-finally adalah bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of the function object that implements the try[-catch] part of the try[-catch]-finally statement being emulated |
| F | The type of the function object that implements the finally part of the try[-catch]-finally statement being emulated |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tryBlock | T\&& | The function object whose body contains the implementation of the try[-catch] part of the try[-catch]-finally statemet being emulated |
| finallyBlock | F\&& | The function object whose body contains the implementation of the finally part of the try[-catch]-finally statement being emulated |

## System::DoTryFinally(T\&&, F\&&) fungsi


Fungsi tunggal yang meniru perilaku pernyataan try[-catch]-finally milik C#. Selama penerjemahan pernyataan try[-catch]-finally C# dengan opsi translator finally_statement_as_lambda disetel ke true, pernyataan tersebut diterjemahkan menjadi pemanggilan metode ini. Overload ini menangani kasus di mana nilai kembali dari objek fungsi yang mengimplementasikan bagian try[-catch] dari pernyataan try[-catch]-finally adalah bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of the function object that implements the try[-catch] part of the try[-catch]-finally statement being emulated |
| F | The type of the function object that implements the finally part of the try[-catch]-finally statement being emulated |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tryBlock | T\&& | The function object whose body contains the implementation of the try[-catch] part of the try[-catch]-finally statemet being emulated |
| finallyBlock | F\&& | The function object whose body contains the implementation of the finally part of the try[-catch]-finally statement being emulated |

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)