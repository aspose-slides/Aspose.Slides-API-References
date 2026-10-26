---
title: "System::Security"
second_title: Aspose.Slides pro C++ referenční příručka API
description: 
type: docs
weight: 807
url: /cs/system.security/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Bezpečný řetězec, představuje text, který by měl zůstat důvěrný. Tato třída NEŠIFRUJE vnitřní data. Objektů této třídy by se měla alokovat pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [SecureStringMarshal](./securestringmarshal/) | Sbírka metod pro alokaci a kopírování neřízených paměťových bloků. |
| [SecurityElement](./securityelement/) | XML objektový model pro kódování bezpečnostního objektu. Není implementováno. Objektů této třídy by se měla alokovat pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) typ ukazatele. |