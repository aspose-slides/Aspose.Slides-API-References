---
title: CombineMode
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, jak jsou kombinovány ořezové oblasti.
type: docs
weight: 170
url: /cs/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Specifikuje, jak jsou kombinovány ořezové oblasti.

```cpp
enum class CombineMode
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Replace | 0 | Jedna ořezová oblast je nahrazena jinou. |
| Intersect | 1 | Dvě ořezové oblasti jsou sloučeny tak, že se vezme jejich průnik. |
| Union | 2 | Dvě ořezové oblasti jsou sloučeny tak, že se vezme jejich sjednocení. |
| Xor | 3 | Dvě ořezové oblasti jsou sloučeny tak, že se vezme jen oblast ohraničená jednou z nich, ale ne oběma. |
| Exclude | 4 | Dvě ořezové oblasti jsou sloučeny tak, že se vezme oblast první oblasti, která se nepřekrývá se druhou. |
| Complement | 5 | Dvě ořezové oblasti jsou sloučeny tak, že se vezme oblast druhé oblasti, která se nepřekrývá s první. |

## Viz také

* Jmenný prostor [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)