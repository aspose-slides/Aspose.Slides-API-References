---
title: ToArray()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Vytvoří a vrátí pole se všemi náhradními fonty pro toto pravidlo.
type: docs
weight: 144
url: /cs/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() metoda

Vytvoří a vrátí pole se všemi náhradními fonty pro toto pravidlo.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Návratová hodnota

Pole typu [System::String](../../../system/string/)

## Poznámky

```cpp
// Vytvoří pravidlo, které obsahuje seznam fontů.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Získá všechna jména fontů jako pole.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) metoda

Vytvoří a vrátí pole se všemi náhradními fonty z určeného rozsahu v seznamu.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **int32_t** | Index prvního fontu, který má být přidán. |
| count | **int32_t** | Počet fontů, které mají být přidány. |

### Návratová hodnota

Pole typu [System::String](../../../system/string/)

## Poznámky

```cpp
// Vytvoří pravidlo, které obsahuje seznam fontů.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Získá poslední dva názvy fontů jako pole.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [FontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)