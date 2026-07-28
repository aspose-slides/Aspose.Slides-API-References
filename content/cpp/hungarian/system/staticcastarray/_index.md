---
title: StaticCastArray()
second_title: Aspose.Slides for C++ API referencia
description: Elvégzi a megadott tömb elemeinek átkonvertálását különböző típusra. Felülbírálás azokban az esetekben, amikor a From egy SmartPtr objektum.
type: docs
weight: 2978
url: /hu/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) függvény

Elvégzi a megadott tömb elemeinek átkonvertálását más típusra. Felülbírálás azokban az esetekben, amikor a From egy [SmartPtr](../smartptr/) objektum.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| To | A típus, amelyre a megadott tömb elemeit át kell konvertálni |
| From | A típus, amelynek elemei a konvertálandó tömb elemei |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Megosztott mutató a konvertálandó elemeket tartalmazó tömbhöz |

### Visszatérési érték

Egy mutató egy új tömbhöz, amely **To** típusú elemeket tartalmaz, amelyek ekvivalensek a **from** elemeivel

Elavult
:   Hozzáadva a visszafelé kompatibilitás érdekében. Használja helyette az ExplicitCast-et.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) függvény

Elvégzi a megadott tömb elemeinek átkonvertálását más típusra. Felülbírálás azokban az esetekben, amikor a From egy Boxable és a To egy [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| To | A típus, amelyre a megadott tömb elemeit át kell konvertálni |
| From | A típus, amelynek elemei a konvertálandó tömb elemei |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Megosztott mutató a konvertálandó elemeket tartalmazó tömbhöz |

### Visszatérési érték

Egy mutató egy új tömbhöz, amely **To** típusú elemeket tartalmaz, amelyek ekvivalensek a **from** elemeivel

Elavult
:   Hozzáadva a visszafelé kompatibilitás érdekében. Használja helyette az ExplicitCast-et.

## Lásd még

* Típusdefiníció [SharedPtr](../sharedptr/)
* Osztály [Array](../array/)
* Osztály [Object](../object/)
* Struktúra [IsSmartPtr](../issmartptr/)
* Struktúra [IsBoxable](../isboxable/)
* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)