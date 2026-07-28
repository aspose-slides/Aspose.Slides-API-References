---
title: XmlSchemaSet
second_title: Aspose.Slides C++ API referencia
description: Gyorsítótárat tartalmaz az XML Schema definíciós nyelv (XSD) sémáiról.
type: docs
weight: 781
url: /hu/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet osztály


Gyorsítótárat tartalmaz az XML [Schema](../) definíciós nyelv (XSD) sémákról.

```cpp
class XmlSchemaSet : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | Hozzáadja a megadott URL-en található XML [Schema](../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](./)-hez. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Hozzáadja a [XmlReader](../../system.xml/xmlreader/)-ben található XML [Schema](../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](./)-hez. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | Hozzáadja az összes XML [Schema](../) definíciós nyelv (XSD) sémát a megadott [XmlSchemaSet](./)-ból a [XmlSchemaSet](./)-ba. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Hozzáadja a megadott [XmlSchema](../xmlschema/)-t a [XmlSchemaSet](./)-hez. |
| void [Compile](./compile/)() | Lefordítja a [XmlSchemaSet](./)-hez hozzáadott XML [Schema](../) definíciós nyelv (XSD) sémákat egy logikai sémává. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | Jelzi, hogy a megadott cél névtér URI-val rendelkező XML [Schema](../) definíciós nyelv (XSD) séma szerepel-e a [XmlSchemaSet](./)-ben. |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Jelzi, hogy a megadott XML [Schema](../) definíciós nyelv (XSD) [XmlSchema](../xmlschema/) objektum szerepel-e a [XmlSchemaSet](./)-ban. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | Átmásolja az összes [XmlSchema](../xmlschema/) objektumot a [XmlSchemaSet](./)-ból a megadott tömbbe, a megadott indexnél kezdve. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Hivatkozástípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Ugyanazt a C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Ugyanazt a C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | Visszaadja a [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)-t a [XmlSchemaSet](./) számára. |
| **int32_t** [get_Count](./get_count/)() | Visszaadja a logikai XML [Schema](../) definíciós nyelv (XSD) sémák számát a [XmlSchemaSet](./)-ben. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | Visszaadja az összes globális attribútumot az összes XML [Schema](../) definíciós nyelv (XSD) sémában a [XmlSchemaSet](./)-ban. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | Visszaadja az összes globális elemet az összes XML [Schema](../) definíciós nyelv (XSD) sémában a [XmlSchemaSet](./)-ban. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | Visszaadja az összes globális egyszerű és összetett típust az összes XML [Schema](../) definíciós nyelv (XSD) sémában a [XmlSchemaSet](./)-ban. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Visszaad egy értéket, amely jelzi, hogy a [XmlSchemaSet](./)-ban lévő XML [Schema](../) definíciós nyelv (XSD) sémák le vannak-e fordítva. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Visszaadja az alapértelmezett [XmlNameTable](../../system.xml/xmlnametable/)-t, amelyet a [XmlSchemaSet](./) használ új XML [Schema](../) definíciós nyelv (XSD) sémák betöltésekor. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-ét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() állítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Az értéktípusú objektumot nullptr-re hivatkozáson alapuló módon hasonlítja. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Eltávolítja a megadott XML [Schema](../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](./)-ból. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Eltávolítja a megadott XML [Schema](../) definíciós nyelv (XSD) sémát és az összes általa importált sémát a [XmlSchemaSet](./)-ból. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | Újrafeldolgozza a már létező XML [Schema](../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](./)-ban. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | Visszaad egy gyűjteményt az összes XML [Schema](../) definíciós nyelv (XSD) sémáról a [XmlSchemaSet](./)-ban. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | Visszaad egy gyűjteményt az összes XML [Schema](../) definíciós nyelv (XSD) sémáról a [XmlSchemaSet](./)-ban, amely a megadott névtérhez tartozik. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | Beállítja a [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)-t a [XmlSchemaSet](./) számára. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Beállítja a [XmlResolver](../../system.xml/xmlresolver/)-t, amelyet a séma include és import elemeiben hivatkozott névterek vagy helyek feloldására használnak. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n.-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a mutatók átkapcsolását gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Egy eseménykezelőt ad hozzá az XML [Schema](../) definíciós nyelv (XSD) séma érvényesítési hibáiról szóló információk fogadásához. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Eltávolít egy eseménykezelőt az XML [Schema](../) definíciós nyelv (XSD) séma érvényesítési hibáiról szóló információk fogadásához. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlSchemaSet](./xmlschemaset/)() | Inicializál egy új példányt a [XmlSchemaSet](./) osztályból. |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | Inicializál egy új példányt a [XmlSchemaSet](./) osztályból a megadott [XmlNameTable](../../system.xml/xmlnametable/)-val. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutató számára, amely az osztály egy példányára mutat. |

## Megjegyzések



Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum argumentumként történő átadásához a függvényeknek. 

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)