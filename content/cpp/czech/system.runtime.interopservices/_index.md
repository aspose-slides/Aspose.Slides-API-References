---
title: "System::Runtime::InteropServices"
second_title: Aspose.Slides pro C++ referenční příručka API
description: 
type: docs
weight: 781
url: /cs/system.runtime.interopservices/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Details_ExternalException](./details_externalexception/) | Základní typ výjimky pro všechny COM interop výjimky a výjimky strukturovaného zpracování výjimek (SEH). Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ExternalException. Nikdy neobalujte instance třídy ExternalException do [System::SmartPtr](../system/smartptr/). |
| [Marshal](./marshal/) | Poskytuje implementaci maršalování. Pouze pro kompatibilitu s přeloženým kódem, protože na straně C++ není podporován žádný spravovaný kód. Jedná se o statický typ bez služeb instance. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [MemoryMarshal](./memorymarshal/) | Poskytuje implementaci maršalování paměti. Pouze pro kompatibilitu s přeloženým kódem, protože na straně C++ není podporován žádný spravovaný kód. Jedná se o statický typ bez služeb instance. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [NativeLibrary](./nativelibrary/) |  |
| [OSPlatform](./osplatform/) |  |

## Struktury

| Struktura | Popis |
| --- | --- |
| [FILETIME](./filetime/) | Obsahuje komponenty časové značky souboru. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu [System::SmartPtr](../system/smartptr/) k řízení objektů tohoto typu. |
| [RuntimeInformation](./runtimeinformation/) |  |

## Výčty

| Výčet | Popis |
| --- | --- |
| [GCHandleType](./gchandletype/) | Definuje, jak je handle zpracováván garbage collectorem. |
| [VarEnum](./varenum/) | Definuje, jak by měly být prvky pole maršalovány. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [ExternalException](./externalexception/) |  |