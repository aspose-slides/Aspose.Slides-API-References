---
title: IHtmlGenerator
second_title: Aspose.Slides for C++ API referencia
description: HTML generátor.
type: docs
weight: 209
url: /hu/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator osztály

HTML generátor.

```cpp
class IHtmlGenerator : public virtual System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [AddAttributeValue](./addattributevalue/)([System::String](../../system/string/)) | Idézőjelekkel veszi körül az attribútumértéket, és hozzáadja a HTML-fájlhoz. |
| virtual void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | Idézőjelekkel veszi körül az attribútumértéket, és hozzáadja a HTML-fájlhoz. |
| virtual void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Idézőjelekkel veszi körül az attribútumértéket, és hozzáadja a HTML-fájlhoz. |
| virtual void [AddHtml](./addhtml/)([System::String](../../system/string/)) | Formázott HTML szöveget ad hozzá. |
| virtual void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | Formázott HTML szöveget ad hozzá. |
| virtual void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Formázott HTML szöveget ad hozzá. |
| virtual void [AddText](./addtext/)([System::String](../../system/string/)) | Egyszerű szöveget ad a HTML-fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. A sortöréseket és a szóközöket nem helyettesíti. |
| virtual void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | Egyszerű szöveget ad a HTML-fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. A sortöréseket és a szóközöket nem helyettesíti. |
| virtual void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Egyszerű szöveget ad a HTML-fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. A sortöréseket és a szóközöket nem helyettesíti. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értékes típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nincs egyetlen értékhez sem egyenlővé téve, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nincs egyetlen értékhez sem egyenlővé téve, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual **int32_t** [get_NextSlideIndex](./get_nextslideindex/)() | Visszaadja egy diának az indexét, amely a jelenlegi dia után lesz renderelve, vagy -1, ha éppen az utolsó diát rendereli. Csak olvasható **int32_t**. |
| virtual **int32_t** [get_PreviousSlideIndex](./get_previousslideindex/)() | Visszaadja a korábban renderelt dia indexét, vagy -1, ha az első dia renderelése folyik. Csak olvasható **int32_t**. |
| virtual [System::Drawing::SizeF](../../system.drawing/sizef/) [get_SlideImageSize](./get_slideimagesize/)() | Visszaadja a dia kép méretét. Csak olvasható [System::Drawing::SizeF](../../system.drawing/sizef/). |
| virtual [SvgCoordinateUnit](../svgcoordinateunit/) [get_SlideImageSizeUnit](./get_slideimagesizeunit/)() | Visszaadja a mértékegységet, amelyben a dia kép mérete meg van adva. Csak olvasható [SvgCoordinateUnit](../svgcoordinateunit/). |
| virtual [System::String](../../system/string/) [get_SlideImageSizeUnitCode](./get_slideimagesizeunitcode/)() | Visszaadja a CSS-kódot, amely a dia kép méretének megadott egységét jelöli. Csak olvasható [System::String](../../system/string/). |
| virtual **int32_t** [get_SlideIndex](./get_slideindex/)() | Visszaadja az éppen renderelt dia indexét. Csak olvasható **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatszerkezetét. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi a saját objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másolási konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem kell közvetlenül hívni; helyette használja az okos mutatókat vagy a ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem kell közvetlenül hívni; helyette használja az okos mutatókat vagy a ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi a saját objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem kell közvetlenül hívni; helyette használja az okos mutatókat vagy a ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem kell közvetlenül hívni; helyette használja az okos mutatókat vagy a ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)