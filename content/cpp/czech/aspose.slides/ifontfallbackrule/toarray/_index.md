---
title: ToArray()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří a vrátí pole se všemi fonty FallBack pro toto pravidlo.
type: docs
weight: 105
url: /cs/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() metoda


Vytvoří a vrátí pole se všemi fonty FallBack pro toto pravidlo.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Návratová hodnota

Pole [System::String](../../../system/string/)
## Poznámky



```cpp
// Vytvořte pravidlo obsahující seznam fontů.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Získejte všechny názvy fontů jako pole
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) metoda


Vytvoří a vrátí pole se všemi fonty FallBack z určeného rozsahu v seznamu.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **int32_t** | Index prvního fontu, který se má přidat. |
| count | **int32_t** | Počet fontů, které se mají přidat. |

### Návratová hodnota

Pole [System::String](../../../system/string/)
## Poznámky



```cpp
// Vytvořte pravidlo obsahující seznam fontů.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Získejte poslední dva názvy fontů jako pole
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [IFontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)