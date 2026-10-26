---
title: ILoadOptions
second_title: Aspose.Slides C++ API referenciája
description: Lehetővé teszi további opciók (például formátum vagy alapértelmezett betűtípus) megadását a prezentáció betöltésekor.
type: docs
weight: 2796
url: /hu/aspose.slides/iloadoptions/
---
## ILoadOptions osztály


Lehetővé teszi további opciók (például formátum vagy alapértelmezett betűtípus) megadását a prezentáció betöltésekor.

```cpp
class ILoadOptions : public virtual System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, így a NaN-nal sem. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, így a NaN-nal sem. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | Az opciókat reprezentálja, amelyek a Binary Large Object (BLOB) kezelés viselkedésének kezelésére használhatók, például ideiglenes fájlok vagy a memória maximális BLOB bájtok használata. Ezek az opciók a legjobb teljesítmény/ memóriafogyasztás arány beállítását célozzák egy adott környezet vagy követelmény esetén. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | Visszaadja az ázsiai betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Olvassa [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | Visszaadja a normál (Regular) betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Olvassa [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | Visszaadja a Symbol betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Olvassa [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | Visszaadja a prezentáció szövegeinek alapértelmezett nyelvét. Olvassa [System::String](../../system/string/). |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | Meghatározza, hogy a [Aspose.Slides](../) törölni fogja-e az összes beágyazott bináris objektumot a prezentáció betöltése során. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | Megadja a külső betűtípusok forrásait, amelyeket a prezentáció használ. Ezek a betűtípusok a prezentáció teljes életciklusa alatt elérhetők, és nem osztódnak meg más prezentációkkal. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | A megszakítási kérések figyelésére szolgáló token. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | Visszaadja a betöltendő prezentáció formátumát. Olvassa [Slides::LoadFormat](../loadformat/). |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | Ez a tulajdonság akkor értelmezhető, ha a prezentáció fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni a titkosított prezentációból, és a jelszót figyelmen kívül kell hagyni. A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszó használatával kell betölteni. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel lesz dobva. Olvassa **bool**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Lekéri a jelszót. Olvassa [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | Visszaadja a visszahívási (callback) interfészt, amely a külső erőforrások betöltését kezeli. Olvassa [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | Az opciókat reprezentálja, amelyek további táblázatok (spreadsheets) viselkedésének megadására használhatók. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | Visszaad egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvassa [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicilizálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | Az opciókat reprezentálja, amelyek a Binary Large Object (BLOB) kezelés viselkedésének kezelésére használhatók, például ideiglenes fájlok vagy a memória maximális BLOB bájtok használata. Ezek az opciók a legjobb teljesítmény/ memóriafogyasztás arány beállítását célozzák egy adott környezet vagy követelmény esetén. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | Beállítja az ázsiai betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Kiírja [System::String](../../system/string/). |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | Beállítja a normál (Regular) betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Kiírja [System::String](../../system/string/). |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | Beállítja a Symbol betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Kiírja [System::String](../../system/string/). |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | Beállítja a prezentáció szövegeinek alapértelmezett nyelvét. Kiírja [System::String](../../system/string/). |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | Meghatározza, hogy a [Aspose.Slides](../) törölni fogja-e az összes beágyazott bináris objektumot a prezentáció betöltése során. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | Megadja a külső betűtípusok forrásait, amelyeket a prezentáció használ. Ezek a betűtípusok a prezentáció teljes életciklusa alatt elérhetők, és nem osztódnak meg más prezentációkkal. |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | A megszakítási kérések figyelésére szolgáló token. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | Beállítja a betöltendő prezentáció formátumát. Kiírja [Slides::LoadFormat](../loadformat/). |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | Ez a tulajdonság akkor értelmezhető, ha a prezentáció fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni a titkosított prezentációból, és a jelszót figyelmen kívül kell hagyni. A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszó használatával kell betölteni. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel lesz dobva. Kiír **bool**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Beállítja a jelszót. Kiírja [System::String](../../system/string/). |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | Beállítja a visszahívási (callback) interfészt, amely a külső erőforrások betöltését kezeli. Kiírja [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | Az opciókat reprezentálja, amelyek további táblázatok (spreadsheets) viselkedésének megadására használhatók. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Beállít egy objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. Kiírja [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)