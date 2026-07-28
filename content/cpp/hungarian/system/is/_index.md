---
title: Is()
second_title: Aspose.Slides C++ API referencia
description: Megvalósítja az 'is' deklarációs minta fordítását.
type: docs
weight: 2302
url: /hu/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) függvény

Megvalósítja az 'is' deklarációs minta fordítását.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| PatternT | ellenőrzendő típus. |
| ExpressionT | bal kifejezés típusa. |
| ResultT | az eredmény kifejezés típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | const ExpressionT\& | a kifejezés, amely ellenőrzésre kerül. |
| result | ResultT\& | változó, amely a ellenőrzött típusra lesz hozzárendelve. |

### Visszatérési érték

igaz, ha a típusellenőrzés sikeres, egyébként hamis.

## System::Is(const ExpressionT\&, const ConstantT\&) függvény

Megvalósítja az 'is' állandó minta fordítását.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ExpressionT | bal kifejezés típusa. |
| ConstantT | az állandó kifejezés típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | const ExpressionT\& | kifejezés, amely ellenőrzésre kerül. |
| constant | const ConstantT\& | kifejezés, amely a balalival lesz összehasonlítva. |

### Visszatérési érték

igaz, ha a típusellenőrzés sikeres, egyébként hamis.

## System::Is(const E\&, const A\&) függvény

Legfelső szintű egyezésfüggvény. Mintát alkalmaz egy értékre.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| A | minta típusa (örökölnie kell a Details::Pattern-t). |
| E | az egyező érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| e | const E\& | Az érték, amelyhez egyezést keresünk. |
| a | const A\& | Alkalmazandó minta. |

### Visszatérési érték

igaz, ha a minta egyezik az értékkel.

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)