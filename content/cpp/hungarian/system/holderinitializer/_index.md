---
title: HolderInitializer
second_title: Aspose.Slides for C++ API Referenciája
description: Ez az osztály arra szolgál, hogy állandó hivatkozást kapjon az objektumpéldányra, legyen az lvalue vagy rvalue. Ilyen hivatkozás megszerzéséhez használja a 'HoldIfTemporary' metódust, amelynek három túlterhelése van. Kettő rvalue-t vesz paraméterül, és egyszerűen visszaadja a rá mutató hivatkozást. A harmadik, ellenkező irányban, lvalue-t vesz paraméterül, pointermásolatot készít, majd visszaadja a másolat hivatkozását. Emellett az osztálynak van egy 'Hold' metódusa, amely a megadott értéket feltétlenül megtartja (helyi stackváltozók vagy azok gyermekhivatkozásainak másolására használható).
type: docs
weight: 1639
url: /hu/system/holderinitializer/
---
## HolderInitializer struktúra


Ez az osztály arra szolgál, hogy állandó hivatkozást kapjon az objektumpéldányra, legyen az lvalue vagy rvalue. Az ilyen hivatkozás megszerzéséhez használja a 'HoldIfTemporary' metódust, amelynek három túlterhelése van. Kettő rvalue-t vesz paraméterül, és egyszerűen visszaadja rá a hivatkozást. A harmadik, ellenkező irányban, lvalue-t vesz paraméterül, pointermásolatot készít, majd visszaadja a másolat hivatkozását. Emellett az osztálynak van egy 'Hold' metódusa, amely a megadott értéket feltétlenül megtartja (helyi stackváltozók vagy azok gyermekhivatkozásainak másolására használható).

```cpp
template<typename T,bool>class HolderInitializer
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az objektum típusa, amelyet tárolni kell. |
| R | Igaz, ha a T egy referencia típus ([SmartPtr](../smartptr/) specializáció vagy [System::String](../string/) típus), és valóban szükség van az ideiglenes hivatkozások megtartására, egyébként hamis. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Átmásolja a megadott lvalue-t a tárolóba, majd visszaadja a tároló hivatkozását. A hívónak feltétlenül ezt a metódust kell használnia a megadott érték megtartásához. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Inicializálja a tároló hivatkozást a megadottal. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Visszaadja a rvalue hivatkozást (const). |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Visszaadja a rvalue hivatkozást (nem const). |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Átmásolja a megadott lvalue-t a tárolóba, majd visszaadja a tároló hivatkozását. |

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)