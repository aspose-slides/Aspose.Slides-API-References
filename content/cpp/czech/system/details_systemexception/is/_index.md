---
title: Is()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: 
type: docs
weight: 27
url: /cs/system/details_systemexception/is/
---
## Podrobnosti_SystemException::Is(const System::TypeInfo\&) const metoda

```cpp
bool System::Details_SystemException::Is(const System::TypeInfo &target) const override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktura popisující typ, vůči kterému se testuje aktuální objekt. |

### Návratová hodnota

True, pokud je objekt označeného typu nebo jeho podtřídy, false jinak.

## Poznámky

Zkontrolujte, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is' operátoru.

## Viz také

* Třída [TypeInfo](../../typeinfo/)
* Třída [Details_SystemException](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)