---
title: PPImage
second_title: Aspose.Slides C++ API referencia
description: Kép egy prezentációban.
type: docs
weight: 4824
url: /hu/aspose.slides/ppimage/
---
## PPImage osztály


Kép egy prezentációban.

```cpp
class PPImage : public Aspose::Slides::IPPImage,
                public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Dispose](./dispose/)() override | Felszabadítja az objektumot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_BinaryData](./get_binarydata/)() override | Visszaadja a kép adatainak másolatát. Csak olvasható **uint8_t**[]. |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Visszaadja egy kép MIME típusát, [PPImage::get_BinaryData](./get_binarydata/) kódolással. Csak olvasható [System::String](../../system/string/). |
| **int32_t** [get_Height](./get_height/)() override | Visszaadja a kép magasságát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\> [get_Image](./get_image/)() override | Visszaadja a kép másolatát. Csak olvasható [IImage](../iimage/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\> [get_SvgImage](./get_svgimage/)() const override | Visszaadja a [ISvgImage](../isvgimage/) objektumot [ISvgImage](../isvgimage/) |
| **int32_t** [get_Width](./get_width/)() override | Visszaadja a kép szélességét. Csak olvasható **int32_t**. |
| **int32_t** [get_X](./get_x/)() override | Visszaadja a kép X-eltolását. Csak olvasható **int32_t**. |
| **int32_t** [get_Y](./get_y/)() override | Visszaadja a kép Y-eltolását. Csak olvasható **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Visszaadja a kép hash kódját. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze érték típusú objektumot a nullptr-pel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [ReplaceImage](./replaceimage/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Lecseréli a kép adatokat. |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\>) override | Lecseréli a kép adatokat. Figyelem: ha a kép metafájl, raszterizálva lesz. Inkább használja a ReplaceImage(byte[]) függvényt. |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IPPImage](../ippimage/)\>) override | Lecseréli a kép adatokat. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>) | Lecseréli a képet. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Lecseréli a képet. |
| void [set_SvgImage](./set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\>) override | Beállítja a [ISvgImage](../isvgimage/) objektumot [ISvgImage](../isvgimage/) |
| virtual void [set_SvgImage](../ippimage/set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgImage](../isvgimage/)\>) | Beállítja a [ISvgImage](../isvgimage/) objektumot [ISvgImage](../isvgimage/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IPPImage](../ippimage/)
* Osztály [IDisposable](../../system/idisposable/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)