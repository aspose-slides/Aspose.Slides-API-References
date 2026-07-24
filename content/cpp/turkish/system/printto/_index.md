---
title: PrintTo()
second_title: Aspose.Slides için C++ API Referansı
description: Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.
type: docs
weight: 2146
url: /tr/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) fonksiyon


Belirtilen nesnenin temsil ettiği değeri belirtilen çıkış akışına yazar.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Akışa yazdırılacak [Decimal](../decimal/) nesnesi |
| os | ::std::ostream * | Belirtilen nesnenin yazdırılacağı akış |

## System::PrintTo(const Details_Exception\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) fonksiyon


Dizgeyi ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [System::String](../string/)\& | yazdırılacak değer. |
| os | std::ostream * | hedef ostream. |

## System::PrintTo(TimeSpan, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) fonksiyon


Değeri ostream'e yazar. Çoğunlukla hata ayıklama için kullanılır.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Ayrıca Bakınız

* Sınıf [DateTime](../datetime/)
* Sınıf [DateTimeOffset](../datetimeoffset/)
* Sınıf [Decimal](../decimal/)
* Sınıf [Details_Exception](../details_exception/)
* Sınıf [ExceptionWrapper](../exceptionwrapper/)
* Sınıf [Guid](../guid/)
* Sınıf [Nullable](../nullable/)
* Sınıf [Object](../object/)
* Sınıf [SmartPtr](../smartptr/)
* Sınıf [String](../string/)
* Sınıf [TimeSpan](../timespan/)
* Sınıf [WeakPtr](../weakptr/)
* Ad alanı [System](../)
* Library [Aspose.Slides](../../)