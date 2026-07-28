---
title: Join()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Łączy tablicę przy użyciu łańcucha jako separatora.
type: docs
weight: 846
url: /pl/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) metoda


Łączy tablicę przy użyciu łańcucha jako separatora.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) do umieszczenia pomiędzy elementami tablicy przy ich łączeniu. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) części do połączenia. |
| startIndex | int | Pierwszy indeks w tablicy, od którego rozpocząć łączenie. |
| count | int | Liczba elementów tablicy do połączenia. -1 oznacza „do końca tablicy”. |

### Wartość zwracana

[String](../) reprezentująca połączone elementy tablicy.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) metoda


Łączy tablicę przy użyciu łańcucha jako separatora.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) do umieszczenia pomiędzy elementami tablicy przy ich łączeniu. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView części do połączenia. |
| startIndex | int | Pierwszy indeks w tablicy, od którego rozpocząć łączenie. |
| count | int | Liczba elementów tablicy do połączenia. -1 oznacza „do końca tablicy”. |

### Wartość zwracana

[String](../) reprezentująca połączone elementy tablicy.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) metoda


Łączy tablicę przy użyciu łańcucha jako separatora.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) do umieszczenia pomiędzy elementami tablicy przy ich łączeniu. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - obiekt wyliczający części |

### Wartość zwracana

[String](../) reprezentująca połączone elementy.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) metoda


Łączy tablicę przy użyciu łańcucha jako separatora.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) do umieszczenia pomiędzy elementami tablicy przy ich łączeniu. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) części do połączenia. |

### Wartość zwracana

[String](../) reprezentująca połączone elementy.

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasa [Object](../../object/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)