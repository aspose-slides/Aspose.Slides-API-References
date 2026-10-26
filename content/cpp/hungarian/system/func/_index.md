---
title: Func
second_title: Az Aspose.Slides C++ API referenciája
description: "Függvény delegált. Ezt a típust a stacken kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 859
url: /hu/system/func/
---
## Func osztály


Függvény delegált. Ezt a típust a stacken kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak a objektumainak kezelésére.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Args | Hívási argumentumok, majd kötelező visszatérési típus. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
|  [Func](./func/)() | Alapértelmezett konstruktor, amely null-Func-ot hoz létre. |
|  [Func](./func/)(T\&&) | Konstruktor, amely [Func](./) objektumot hoz létre, és értéket (valódi visszahívást vagy nullptr-t) rendeli hozzá. |
|  [Func](./func/)(const [Func](./)\&) | Másoló konstruktor. |
|  [Func](./func/)([Func](./)\&&) | Áthelyező konstruktor. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Másoló hozzárendelés. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Áthelyező hozzárendelés. |
|  [~Func](./~func/)() | Megsemmisítő. |
## Megjegyzések



```cpp
#include "system/func.h"
#include <iostream"

// Ez a függvény egy System::Func delegált példányt fogad paraméterként.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Hozzon létre egy System::Func delegált példányt.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Adja át a létrehozott példányt függvényargumentumként.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Ez a kódpélda a következő kimenetet állítja elő:
1
4
9
*/
```

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)