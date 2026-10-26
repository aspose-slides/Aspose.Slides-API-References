---
title: Boolean
second_title: Aspose.Slides C++ API-referencia
description: Osztály, amely a System.Boolean .Net típus statikus tagjait tartalmazza.
type: docs
weight: 79
url: /hu/system/boolean/
---
## Boolean osztály

Osztály, amely a [System.Boolean](./) .[Net](../../system.net/) típus statikus tagjait tartalmazza.

```cpp
class Boolean
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot a bool típusú értékké. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Átalakítja a megadott karakterláncot a bool típusú értékké. |
## Mezők

| Mező | Leírás |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) a 'false' logikai érték ábrázolása. |
| static [TrueString](./truestring/) | [String](../string/) a 'true' logikai érték ábrázolása. |
## Megjegyzések


```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Hozzon létre egy logikai változót.
  bool isWeekend = false;

  // Feldolgozza a bemeneti karakterláncot és kiírja az eredményt.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Ez a kódpélda a következő kimenetet eredményezi:
Hétvége: Igen
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)