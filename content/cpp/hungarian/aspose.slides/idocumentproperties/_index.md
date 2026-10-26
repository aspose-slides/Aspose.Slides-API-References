---
title: IDocumentProperties
second_title: Aspose.Slides C++ API-referencia
description: A bemutató tulajdonságait képviseli.
type: docs
weight: 1977
url: /hu/aspose.slides/idocumentproperties/
---
## IDocumentProperties osztály


A bemutató tulajdonságait képviseli.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Törli és alapértelmezett értékeket állít be az összes beépített tulajdonságnál. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Eltávolítja az összes egyedi tulajdonságot. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Ellenőrzi, hogy létezik-e egy egyedi tulajdonság a megadott névvel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C#-stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C#-stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Visszaadja az alkalmazás sablonját. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Visszaadja az alkalmazás verzióját. Csak olvasható [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Visszaadja a bemutató szerzőjét. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Visszaadja a bemutató kategóriáját. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Visszaadja a bemutató megjegyzéseit. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Visszaadja a cég tulajdonságát. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Visszaadja a bemutató tartalomállapotát. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Visszaadja a bemutató tartalomtípusát. Olvasd [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Visszaadja a gyűjteményben ténylegesen lévő egyedi tulajdonságok számát. Csak olvasható **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Visszaadja a bemutató létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasd [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Jelzi a dokumentum részek csoportosítását és az egyes csoportokban lévő részek számát. Csak olvasható [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Megadja a bemutató dokumentumban rejtett diák számát. Csak olvasható **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Visszaadja a HyperlinkBase dokumentumtulajdonságot. Olvasd [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag a termelő által került frissítésre. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasd **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Visszaadja a bemutató kulcsszavait. Olvasd [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Visszaadja a bemutató utolsó nyomtatásának dátumát. Olvasd [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Visszaadja a bemutatót utoljára módosító személy nevét. Olvasd [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Visszaadja a bemutató legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mivel belsőleg frissül a [IPresentation](../ipresentation/) objektum mentési folyamata közben). Módosítható a [DocumentProperties](../documentproperties/) példányon keresztül, amely a [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) metódus által kerül visszaadásra. Lásd a példát a [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) metódus összegzésében. |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. Állítsa ezt az elemet **true**-ra, ha a hiperhivatkozások frissítve vannak. Állítsa **false**-ra, ha a hiperhivatkozások elavultak. Olvasd **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Visszaadja a menedzser tulajdonságot. Olvasd [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Megadja a dokumentumban jelen lévő hang- vagy videoklipeknak a teljes számát. Csak olvasható **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Visszaadja az alkalmazás nevét. Olvasd [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Megadja a jegyzetet tartalmazó diák számát a bemutatóban. Csak olvasható **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Megadja a dokumentumban megtalált bekezdések teljes számát, ha alkalmazható. Csak olvasható **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Visszaadja a bemutató szándékolt formátumát. Olvasd [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Visszaadja a bemutató revízió számát. Olvasd **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Jelzi a dokumentum előnézeti kép megjelenítési módját. Állítsa ezt az elemet **true**-ra, ha a dokumentum előnézeti képet a kijelzőhöz szeretné skálázni. Állítsa **false**-ra, ha a dokumentum előnézeti képet úgy szeretné levágni, hogy csak a kijelzőhöz illeszkedő részek jelenjenek meg. Olvasd **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Megállapítja, hogy a bemutató több személy között van-e megosztva. Olvasd **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Megadja a bemutató dokumentumban lévő diák teljes számát. Csak olvasható **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Visszaadja a bemutató tárgyát. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Visszaadja a bemutató címét. Olvasd [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Megadja minden dokumentum rész címét. Ezek a részek nem dokumentum részek, hanem a dokumentum szakaszainak fogalmi ábrázolásai. Csak olvasható [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | A bemutató teljes szerkesztési ideje. Olvasd [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Megadja a dokumentumban található szavak teljes számát. Csak olvasható **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektummal kapcsolatos referencia számláló adatstruktúrát. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Visszaad egy egyedi tulajdonság nevet a megadott indexen. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Lekér egy névvel ellátott logikai értéket az egyedi tulajdonságokból. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Lekér egy névvel ellátott egész szám értéket az egyedi tulajdonságokból. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Lekér egy névvel ellátott DateTime értéket az egyedi tulajdonságokból. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Lekér egy névvel ellátott sztring értéket az egyedi tulajdonságokból. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Lekér egy névvel ellátott float értéket az egyedi tulajdonságokból. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Lekér egy névvel ellátott double értéket az egyedi tulajdonságokból. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hashelését. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Lekér egy tömböt a szenzitivitási címkékkel az egyedi dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Visszaadja a megadott névhez tartozó egyedi tulajdonságot. Olvasd [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Beállítja a megadott névhez tartozó egyedi tulajdonságot. Írja [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# ‘is’ operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zárolásra. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) szemvédő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Eltávolít egy megadott névhez tartozó egyedi tulajdonságot. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Beállítja az alkalmazás sablonját. Írja [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Beállítja a bemutató szerzőjét. Írja [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Beállítja a bemutató kategóriáját. Írja [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Beállítja a bemutató megjegyzéseit. Írja [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Beállítja a cég tulajdonságát. Írja [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Beállítja a bemutató tartalomállapotát. Írja [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Beállítja a bemutató tartalomtípusát. Írja [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Visszaadja a bemutató létrehozásának dátumát. Az értékek UTC-ben vannak. Írja [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Beállítja a HyperlinkBase dokumentumtulajdonságot. Írja [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag a termelő által került frissítésre. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Írja **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Beállítja a bemutató kulcsszavait. Írja [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Visszaadja a bemutató utolsó nyomtatásának dátumát. Írja [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Beállítja a bemutatót utoljára módosító személy nevét. Írja [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Visszaadja a bemutató legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mivel belsőleg frissül a [IPresentation](../ipresentation/) objektum mentési folyamata közben). Módosítható a [DocumentProperties](../documentproperties/) példányon keresztül, amely a [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) metódus által kerül visszaadásra. Lásd a példát a [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) metódus összegzésében. |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. Állítsa ezt az elemet **true**-ra, ha a hiperhivatkozások frissítve vannak. Állítsa **false**-ra, ha a hiperhivatkozások elavultak. Írja **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Beállítja a menedzser tulajdonságot. Írja [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Beállítja az alkalmazás nevét. Írja [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Beállítja a bemutató szándékolt formátumát. Írja [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Beállítja a bemutató revízió számát. Írja **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Jelzi a dokumentum előnézeti kép megjelenítési módját. Állítsa ezt az elemet **true**-ra, ha a dokumentum előnézeti képet a kijelzőhöz szeretné skálázni. Állítsa **false**-ra, ha a dokumentum előnézeti képet úgy szeretné levágni, hogy csak a kijelzőhöz illeszkedő részek jelenjenek meg. Írja **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Megállapítja, hogy a bemutató több személy között van-e megosztva. Írja **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Beállítja a bemutató tárgyát. Írja [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Beállítja a bemutató címét. Írja [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | A bemutató teljes szerkesztési ideje. Írja [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Beállít egy névvel ellátott logikai egyedi tulajdonságot. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Beállít egy névvel ellátott egész szám egyedi tulajdonságot. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Beállít egy névvel ellátott DateTime egyedi tulajdonságot. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Beállít egy névvel ellátott sztring egyedi tulajdonságot. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Beállít egy névvel ellátott float egyedi tulajdonságot. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Beállít egy névvel ellátott double egyedi tulajdonságot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem shared). Lehetővé teszi a mutatók konténerekben gyenge módra történő átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) szemvédő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Lemészti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)