---
title: XmlSchemaInference
second_title: Aspose.Slides C++ API Referencia
description: XML Schema Definition Language (XSD) sémát állapít meg egy XML dokumentumból. Az XmlSchemaInference osztály nem örökölhető.
type: docs
weight: 508
url: /hu/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference osztály


XML [Schema](../) Definíciós Nyelv (XSD) sémát állapít meg egy XML dokumentumból. A [XmlSchemaInference](./) osztály nem örökölhető.

```cpp
class XmlSchemaInference : public System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_Occurrence](./get_occurrence/)() | Visszaadja a [XmlSchemaInference::InferenceOption](./inferenceoption/) értéket, ami befolyásolja a XML dokumentumból származtatott séma előfordulási deklarációkat. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_TypeInference](./get_typeinference/)() | Visszaadja a [XmlSchemaInference::InferenceOption](./inferenceoption/) értéket, ami befolyásolja a XML dokumentumból származtatott típusokat. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | XML [Schema](../) Definíciós Nyelv (XSD) sémát állapít meg a megadott [XmlReader](../../system.xml/xmlreader/) objektumban található XML dokumentumból. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>) | XML [Schema](../) Definíciós Nyelv (XSD) sémát állapít meg a megadott [XmlReader](../../system.xml/xmlreader/) objektumban található XML dokumentumból, és finomítja a származtatott sémát a megadott [XmlSchemaSet](../xmlschemaset/) objektumban lévő meglévő séma felhasználásával, amely ugyanazzal a cél névtérrel rendelkezik. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát reprezentálja-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást a zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szintű összehasonlítás érték típusú objektum és nullptr között. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Occurrence](./set_occurrence/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Beállítja a [XmlSchemaInference::InferenceOption](./inferenceoption/) értéket, amely befolyásolja a XML dokumentumból származtatott séma előfordulási deklarációkat. |
| void [set_TypeInference](./set_typeinference/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Beállítja a [XmlSchemaInference::InferenceOption](./inferenceoption/) értéket, amely befolyásolja a XML dokumentumból származtatott típusokat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (ahelyett, hogy megosztott lenne). Lehetővé teszi a mutatók konténerben történő átváltását gyenge módba. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi a saját objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlSchemaInference](./xmlschemainference/)() | Inicializál egy új példányt a [XmlSchemaInference](./) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Enumok

| Enum | Leírás |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Befolyásolja a [XmlSchemaInference](./) osztály által egy XML dokumentumban lévő elemek és attribútumok esetén származtatott előfordulási és típusinformációkat. |

## Typedefok

| Typedef | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Alias egy megosztott mutatóhoz, amely ennek az osztálynak egy példányára mutat. |

## Megjegyzések



Az osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányokat ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvényekhez argumentumként való átadásához. 

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)