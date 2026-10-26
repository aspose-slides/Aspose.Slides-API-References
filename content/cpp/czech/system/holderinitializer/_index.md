---
title: HolderInitializer
second_title: Aspose.Slides pro C++ API Reference
description: Třída se používá k získání trvalého odkazu na instanci objektu, ať už jde o lvalue nebo rvalue. Pro získání takového odkazu použijte metodu 'HoldIfTemporary', která má tři přetížení. Dvě z nich přijímají rvalue jako parametr a pouze vrací odkaz na něj. Třetí, naopak, přijímá lvalue jako parametr, vytvoří kopii ukazatele a pak vrátí odkaz na tuto kopii. Třída také obsahuje metodu 'Hold' pro nepodmíněné držení předané hodnoty (používá se k kopírování hodnot lokálních proměnných na zásobníku nebo jejich podřízených odkazů).
type: docs
weight: 1639
url: /cs/system/holderinitializer/
---
## HolderInitializer struct

Třída se používá k získání trvalého odkazu na instanci objektu, ať už jde o lvalue nebo rvalue. Pro získání takového odkazu použijte metodu 'HoldIfTemporary', která má tři přetížení. Dvě z nich přijímají rvalue jako parametr a jen vrací odkaz na něj. Třetí, naopak, přijímá lvalue jako parametr, vytvoří kopii ukazatele a poté vrátí odkaz na tuto kopii. Třída také obsahuje metodu 'Hold' pro nepodmíněné držení předané hodnoty (používá se k kopírování hodnot lokálních proměnných na zásobníku nebo jejich podřízených odkazů)

```cpp
template<typename T,bool>class HolderInitializer
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu, který má být držen. |
| R | True, pokud je T referenční typ (specializace [SmartPtr](../smartptr/) nebo typ [System::String](../string/)) a držení dočasných odkazů je skutečně vyžadováno, false – v opačném případě. |

## Metody

| Metoda | Popis |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Zkopíruje předaný lvalue do držitele a poté vrátí odkaz na držitele. Volající by měl tuto metodu použít k nepodmíněnému držení předané hodnoty. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Inicializuje odkaz držitele předaným. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Vrací odkaz na rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Vrací odkaz na rvalue (non-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Zkopíruje předaný lvalue do držitele a poté vrátí odkaz na držitele. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)