---
title: XmlReaderSettings
second_title: Aspose.Slides C++ API referenciája
description: "Megadja az XmlReader::Create metódus által létrehozott XmlReader objektumon támogatandó funkciók halmazát."
type: docs
weight: 443
url: /hu/system.xml/xmlreadersettings/
---
## XmlReaderSettings osztály

Megadja a [XmlReader](../xmlreader/) objektumon támogatandó funkciók halmazát, amelyet a [XmlReader::Create](../xmlreader/create/) metódus hoz létre.

```cpp
class XmlReaderSettings : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Létrehozza a [XmlReaderSettings](./) példány egy másolatát. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Egy értéket ad vissza, amely jelzi, hogy karakterellenőrzést hajtson-e végre. |
| **bool** [get_CloseInput](./get_closeinput/)() | Egy értéket ad vissza, amely jelzi, hogy a belső stream vagy TextReader legyen-e bezárva, amikor az olvasó lezárul. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Visszaadja azt a megfelelőségi szintet, amelynek a [XmlReader](../xmlreader/) megfelel. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Egy értéket ad vissza, amely meghatározza a DTD-k feldolgozását. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Egy értéket ad vissza, amely jelzi, hogy figyelmen kívül hagyja-e a megjegyzéseket. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Egy értéket ad vissza, amely jelzi, hogy figyelmen kívül hagyja-e a feldolgozási utasításokat. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Egy értéket ad vissza, amely jelzi, hogy figyelmen kívül hagyja-e a jelentéktelen szóközöket. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Visszaadja a [XmlReader](../xmlreader/) objektum sor számának eltolását. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Visszaadja a [XmlReader](../xmlreader/) objektum sorpozíciójának eltolását. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Egy értéket ad vissza, amely jelzi a dokumentumban az entitások kibontásából eredő legnagyobb megengedett karakterek számát. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Egy értéket ad vissza, amely jelzi egy XML dokumentumban a legnagyobb megengedett karakterek számát. A nulla (0) érték határtalanságot jelent a dokumentum méretére vonatkozóan. A nem nulla érték a maximális méretet adja meg karakterekben. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Visszaadja a [XmlNameTable](../xmlnametable/) értéket, amely az atomizált karakterlánc-összehasonlításhoz használatos. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Egy értéket ad vissza, amely jelzi, hogy tiltandó-e a dokumentumtípus-definíció (DTD) feldolgozása. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Visszaadja a séma validálás során használandó XmlSchemaSet-et. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Egy értéket ad vissza, amely jelzi a séma validálási beállításokat. Ez a beállítás a [XmlReader](../xmlreader/) objektumokra vonatkozik, amelyek sémát validálnak ([XmlReaderSettings::get_ValidationType](./get_validationtype/) értéke [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Egy értéket ad vissza, amely jelzi, hogy a [XmlReader](../xmlreader/) végrehajt-e validálást vagy típus hozzárendelést olvasás közben. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-alapú összehasonlítás értéktípusú objektumot nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámláló értékét a megadott értékkel. |
| void [Reset](./reset/)() | Visszaállítja a beállítások osztály tagjait az alapértelmezett értékekre. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Beállít egy értéket, amely jelzi, hogy karakterellenőrzést hajtson-e végre. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a belső stream vagy TextReader legyen-e bezárva, amikor az olvasó lezárul. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Beállítja azt a megfelelőségi szintet, amelynek a [XmlReader](../xmlreader/) megfelel. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Beállít egy értéket, amely meghatározza a DTD-k feldolgozását. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Beállít egy értéket, amely jelzi, hogy figyelmen kívül hagyja-e a megjegyzéseket. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Beállít egy értéket, amely jelzi, hogy figyelmen kívül hagyja-e a feldolgozási utasításokat. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Beállít egy értéket, amely jelzi, hogy figyelmen kívül hagyja-e a jelentéktelen szóközöket. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Beállítja a [XmlReader](../xmlreader/) objektum sor számának eltolását. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Beállítja a [XmlReader](../xmlreader/) objektum sorpozíciójának eltolását. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Beállít egy értéket, amely jelzi a dokumentumban az entitások kibontásából eredő legnagyobb megengedett karakterek számát. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Beállít egy értéket, amely jelzi egy XML dokumentumban a legnagyobb megengedett karakterek számát. A nulla (0) érték határtalanságot jelent a dokumentum méretére vonatkozóan. A nem nulla érték a maximális méretet adja meg karakterekben. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Beállítja a [XmlNameTable](../xmlnametable/) értéket, amely az atomizált karakterlánc-összehasonlításhoz használatos. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Beállít egy értéket, amely jelzi, hogy tiltandó-e a dokumentumtípus-definíció (DTD) feldolgozása. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Beállítja a séma validálás során használandó XmlSchemaSet-et. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Beállít egy értéket, amely jelzi a séma validálási beállításokat. Ez a beállítás a [XmlReader](../xmlreader/) objektumokra vonatkozik, amelyek sémát validálnak ([XmlReaderSettings::get_ValidationType](./get_validationtype/) értéke [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Beállít egy értéket, amely jelzi, hogy a [XmlReader](../xmlreader/) végrehajt-e validálást vagy típus hozzárendelést olvasás közben. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Beállítja a [XmlResolver](../xmlresolver/) értéket, amely külső dokumentumok elérésére használatos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge pointerre (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Hozzáad egy eseménykezelőt, amely akkor lép fel, amikor az olvasó validációs hibákra bukkan. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Eltávolít egy eseménykezelőt, amely akkor lép fel, amikor az olvasó validációs hibákra bukkan. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Inicializál egy új példányt a [XmlReaderSettings](./) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Ez egy alias a megosztott mutatóra, amely egy példányra mutat ebben az osztályban. |

## Megjegyzések

Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányokat a stacken vagy az operator new használatával, mivel ez futási hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert az objektum függvények argumentumaként való átadásához.

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)