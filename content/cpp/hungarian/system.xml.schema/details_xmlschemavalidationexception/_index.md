---
title: Details_XmlSchemaValidationException
second_title: Aspose.Slides C++ API-referencia
description: Ábrázolja azt a kivételt, amelyet akkor dobnak, amikor XML Schema Definition Language (XSD) sémaellenőrzési hibákkal és figyelmeztetésekkel találkoznak egy validált XML-dokumentumban.
type: docs
weight: 27
url: /hu/system.xml.schema/details_xmlschemavalidationexception/
---
## Details_XmlSchemaValidationException osztály


Ábrázolja azt a kivételt, amelyet akkor dobnak, amikor XML [Schema](../) Definition Language (XSD) sémaellenőrzési hibákkal és figyelmeztetésekkel találkoznak egy validált XML-dokumentumban.

```cpp
class Details_XmlSchemaValidationException : public System::Xml::Schema::Details_XmlSchemaException
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Visszaad egy szótárt egyéni kivételadatokkal. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Visszaad egy 32 bites egész értéket, amely a jelen objektum által képviselt kivételhez tartozó HRESULT kód. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Visszaad egy hivatkozást az objektumra, amely a belső kivételt képviseli. |
| **int32_t** [get_LineNumber](../details_xmlschemaexception/get_linenumber/)() | Visszaadja a sor számát, amely jelzi, hol történt a hiba. |
| **int32_t** [get_LinePosition](../details_xmlschemaexception/get_lineposition/)() | Visszaadja a sor pozícióját, amely jelzi, hol történt a hiba. |
| [String](../../system/string/) [get_Message](../details_xmlschemaexception/get_message/)() const override | Visszaadja ennek a kivételnek a hibafeltétel leírását. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SourceObject](./get_sourceobject/)() | Visszaadja az XML csomópontot, amely ezt az XmlSchemaValidationException-t kiváltotta. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_SourceSchemaObject](../details_xmlschemaexception/get_sourceschemaobject/)() | Az a **[XmlSchemaObject](../xmlschemaobject/)**, amely előállította az XmlSchemaException-t. |
| [String](../../system/string/) [get_SourceUri](../details_xmlschemaexception/get_sourceuri/)() | Visszaadja a Uniform Resource Identifier (URI) helyét a séma számára, amely a kivételt okozta. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Visszaadja a veremnyomot tartalmazó karakterláncot. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Visszaadja a legbelső kivételt képviselő Exception objektum másolatát. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Közvetlenül hívható vagy használható a [LockContext](../../system/lockcontext/) őrzőobjektum. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsökkentőt a megadott értékkel. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsökkentő aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Visszaadja a jelen objektum karakterlánc reprezentációját. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Közvetlenül hívható vagy használható a [LockContext](../../system/lockcontext/) őrzőobjektum. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../../system/details_exception/what/)() const | Megvalósítja a [what()](../../system/details_exception/what/) metódust, amelyet a [ExceptionWrapper](../../system/exceptionwrapper/) osztály hív meg. Annak ellenére, hogy ez az osztály nem öröklődik a std::exception osztályból, a leszármazott osztályok védett/privát tagokat használhatnak logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../../system/exceptionwrapper/)-ba való áthelyezése megtörheti azt a logikát. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóhoz, amely ennek az osztálynak egy példányát jelöli. |

## Lásd még

* Osztály [Details_XmlSchemaException](../details_xmlschemaexception/)
* Névterület [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)