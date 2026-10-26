---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: "Konverterar värdet för detta objekt till en motsvarande System::String med den angivna kulturspecifika formateringsinformationen."
type: docs
weight: 196
url: /sv/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) metod


Konverterar värdet för detta objekt till en motsvarande [System::String](../../string/) med den angivna kulturspecifika formateringsinformationen.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | En [System::IFormatProvider](../../iformatprovider/) gränssnittsimplementation som tillhandahåller kulturspecifik formateringsinformation. |

### Returvärde

En [System::String](../../string/) instans som är motsvarande värdet för detta objekt.

## IConvertible::ToString() const metod


Analog till C# [Object.ToString()](../../object/tostring/)-metod. Gör det möjligt att konvertera anpassade objekt till sträng.

```cpp
virtual String System::Object::ToString() const
```


### Returvärde

[String](../../string/) representation som tillhandahålls av den slutgiltiga klassen.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [IConvertible](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)