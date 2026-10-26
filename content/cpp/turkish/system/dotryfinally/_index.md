---
title: DoTryFinally()
second_title: Aspose.Slides için C++ API Referansı
description: C#'ın try[-catch]-finally ifadesinin davranışını taklit eden tek fonksiyon. Çevirmenin finally_statement_as_lambda seçeneği true olarak ayarlandığında C#'ın try[-catch]-finally ifadesi bu yöntemin çağrısına çevrilir.
type: docs
weight: 2445
url: /tr/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) fonksiyon


Deneme-yakalama-finally ifadesinin C#'daki davranışını taklit eden tek fonksiyon. Çevirmen seçeneği finally_statement_as_lambda true olarak ayarlandığında C#'daki try[-catch]-finally ifadesi bu yöntemin çağrısına çevrilir.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Emüle edilen try[-catch]-finally ifadesinin try[-catch] bölümünü uygulayan fonksiyon nesnesinin türü |
| F | Emüle edilen try[-catch]-finally ifadesinin finally bölümünü uygulayan fonksiyon nesnesinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tryBlock | T\&& | Emüle edilen try[-catch]-finally ifadesinin try[-catch] bölümünü uygulayan fonksiyon nesnesinin gövdesini içeren fonksiyon nesnesi |
| finallyBlock | F\&& | Emüle edilen try[-catch]-finally ifadesinin finally bölümünü uygulayan fonksiyon nesnesinin gövdesini içeren fonksiyon nesnesi |

## System::DoTryFinally(T\&&, F\&&) fonksiyon


Deneme-yakalama-finally ifadesinin C#'daki davranışını taklit eden tek fonksiyon. Çevirmen seçeneği finally_statement_as_lambda true olarak ayarlandığında C#'daki try[-catch]-finally ifadesi bu yöntemin çağrısına çevrilir. Bu aşırı yükleme, try[-catch]-finally ifadesinin try[-catch] kısmını uygulayan fonksiyon nesnesinin dönüş değerinin bool olduğu durumu ele alır.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Emüle edilen try[-catch]-finally ifadesinin try[-catch] bölümünü uygulayan fonksiyon nesnesinin türü |
| F | Emüle edilen try[-catch]-finally ifadesinin finally bölümünü uygulayan fonksiyon nesnesinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tryBlock | T\&& | Emüle edilen try[-catch]-finally ifadesinin try[-catch] bölümünü uygulayan fonksiyon nesnesinin gövdesini içeren fonksiyon nesnesi |
| finallyBlock | F\&& | Emüle edilen try[-catch]-finally ifadesinin finally bölümünü uygulayan fonksiyon nesnesinin gövdesini içeren fonksiyon nesnesi |

## System::DoTryFinally(T\&&, F\&&) fonksiyon


Deneme-yakalama-finally ifadesinin C#'daki davranışını taklit eden tek fonksiyon. Çevirmen seçeneği finally_statement_as_lambda true olarak ayarlandığında C#'daki try[-catch]-finally ifadesi bu yöntemin çağrısına çevrilir. Bu aşırı yükleme, try[-catch]-finally ifadesinin try[-catch] kısmını uygulayan fonksiyon nesnesinin dönüş değerinin bool& olduğu durumu ele alır.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Emüle edilen try[-catch]-finally ifadesinin try[-catch] bölümünü uygulayan fonksiyon nesnesinin türü |
| F | Emüle edilen try[-catch]-finally ifadesinin finally bölümünü uygulayan fonksiyon nesnesinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tryBlock | T\&& | Emüle edilen try[-catch]-finally ifadesinin try[-catch] bölümünü uygulayan fonksiyon nesnesinin gövdesini içeren fonksiyon nesnesi |
| finallyBlock | F\&& | Emüle edilen try[-catch]-finally ifadesinin finally bölümünü uygulayan fonksiyon nesnesinin gövdesini içeren fonksiyon nesnesi |

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)