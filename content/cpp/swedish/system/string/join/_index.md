---
title: Join()
second_title: Aspose.Slides för C++ API-referens
description: Kombinerar en array med en sträng som avgränsare.
type: docs
weight: 846
url: /sv/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method

Kombinerar en array med en sträng som avgränsare.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) för att placera mellan array-element när de slås ihop. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) av delar att slå ihop. |
| startIndex | int | Första index i arrayen att börja slå ihop från. |
| count | int | Antal array-element att slå ihop. -1 betyder 'tills arrayen slutar'. |

### Returvärde

[String](../) som representerar sammanslagna array-element.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method

Kombinerar en array med en sträng som avgränsare.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) för att placera mellan array-element när de slås ihop. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView av delar att slå ihop. |
| startIndex | int | Första index i arrayen att börja slå ihop från. |
| count | int | Antal array-element att slå ihop. -1 betyder 'tills arrayen slutar'. |

### Returvärde

[String](../) som representerar sammanslagna array-element.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method

Kombinerar en array med en sträng som avgränsare.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) för att placera mellan array-element när de slås ihop. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - enumererbart objekt av delar |

### Returvärde

[String](../) som representerar sammanslagna element.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method

Kombinerar en array med en sträng som avgränsare.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) för att placera mellan array-element när de slås ihop. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) av delar att slå ihop. |

### Returvärde

[String](../) som representerar sammanslagna element.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [Object](../../object/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)