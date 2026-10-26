---
title: StaticCastArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt das Casting von Elementen des angegebenen Arrays in einen anderen Typ durch. Überschreibung für Fälle, in denen From ein SmartPtr-Objekt ist.
type: docs
weight: 2978
url: /de/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) Funktion

Führt das Casting von Elementen des angegebenen Arrays in einen anderen Typ durch. Überschreibung für Fälle, in denen From ein [SmartPtr](../smartptr/)-Objekt ist.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| To | Der Typ, in den die Elemente des angegebenen Arrays gecastet werden sollen |
| From | Der Typ der Elemente des Arrays, das gecastet werden soll |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Gemeinsamer Zeiger auf das Array, das die zu castenden Elemente enthält |

### Rückgabewert

Ein Zeiger auf ein neues Array, das Elemente des Typs **To** enthält, die den Elementen von **from** entsprechen

Veraltet
:   Hinzugefügt für Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) Funktion

Führt das Casting von Elementen des angegebenen Arrays in einen anderen Typ durch. Überschreibung für Fälle, in denen From Boxable ist und To [Object](../object/)[] ist.

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| To | Der Typ, in den die Elemente des angegebenen Arrays gecastet werden sollen |
| From | Der Typ der Elemente des Arrays, das gecastet werden soll |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Gemeinsamer Zeiger auf das Array, das die zu castenden Elemente enthält |

### Rückgabewert

Ein Zeiger auf ein neues Array, das Elemente des Typs **To** enthält, die den Elementen von **from** entsprechen

Veraltet
:   Hinzugefügt für Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Klasse [Array](../array/)
* Klasse [Object](../object/)
* Struktur [IsSmartPtr](../issmartptr/)
* Struktur [IsBoxable](../isboxable/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)