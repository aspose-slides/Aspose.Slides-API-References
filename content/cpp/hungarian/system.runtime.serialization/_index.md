---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 794
url: /hu/system.runtime.serialization/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Egy alap implementációt képviseli a [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) interfész számára. |
| [IFormatterConverter](./iformatterconverter/) | Biztosítja a kapcsolatot a [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) példány és a formázó által biztosított, a [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) belsejében lévő adatok feldolgozására leginkább alkalmas osztály között. |
| [ISerializable](./iserializable/) | Interfész egy sorosítható objektumhoz. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja a függvények argumentumaként. |
| [SerializationInfo](./serializationinfo/) | Névtelen mezőket tartalmazó halmazt tárol, amely a sorosított objektumot ábrázolja. Nem implementált. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja a függvények argumentumaként. |
| [StreamingContext](./streamingcontext/) | Üres osztály, amely lehetővé teszi a StreamingContext-et használó lefordított osztályok fordítását. Ne kezelje ennek az osztálynak a példányait a [SmartPtr](../system/smartptr/) által, ezeket csak a veremben szabad lefoglalni. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [SerializationException](./serializationexception/) |  |