---
title: CompareTo()
second_title: Aspose.Slides C++ API referencia
description: Összehasonlítja az aktuális és a megadott objektumokat.
type: docs
weight: 27
url: /hu/system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const metódus


Összehasonlítja az aktuális objektumot és a megadott objektumot.

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [TimeSpan](../) | A [TimeSpan](../) objektum, amellyel az aktuális objektumot összehasonlítjuk |

### Visszatérési érték

- 1, ha az aktuális objektum az **value**-nál rövidebb időintervallumot képvisel; 0, ha az aktuális objektum az **value**-val egyenlő időintervallumot képvisel; 1, ha az aktuális objektum az **value**-nál hosszabb időintervallumot képvisel

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const metódus


Összehasonlítja az aktuális objektumot és a megadott objektumot.

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A [TimeSpan](../) objektum, amellyel az aktuális objektumot összehasonlítjuk |

### Visszatérési érték

- 1, ha az aktuális objektum az **value**-nál rövidebb időintervallumot képvisel; 0, ha az aktuális objektum az **value**-val egyenlő időintervallumot képvisel; 1, ha az aktuális objektum az **value**-nál hosszabb időintervallumot képvisel

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [TimeSpan](../)
* Osztály [Object](../../object/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)