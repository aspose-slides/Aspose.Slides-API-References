---
title: DocumentProperties
second_title: Aspose.Slides for C++ API Referencia
description: A bemutató tulajdonságait képviseli.
type: docs
weight: 794
url: /hu/aspose.slides/documentproperties/
---
## DocumentProperties osztály

Represents properties of a presentation.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Módszer
| Módszer | Leírás |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Törli és alapértelmezett értékekre állítja az összes beépített tulajdonságot. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Eltávolítja az összes egyedi tulajdonságot. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klónozza a jelenlegi objektumot. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Klónozza a jelenlegi objektumot. |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Ellenőrzi, hogy létezik-e egy megadott névvel rendelkező egyedi tulajdonság. |
| [DocumentProperties](./documentproperties/)() | Inicializál egy új példányt a(z) [DocumentProperties](./) osztályból. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stílusban hasonlítja össze a referencia típusú objektumokat. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stílusban hasonlítja össze az értéktípusú objektumokat. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Visszaadja az alkalmazás sablonját. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Visszaadja az alkalmazás verzióját. Csak olvasható [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Visszaadja a bemutató szerzőjét. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Visszaadja a bemutató kategóriáját. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Visszaadja a bemutató megjegyzéseit. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Visszaadja a vállalat tulajdonságát. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Visszaadja a bemutató tartalom állapotát. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Visszaadja a bemutató tartalom típusát. Olvassa [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Visszaadja a gyűjteményben ténylegesen lévő egyedi tulajdonságok számát. Csak olvasható **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Visszaadja a bemutató létrehozásának dátumát. Az értékek UTC-ben vannak. Olvassa [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | A dokumentum részek csoportosítását és az egyes csoportokban lévő részek számát jelzi. Csak olvasható [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Visszaadja a bemutató dokumentum elrejtett diák számát. Csak olvasható **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Visszaadja a HyperlinkBase dokumentumtulajdonságot. Olvassa [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Megadja, hogy a részben egy vagy több hivatkozást kizárólag ebben a részben frissített egy producer. A következő producer, amely megnyitja a dokumentumot, frissíti a hivatkozáskapcsolatokat a részben megadott új hivatkozásokkal. Olvassa **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Visszaadja a bemutató kulcsszavait. Olvassa [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Visszaadja a bemutató legutóbbi nyomtatási dátumát. Olvassa [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Visszaadja a bemutatót utoljára módosító személy nevét. Olvassa [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Visszaadja a bemutató utolsó módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható, ha [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (mivel a [IPresentation](../ipresentation/) objektum mentési folyamatakor belsőleg frissül). Módosítható a [DocumentProperties](./) példányon keresztül, amelyet a [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) metódus ad vissza. Lásd a példát a [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) metódus összefoglalójában. |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Jelzi, hogy a dokumentum hivatkozásai naprakészek-e. Állítsa **true**-ra, ha a hivatkozások frissítve vannak. Állítsa **false**-ra, ha a hivatkozások elavultak. Olvassa **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Visszaadja a manager (kezelő) tulajdonságot. Olvassa [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Visszaadja a dokumentumban jelen lévő hang- vagy videoklipek teljes számát. Csak olvasható **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Visszaadja az alkalmazás nevét. Olvassa [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Visszaadja a jegyzeteket tartalmazó diák számát a bemutatóban. Csak olvasható **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Visszaadja a dokumentumban (ha alkalmazható) található bekezdések teljes számát. Csak olvasható **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Visszaadja a bemutató kívánt formátumát. Olvassa [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Visszaadja a bemutató revíziószámát. Olvassa **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsa **true**-ra a bélyegkép a megjelenítőhöz való méretezéséhez. Állítsa **false**-ra, hogy a bélyegkép csak a kijelzőnek megfelelő részeket mutassa. Olvassa **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Megállapítja, hogy a bemutató több ember között van-e megosztva. Olvassa **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Visszaadja a bemutató dokumentumban lévő diák teljes számát. Csak olvasható **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Visszaadja a bemutató tárgyát. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Visszaadja a bemutató címét. Olvassa [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Megadja az egyes dokumentumrészek címeit. Ezek a részek nem dokumentumrészek, hanem a dokumentumszakaszok koncepcionális ábrázolásai. Csak olvasható [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | A bemutató teljes szerkesztési ideje. Olvassa [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Visszaadja a dokumentumban lévő szavak teljes számát. Csak olvasható **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Visszaad egy egyedi tulajdonság nevét a megadott indexen. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Lekéri egy név alapján megnevezett bool értéket az egyedi tulajdonságokból. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Lekéri egy név alapján megnevezett egész értéket az egyedi tulajdonságokból. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Lekéri egy név alapján megnevezett DateTime értéket az egyedi tulajdonságokból. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Lekéri egy név alapján megnevezett string értéket az egyedi tulajdonságokból. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Lekéri egy név alapján megnevezett float értéket az egyedi tulajdonságokból. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Lekéri egy név alapján megnevezett double értéket az egyedi tulajdonságokból. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Lekéri a szenzitivitási címkék tömbjét az egyedi dokumentumtulajdonságokból (Microsoft Information Protection SDK Metaadat). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Visszaadja a megadott névhez kapcsolódó egyedi tulajdonságot. Olvassa [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Beállítja a megadott névhez kapcsolódó egyedi tulajdonságot. Írja [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot hoz létre és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot hoz létre és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Eltávolít egy megadott névhez kapcsolódó egyedi tulajdonságot. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Beállítja egy alkalmazás sablonját. Írja [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Beállítja a bemutató szerzőjét. Írja [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Beállítja a bemutató kategóriáját. Írja [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Beállítja a bemutató megjegyzéseit. Írja [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Beállítja a vállalat tulajdonságot. Írja [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Beállítja a bemutató tartalom állapotát. Írja [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Beállítja a bemutató tartalom típusát. Írja [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Visszaadja a bemutató létrehozásának dátumát. Az értékek UTC-ben vannak. Írja [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Beállítja a HyperlinkBase dokumentumtulajdonságot. Írja [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Megadja, hogy a részben egy vagy több hivatkozást kizárólag ebben a részben frissített egy producer. A következő producer, amely megnyitja a dokumentumot, frissíti a hivatkozáskapcsolatokat a részben megadott új hivatkozásokkal. Írja **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Beállítja a bemutató kulcsszavait. Írja [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Visszaadja a bemutató legutóbbi nyomtatási dátumát. Írja [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Beállítja a bemutatót utoljára módosító személy nevét. Írja [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Visszaadja a bemutató utolsó módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható, ha [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (mivel a [IPresentation](../ipresentation/) objektum mentésekor belsőleg frissül). Módosítható a [DocumentProperties](./) példányon keresztül, amelyet a [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) metódus ad vissza. Lásd a példát a [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) metódus összefoglalójában. |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Jelzi, hogy a dokumentum hivatkozásai naprakészek-e. Állítsa **true**-ra, ha a hivatkozások frissítve vannak. Állítsa **false**-ra, ha a hivatkozások elavultak. Írja **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Beállítja a manager tulajdonságot. Írja [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Beállítja az alkalmazás nevét. Írja [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Beállítja a bemutató kívánt formátumát. Írja [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Beállítja a bemutató revíziószámát. Írja **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsa **true**-ra, hogy a bélyegkép a megjelenítőhöz méreteződjön. Állítsa **false**-ra, hogy a bélyegkép csak a kijelzőnek megfelelő részeket mutassa. Írja **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Megállapítja, hogy a bemutató több ember között van-e megosztva. Írja **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Beállítja a bemutató tárgyát. Írja [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Beállítja a bemutató címét. Írja [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | A bemutató teljes szerkesztési ideje. Írja [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Beállít egy név alapján megnevezett bool egyedi tulajdonságot. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Beállít egy név alapján megnevezett egész egyedi tulajdonságot. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Beállít egy név alapján megnevezett DateTime egyedi tulajdonságot. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Beállít egy név alapján megnevezett string egyedi tulajdonságot. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Beállít egy név alapján megnevezett float egyedi tulajdonságot. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Beállít egy név alapján megnevezett double egyedi tulajdonságot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztott). Lehetővé teszi a mutatók konténerben történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

Az alábbi példa bemutatja, hogyan lehet elérni a PowerPoint [Presentation](../presentation/) beépített tulajdonságait.
```cpp
// Példányosítsa a Presentation osztályt, amely a bemutatót képviseli
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
Az alábbi példa bemutatja, hogyan lehet módosítani a PowerPoint [Presentation](../presentation/) beépített tulajdonságait.
```cpp
// Példányosítja a Presentation osztályt, amely a Presentation-t képviseli
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Létrehozza a Presentation-hez kapcsolódó IDocumentProperties objektum referenciáját
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Beállítja a beépített tulajdonságokat
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Mentse a prezentációt egy fájlba
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IDocumentProperties](../idocumentproperties/)
* Osztály [IGenericCloneable](../igenericcloneable/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)