---
title: ToString()
second_title: Aspose.Slides C++ API-referencia
description: "Átalakítja ennek az példánynak az értékét egy ekvivalens System::String-re a megadott kulturális formázási információk felhasználásával."
type: docs
weight: 196
url: /hu/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) metódus


Átalakítja ennek az példánynak az értékét egy ekvivalens [System::String](../../string/)-ra a megadott kulturális formázási információk felhasználásával.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Egy [System::IFormatProvider](../../iformatprovider/) interfész megvalósítás, amely kulturális formázási információkat biztosít. |

### Visszatérési érték

Egy [System::String](../../string/) példány, amely ekvivalens ennek a példánynak az értékével.

## IConvertible::ToString() const metódus


A C# [Object.ToString()](../../object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterláncba konvertálását.

```cpp
virtual String System::Object::ToString() const
```


### Visszatérési érték

[String](../../string/) ábrázolás, ahogyan a végső osztály biztosítja.

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [IConvertible](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)