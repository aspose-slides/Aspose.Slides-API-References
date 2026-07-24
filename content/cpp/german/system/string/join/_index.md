---
title: Join()
second_title: Aspose.Slides für C++ API-Referenz
description: Verknüpft ein Array mit dem String als Trennzeichen.
type: docs
weight: 846
url: /de/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) Methode

Verknüpft ein Array mit dem String als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) der Teile zum Verbinden. |
| startIndex | int | Erster Index im Array, ab dem das Zusammenführen beginnt. |
| count | int | Anzahl der Array-Elemente, die verbunden werden sollen. -1 bedeutet 'bis zum Ende des Arrays'. |

### Rückgabewert

[String](../) die verbundenen Array-Elemente darstellt.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) Methode

Verknüpft ein Array mit dem String als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView der Teile zum Verbinden. |
| startIndex | int | Erster Index im Array, ab dem das Zusammenführen beginnt. |
| count | int | Anzahl der Array-Elemente, die verbunden werden sollen. -1 bedeutet 'bis zum Ende des Arrays'. |

### Rückgabewert

[String](../) die verbundenen Array-Elemente darstellt.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) Methode

Verknüpft ein Array mit dem String als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - aufzählbares Objekt für Teile |

### Rückgabewert

[String](../) die verbundenen Elemente darstellt.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) Methode

Verknüpft ein Array mit dem String als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) der Teile zum Verbinden. |

### Rückgabewert

[String](../) die verbundenen Elemente darstellt.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [Object](../../object/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)