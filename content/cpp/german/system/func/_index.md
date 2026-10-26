---
title: Func
second_title: Aspose.Slides für C++ API-Referenz
description: "Funktions-Delegate. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 859
url: /de/system/func/
---
## Func Klasse

Funktions-Delegate. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Args | Aufrufargumente, danach obligatorischer Rückgabetyp. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [Func](./func/)() | Standardkonstruktor, der null-Func erzeugt. |
|  [Func](./func/)(T\&&) | Konstruktor, der ein [Func](./) Objekt erstellt und ihm einen Wert zuweist (entweder echten Callback oder nullptr). |
|  [Func](./func/)(const [Func](./)\&) | Kopierkonstruktor. |
|  [Func](./func/)([Func](./)\&&) | Move-Konstruktor. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Kopierzuweisung. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Move-Zuweisung. |
|  [~Func](./~func/)() | Destruktor. |

## Anmerkungen

```cpp
#include "system/func.h"
#include <iostream>

// Diese Funktion akzeptiert ein Exemplar des System::Func-Delegaten als Parameter.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Erstelle ein Exemplar des System::Func-Delegaten.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Übergebe das erstellte Exemplar als Funktionsargument.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
1
4
9
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)