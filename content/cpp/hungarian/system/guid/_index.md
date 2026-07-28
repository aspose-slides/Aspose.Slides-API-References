---
title: Guid
second_title: Aspose.Slides C++ API referenciája
description: "Globálisan egyedi azonosítót (GUID) képviseli. Ezt a típust a veremben kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 885
url: /hu/system/guid/
---
## Guid osztály

A Globally Unique IDentifier-t (GUID) képviseli. Ezt a típust a veremben kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Guid
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | A jelenlegi és a megadott objektumok által képviselt GUID-ok aritmetikai összehasonlítását hajtja végre. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Meghatározza, hogy a jelenlegi és a megadott objektumok által képviselt GUID-ok egyenlőek-e. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| [Guid](./guid/)() | Létrehoz egy objektumot, amely egy csak nullákat tartalmazó GUID-ot képvisel. |
| [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Létrehoz egy objektumot, amely egy, unsigned 8-bit egész értékekből álló tömbként megadott GUID-ot képvisel. |
| [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Létrehoz egy objektumot, amely egy unsigned 8-bit egész értékek tömbnézeteként megadott GUID-ot képvisel. |
| [Guid](./guid/)(const [String](../string/)\&) | Létrehoz egy objektumot, amely egy karakterláncként megadott GUID-ot képvisel. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Létrehoz egy [Guid](./) osztály példányát a megadott GUID-összetevőkből. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Létrehoz egy [Guid](./) osztály példányát a megadott GUID-összetevőkből. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Létrehoz egy [Guid](./) osztály példányt a megadott unsigned egész számokból és bájtokból. |
| [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Létrehoz egy [Guid](./) osztály példányt a megadott unsigned egész számokból és bájtokból. |
| [Guid](./guid/)(const [Guid](./)\&) | Létrehoz egy objektumot, amely azonos GUID-ot képvisel, mint a megadott objektum. |
| static [Guid](./) [NewGuid](./newguid/)() | Új GUID-ot generál, és egy [Guid](./) objektumot ad vissza, amely ezt a GUID-ot képviseli. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Meghatározza, hogy a jelenlegi és a megadott objektumok által képviselt GUID-ok nem egyenlőek-e. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | A jelenlegi objektumhoz hozzárendeli a megadott [Guid](./) objektum által képviselt GUID-értéket. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Meghatározza, hogy a jelenlegi és a megadott objektumok által képviselt GUID-ok egyenlőek-e. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterlánc reprezentációját egy ekvivalens [Guid](./) objektummá. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Átalakítja a jelenlegi objektum által képviselt GUID-ot egy bájt tömbbé. |
| [String](../string/) [ToString](./tostring/)() const | Átalakítja a jelenlegi objektum által képviselt GUID-ot a string ábrázolásává. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Átalakítja a jelenlegi objektum által képviselt GUID-ot a megadott string formátumot használva a string ábrázolásává. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Átalakítja a jelenlegi objektum által képviselt GUID-ot a megadott string formátumot és kultúrát használva a string ábrázolásává. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Megkísérli a megadott karakterlánc átalakítását egy [Guid](./) objektummá. |
| [~Guid](./~guid/)() | Destruktor. |
## Mezők

| Mező | Leírás |
| --- | --- |
| static [Empty](./empty/) | Egy 0 értékkel rendelkező GUID-ot képvisel. |
## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)