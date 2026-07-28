---
title: Format()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Zwraca reprezentację łańcucha znaków wartości reprezentowanej przez bieżący obiekt przy użyciu określonego formatu.
type: docs
weight: 1
url: /pl/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) metoda

Zwraca łańcuch znaków reprezentujący wartość reprezentowaną przez bieżący obiekt przy użyciu określonego formatu.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | [System::String](../../string/) | Format łańcucha |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Obiekt do sformatowania |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Obiekt dostarczający informacje o formatowaniu |

### Wartość zwracana

Łańcuch znaków reprezentujący **arg** sformatowany zgodnie z formatem określonym przez **format** i **formatProvider**

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [Object](../../object/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [ICustomFormatter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)