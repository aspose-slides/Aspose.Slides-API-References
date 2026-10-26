---
title: CastEnumerableTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt das explizite Casting der Elemente des angegebenen Enumerable-Objekts in einen anderen Typ aus.
type: docs
weight: 2965
url: /de/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) Funktion

Führt das explizite Casting der Elemente des angegebenen Enumerable-Objekts in einen anderen Typ aus.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| To | Der Typ, in den die Elemente des Enumerable-Objekts statisch gecastet werden sollen |
| From | Der Typ des Enumerable-Objekts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enumerable | const From\& | Enumerable-Objekt, das die zu castenden Elemente enthält |

### Rückgabewert

Ein Zeiger auf eine neue Sammlung, die Elemente vom Typ **To** enthält, die den Elementen von **enumerable** entsprechen.

## System::CastEnumerableTo(const From\&) Funktion

Führt das explizite Casting der Elemente des angegebenen Enumerable-Objekts in einen anderen Typ aus.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| To | Der Typ, in den die Elemente des Enumerable-Objekts statisch gecastet werden sollen |
| From | Der Typ des Enumerable-Objekts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enumerable | const From\& | ist Erbe eines Enumerable-Objekts mit definierter get_Count-Methode und enthält die zu castenden Elemente |

### Rückgabewert

Ein Zeiger auf eine neue Sammlung, die Elemente vom Typ **To** enthält, die den Elementen von **enumerable** entsprechen.

## Siehe auch

* Klasse [ListPtr](../../system.collections.generic/listptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)