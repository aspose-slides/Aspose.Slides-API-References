---
title: PrintTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.
type: docs
weight: 2146
url: /id/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) fungsi

Menulis nilai yang direpresentasikan oleh objek tertentu ke aliran output yang ditentukan.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | [Decimal](../decimal/) objek untuk mencetak ke aliran |
| os | ::std::ostream * | Aliran untuk mencetak objek yang ditentukan ke |

## System::PrintTo(const Details_Exception\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) fungsi

Mencetak string ke ostream. Umumnya digunakan untuk debugging.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [System::String](../string/)\& | untuk dicetak. |
| os | std::ostream * | ostream target. |

## System::PrintTo(TimeSpan, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) fungsi

Mencetak nilai ke ostream. Umumnya digunakan untuk debugging.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Lihat Juga

* Kelas [DateTime](../datetime/)
* Kelas [DateTimeOffset](../datetimeoffset/)
* Kelas [Decimal](../decimal/)
* Kelas [Details_Exception](../details_exception/)
* Kelas [ExceptionWrapper](../exceptionwrapper/)
* Kelas [Guid](../guid/)
* Kelas [Nullable](../nullable/)
* Kelas [Object](../object/)
* Kelas [SmartPtr](../smartptr/)
* Kelas [String](../string/)
* Kelas [TimeSpan](../timespan/)
* Kelas [WeakPtr](../weakptr/)
* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)