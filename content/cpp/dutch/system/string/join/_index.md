---
title: Join()
second_title: Aspose.Slides for C++ API Referentie
description: Voegt array samen met een string als scheidingsteken.
type: docs
weight: 846
url: /nl/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) methode


Voegt array samen met een string als scheidingsteken.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) om tussen array-elementen te plaatsen bij het samenvoegen. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) van delen om samen te voegen. |
| startIndex | int | Eerste index in de array om het samenvoegen te starten. |
| count | int | Aantal array-elementen om samen te voegen. -1 betekent 'tot het einde van de array'. |

### Retourwaarde

[String](../) die de samengevoegde array-elementen vertegenwoordigt.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) methode


Voegt array samen met een string als scheidingsteken.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) om tussen array-elementen te plaatsen bij het samenvoegen. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView van delen om samen te voegen. |
| startIndex | int | Eerste index in de array om het samenvoegen te starten. |
| count | int | Aantal array-elementen om samen te voegen. -1 betekent 'tot het einde van de array'. |

### Retourwaarde

[String](../) die de samengevoegde array-elementen vertegenwoordigt.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) methode


Voegt array samen met een string als scheidingsteken.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) om tussen array-elementen te plaatsen bij het samenvoegen. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - enumerateerbaar object van delen |

### Retourwaarde

[String](../) die de samengevoegde elementen vertegenwoordigt.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) methode


Voegt array samen met een string als scheidingsteken.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) om tussen array-elementen te plaatsen bij het samenvoegen. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) van delen om samen te voegen. |

### Retourwaarde

[String](../) die de samengevoegde elementen vertegenwoordigt.

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [Object](../../object/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)