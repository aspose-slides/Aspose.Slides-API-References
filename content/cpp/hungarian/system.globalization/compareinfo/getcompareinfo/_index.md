---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API-referencia
description: Lekéri a megadott kultúrához kapcsolódó CompareInfo-t, a megadott assembly-ben található karakterlánc-összehasonlítási módszerek használatával.
type: docs
weight: 183
url: /hu/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) method

Lekéri a megadott kultúrához kapcsolódó [CompareInfo](../)-t, a megadott assembly-ben található karakterlánc-összehasonlítási módszerek használatával.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Visszatérési érték

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) method

Lekéri a megadott kultúrához kapcsolódó [CompareInfo](../)-t, a megadott assembly-ben található karakterlánc-összehasonlítási módszerek használatával.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Visszatérési érték

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(int) method

Lekéri a megadott kultúrához kapcsolódó [CompareInfo](../)-t.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |

### Visszatérési érték

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&) method

Lekéri a megadott kultúrához kapcsolódó [CompareInfo](../)-t.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |

### Visszatérési érték

[CompareInfo](../) object.

## Lásd még

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Assembly](../../../system.reflection/assembly/)
* Osztály [CompareInfo](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Globalization](../../)
* Library [Aspose.Slides](../../../)