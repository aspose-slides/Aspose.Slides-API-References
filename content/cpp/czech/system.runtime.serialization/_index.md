---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides pro C++ referenční příručka API
description: 
type: docs
weight: 794
url: /cs/system.runtime.serialization/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Representuje základní implementaci rozhraní [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Poskytuje spojení mezi instancí [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) a třídou poskytnutou formátovačem, která je nejvhodnější pro parsování dat uvnitř [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Rozhraní objektu, který může být serializován. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zapouzdřete tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [SerializationInfo](./serializationinfo/) | Uchovává sadu pojmenovaných polí představujících serializovaný objekt. Není implementováno. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zapouzdřete tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [StreamingContext](./streamingcontext/) | Ukázková třída pro umožnění kompilace přeložených tříd používajících StreamingContext. Nespravujte instance této třídy pomocí [SmartPtr](../system/smartptr/), musí být alokovány pouze na zásobníku. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [SerializationException](./serializationexception/) |  |