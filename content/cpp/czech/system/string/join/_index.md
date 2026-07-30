---
title: Join()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Spojí pole pomocí řetězce jako oddělovače.
type: docs
weight: 846
url: /cs/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) metoda


Spojí pole pomocí řetězce jako oddělovače.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) k umístění mezi prvky pole při spojování. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) částí k spojení. |
| startIndex | int | První index v poli, od kterého začít spojování. |
| count | int | Počet prvků pole, které se mají spojit. -1 znamená 'do konce pole'. |

### Návratová hodnota

[String](../) představující spojené prvky pole.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) metoda


Spojí pole pomocí řetězce jako oddělovače.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) k umístění mezi prvky pole při spojování. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView částí k spojení. |
| startIndex | int | První index v poli, od kterého začít spojování. |
| count | int | Počet prvků pole, které se mají spojit. -1 znamená 'do konce pole'. |

### Návratová hodnota

[String](../) představující spojené prvky pole.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) metoda


Spojí pole pomocí řetězce jako oddělovače.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) k umístění mezi prvky pole při spojování. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - výčtový objekt částí |

### Návratová hodnota

[String](../) představující spojené prvky.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) metoda


Spojí pole pomocí řetězce jako oddělovače.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) k umístění mezi prvky pole při spojování. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) částí k spojení. |

### Návratová hodnota

[String](../) představující spojené prvky.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [Object](../../object/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)