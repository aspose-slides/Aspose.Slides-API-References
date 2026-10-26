---
title: CharacterRange
second_title: Aspose.Slides C++ API referencia
description: "Egy karakterláncban a karakterpozíciók tartományát ábrázolja. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 40
url: /hu/system.drawing/characterrange/
---
## CharacterRange osztály

Egy karakterláncban a karakterpozíciók tartományát ábrázolja. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class CharacterRange
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | [CharacterRange](./) osztály egy új példányát hozza létre, amely a megadott tartományt ábrázolja. |
|  [CharacterRange](./characterrange/)() | [CharacterRange](./) osztály egy új példányát hozza létre, amely egy üres tartományt ábrázol. |
| **int32_t** [get_First](./get_first/)() const | Visszaadja az aktuális objektum által ábrázolt tartomány első karakterének pozícióját. |
| **int32_t** [get_Length](./get_length/)() const | Visszaadja az aktuális objektum által ábrázolt tartományban lévő karakterek számát. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Megállapítja, hogy az aktuális és a megadott objektumok különböző tartományokat ábrázolnak-e. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Megállapítja, hogy az aktuális és a megadott objektumok ugyanazt a tartományt ábrázolják-e. |
| void [set_First](./set_first/)(**int32_t**) | Beállítja az aktuális objektum által ábrázolt tartomány első karakterének pozícióját. |
| void [set_Length](./set_length/)(**int32_t**) | Visszaadja az aktuális objektum által ábrázolt tartományban lévő karakterek számát. |

## Lásd még

* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)