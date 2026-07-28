---
title: MarkdownSaveOptions
second_title: Aspose.Slides C++ API referencia
description: Olyan beállításokat képvisel, amelyek szabályozzák, hogyan kell a prezentációt markdown formátumban menteni.
type: docs
weight: 547
url: /hu/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions osztály


Olyan beállításokat képvisel, amelyek szabályozzák, hogyan kell a prezentációt markdown formátumban menteni.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szintaxis használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra használható. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Meghatározza az alap elérési utat, ahol a forrásokkal ellátott dokumentum mentésre kerül. Alapértelmezett a program jelenlegi könyvtára. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Visszaadja azt a betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. [System::String](../../system/string/)-t olvassa. |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Megadja, hogy melyik markdown specifikációt használja a prezentáció konvertálásához. Alapértelmezett a **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Megadja, hogy melyik markdown specifikációt használja a prezentáció konvertálásához. Alapértelmezett a **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Visszaadja a gradient vizuális stílusát. [GradientStyle](../../aspose.slides/gradientstyle/)-t olvassa. |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Megadja, hogyan kell kezelni a ismétlődő szabályos szóköz karaktereket a Markdown exportálás során. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Megadja a képek mentésére szolgáló mappanév. Alapértelmezett **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Megadja, hogy a létrehozott dokumentumnak milyen vonalvége legyen: \r (Macintosh), \n (Unix) vagy \r\n (Windows). Alapértelmezett **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Egy visszahívási objektumot képvisel a mentési folyamat százalékos állapotának frissítéséhez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | Ha **true** értékre van állítva, eltávolítja az üres vagy csak szóközöket tartalmazó sorokat a végső Markdown kimenetből. Alapértelmezett **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Megadja, hogy a létrehozott dokumentumban megjelenjenek-e a megjegyzések vagy sem. Alapértelmezett **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Megadja, hogy a létrehozott dokumentumban legyenek-e rejtett diák. Alapértelmezett **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Megadja, hogy a létrehozott dokumentumban megjelenjen-e minden dia száma. Alapértelmezett **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. **bool**-t olvassa. Alapértelmezett érték **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Lekéri a Markdown kimenetben a dia szám fejlécéhez használt formátum stringet. A formátumnak tartalmaznia kell a \"{0}\" helyőrzőt, amely az exportálás során a dia indexével lesz helyettesítve. Példa: \"# Slide {0}\" eredményezi \"# Slide 1\", \"# Slide 2\", stb. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)-t olvassa. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védelmi objektumot. |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | Konstruktor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi a leszármazottak másolásalapú konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi a leszármazottak másolásalapú konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Meghatározza az alap elérési utat, ahol a forrásokkal ellátott dokumentum mentésre kerül. Alapértelmezett a program jelenlegi könyvtára. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. [System::String](../../system/string/)-t írja. |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Megadja, hogy melyik markdown specifikációt használja a prezentáció konvertálásához. Alapértelmezett a **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Megadja, hogy melyik markdown specifikációt használja a prezentáció konvertálásához. Alapértelmezett a **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Beállítja a gradient vizuális stílusát. [GradientStyle](../../aspose.slides/gradientstyle/)-t írja. |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Megadja, hogyan kell kezelni a ismétlődő szabályos szóköz karaktereket a Markdown exportálás során. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Megadja a képek mentésére szolgáló mappanév. Alapértelmezett **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Megadja, hogy a létrehozott dokumentumnak milyen vonalvége legyen: \r (Macintosh), \n (Unix) vagy \r\n (Windows). Alapértelmezett **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Egy visszahívási objektumot képvisel a mentési folyamat százalékos állapotának frissítéséhez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | Ha **true** értékre van állítva, eltávolítja az üres vagy csak szóközöket tartalmazó sorokat a végső Markdown kimenetből. Alapértelmezett **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Megadja, hogy a létrehozott dokumentumban megjelenjenek-e a megjegyzések vagy sem. Alapértelmezett **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Megadja, hogy a létrehozott dokumentumban legyenek-e rejtett diák. Alapértelmezett **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Megadja, hogy a létrehozott dokumentumban megjelenjen-e minden dia száma. Alapértelmezett **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. **bool**-t írja. Alapértelmezett érték **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Beállítja a Markdown kimenetben a dia szám fejlécéhez használt formátum stringet. A formátumnak tartalmaznia kell a \"{0}\" helyőrzőt, amely a dia indexével lesz helyettesítve exportálás során. Példa: \"# Slide {0}\" eredményezi \"# Slide 1\", \"# Slide 2\", stb. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)-t írja. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóvá (ahelyett hogy megosztott lenne). Lehetővé teszi a mutatók konténerekben való gyenge módra történő átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védelmi objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Minden nem SVG kép (bitmap vagy metafájl) esetén meghívódik a Markdown exportálás során. Return **true** to use the specified *link* , or **false** to apply the default saving logic. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Minden SVG kép esetén meghívódik a Markdown exportálás során. Return **true** to use the specified *link* , or **false** to apply the default saving logic. |

## Megjegyzések

Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Lásd még

* Osztály [SaveOptions](../saveoptions/)
* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)