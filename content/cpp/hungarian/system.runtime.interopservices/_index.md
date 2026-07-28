---
title: "System::Runtime::InteropServices"
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 781
url: /hu/system.runtime.interopservices/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [Details_ExternalException](./details_externalexception/) | Az alap kivételtípus minden COM interop kivétel és struktúrált kivételkezelés (SEH) kivétel számára. Soha ne hozzon létre példányokat ebből az osztályból kézzel. Használja helyette az ExternalException osztályt. Soha ne csomagolja az ExternalException osztály példányait [System::SmartPtr](../system/smartptr/)-be. |
| [Marshal](./marshal/) | Marshaling megvalósítást biztosít. Csak a lefordított kóddal való kompatibilitás miatt, mivel a C++ oldalon nem támogatott a felügyelt kód. Ez egy statikus típus, amely nem biztosít példányszolgáltatásokat. Soha ne hozzon létre példányokat semmilyen módon. |
| [MemoryMarshal](./memorymarshal/) | Memória marshaling megvalósítást biztosít. Csak a lefordított kóddal való kompatibilitás miatt, mivel a C++ oldalon nem támogatott a felügyelt kód. Ez egy statikus típus, amely nem biztosít példányszolgáltatásokat. Soha ne hozzon létre példányokat semmilyen módon. |
| [NativeLibrary](./nativelibrary/) |  |
| [OSPlatform](./osplatform/) |  |
## Struktúrák

| Struktúra | Leírás |
| --- | --- |
| [FILETIME](./filetime/) | Fájl idő komponenseket tárol. Ezt a típust a stacken kell lefoglalni, és érték szerint vagy referencia szerint átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére. |
| [RuntimeInformation](./runtimeinformation/) |  |
## Enumok

| Enum | Leírás |
| --- | --- |
| [GCHandleType](./gchandletype/) | Meghatározza, hogyan kezelje a szemétgyűjtő a kezelőt. |
| [VarEnum](./varenum/) | Meghatározza, hogyan legyen marshalingelve a tömb elemei. |
## Typedefek

| Typedef | Leírás |
| --- | --- |
| [ExternalException](./externalexception/) |  |