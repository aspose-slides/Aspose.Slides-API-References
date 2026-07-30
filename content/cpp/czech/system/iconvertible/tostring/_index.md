---
title: ToString()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: "Převede hodnotu této instance na ekvivalentní System::String pomocí zadaných informací o formátování specifických pro kulturu."
type: docs
weight: 196
url: /cs/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) metoda


Převede hodnotu této instance na ekvivalentní [System::String](../../string/) pomocí zadaných informací o formátování specifických pro kulturu.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Implementace rozhraní [System::IFormatProvider](../../iformatprovider/), která poskytuje informace o formátování specifické pro kulturu. |

### Návratová hodnota

Instanci [System::String](../../string/) ekvivalentní hodnotě této instance.

## IConvertible::ToString() const metoda


Analog metody [Object.ToString()](../../object/tostring/) v C#. Umožňuje převádět vlastní objekty na řetězec.

```cpp
virtual String System::Object::ToString() const
```


### Návratová hodnota

Zobrazení [String](../../string/) poskytované konečnou třídou.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [IConvertible](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)