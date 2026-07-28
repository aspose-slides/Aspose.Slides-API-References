---
title: IEmbeddedWoffFontsHtmlController
second_title: Aspose.Slides C++ API referencia
description: Beágyazott woff betűtípusok html vezérlő.
type: docs
weight: 144
url: /hu/aspose.slides.export/iembeddedwofffontshtmlcontroller/
---
## IEmbeddedWoffFontsHtmlController osztály


Beágyazott woff betűtípusok html vezérlő.

```cpp
class IEmbeddedWoffFontsHtmlController : public Aspose::Slides::Export::IHtmlFormattingController
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Átadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett) állítja be. Lehetővé teszi a mutatók átváltását a gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [WriteDocumentEnd](../ihtmlformattingcontroller/writedocumentend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | HTML dokumentum láblécének írásához hívják. Minden prezentáció átalakításakor egyszer meghívásra kerül. |
| virtual void [WriteDocumentStart](../ihtmlformattingcontroller/writedocumentstart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | HTML dokumentum fejlécének írásához hívják. Minden prezentáció átalakításakor egyszer meghívásra kerül. |
| virtual void [WriteShapeEnd](../ihtmlformattingcontroller/writeshapeend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Alakzat renderelése előtt hívják. Minden alakzatra egyszer meghívásra kerül. Ha ez a függvény bármit ír a generátorba, a jelenlegi dia kép létrehozása befejeződik, hozzáadott html töredék beillesztésre kerül, és új kép indul a korábbi tetején. |
| virtual void [WriteShapeStart](../ihtmlformattingcontroller/writeshapestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Alakzat renderelése előtt hívják. Minden alakzatra egyszer meghívásra kerül. Ha ez a függvény bármit ír a generátorba, a jelenlegi dia kép létrehozása befejeződik, hozzáadott html töredék beillesztésre kerül, és új kép indul a korábbi tetején. |
| virtual void [WriteSlideEnd](../ihtmlformattingcontroller/writeslideend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | HTML dia láblécének írásához hívják. Minden diára egyszer meghívásra kerül. |
| virtual void [WriteSlideStart](../ihtmlformattingcontroller/writeslidestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | HTML dia fejlécének írásához hívják. Minden diára egyszer meghívásra kerül. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IHtmlFormattingController](../ihtmlformattingcontroller/)
* Névterület [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)