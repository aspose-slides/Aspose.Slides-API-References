---
title: PrintTo()
second_title: Aspose.Slides C++ API Referencia
description: Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.
type: docs
weight: 2146
url: /hu/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) függvény

Kiírja a megadott objektum által képviselt értéket a megadott kimeneti stream-be.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | A [Decimal](../decimal/) objektum, amelyet a stream-be kell kiírni |
| os | ::std::ostream * | A stream, amelyre a megadott objektumot ki kell írni |

## System::PrintTo(const Details_Exception\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) függvény

Kiírja a karakterláncot egy ostream-re. Leginkább hibakereséshez használják.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::String](../string/)\& | a kiírandó |
| os | std::ostream * | cél ostream |

## System::PrintTo(TimeSpan, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) függvény

Kiírja az értéket egy ostream-re. Leginkább hibakereséshez használják.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Lásd még

* Osztály [DateTime](../datetime/)
* Osztály [DateTimeOffset](../datetimeoffset/)
* Osztály [Decimal](../decimal/)
* Osztály [Details_Exception](../details_exception/)
* Osztály [ExceptionWrapper](../exceptionwrapper/)
* Osztály [Guid](../guid/)
* Osztály [Nullable](../nullable/)
* Osztály [Object](../object/)
* Osztály [SmartPtr](../smartptr/)
* Osztály [String](../string/)
* Osztály [TimeSpan](../timespan/)
* Osztály [WeakPtr](../weakptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)