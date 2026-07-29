---
title: StaticCastArray()
second_title: Aspose.Slides för C++ API-referens
description: Utför castning av element i den angivna arrayen till en annan typ. Överskugga för fall då From är SmartPtr obj.
type: docs
weight: 2978
url: /sv/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funktion


Utför castning av element i den angivna arrayen till en annan typ. Överskuggning för fall då From är [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| To | Typen att kasta elementen i den angivna arrayen till |
| From | Typen av elementen i arrayen som ska kastas |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Delad pekare till arrayen som innehåller elementen att kasta |

### Returvärde

En pekare till en ny array som innehåller element av typ **To** motsvarande elementen i **from**

Föråldrad
:   Tillagd för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funktion


Utför castning av element i den angivna arrayen till en annan typ. Överskuggning för fall då From är Boxable och To är [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| To | Typen att kasta elementen i den angivna arrayen till |
| From | Typen av elementen i arrayen som ska kastas |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Delad pekare till arrayen som innehåller elementen att kasta |

### Returvärde

En pekare till en ny array som innehåller element av typ **To** motsvarande elementen i **from**

Föråldrad
:   Tillagd för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Typdefinition [SharedPtr](../sharedptr/)
* Klass [Array](../array/)
* Klass [Object](../object/)
* Struktur [IsSmartPtr](../issmartptr/)
* Struktur [IsBoxable](../isboxable/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)