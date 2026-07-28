---
title: SoapHeader
second_title: Aspose.Slides for C++ API referenciája
description: "A SOAP fejléc tartalmát reprezentálja. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához."
type: docs
weight: 79
url: /hu/system.web.services.protocols/soapheader/
---
## SoapHeader osztály


Representálja a SOAP fejléc tartalmát. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához.

```cpp
class SoapHeader : public System::Object
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikája szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utasítja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utasítja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | A SOAP fejlécre címzett URI-ját adja vissza, ha a SOAP 1.1-es verziója van használatban. |
| **bool** [get_DidUnderstand](./get_didunderstand/)() | Visszaad egy értéket, amely jelzi, hogy a SOAP fejléc megfelelően feldolgozott-e. |
| [String](../../system/string/) [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | A 'mustUnderstand' attribútum értékét adja vissza, ha a SOAP 1.1-es verziója van használatban. |
| [String](../../system/string/) [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | A 'mustUnderstand' attribútum értékét adja vissza, ha a SOAP 1.2-es verziója van használatban. |
| [String](../../system/string/) [get_EncodedRelay](./get_encodedrelay/)() | A 'relay' attribútum értékének karakterlánc ábrázolását adja vissza. |
| **bool** [get_MustUnderstand](./get_mustunderstand/)() | Visszaad egy értéket, amely jelzi, hogy a SOAP fejlécnek érthetőnek kell lennie. |
| **bool** [get_Relay](./get_relay/)() | A 'relay' attribútum értékét adja vissza. |
| [String](../../system/string/) [get_Role](./get_role/)() | A SOAP fejlécre címzett URI-ját adja vissza, ha a SOAP 1.2-es verziója van használatban. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot hasonlít össze a nullptr-re hivatkozva. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Actor](./set_actor/)([String](../../system/string/)) | Beállítja a SOAP fejlécre címzett URI-ját, ha a SOAP 1.1-es verziója van használatban. |
| void [set_DidUnderstand](./set_didunderstand/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a SOAP fejléc megfelelően feldolgozott-e. |
| void [set_EncodedMustUnderstand](./set_encodedmustunderstand/)([String](../../system/string/)) | Beállítja a 'mustUnderstand' attribútum értékét, ha a SOAP 1.1-es verziója van használatban. |
| void [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)([String](../../system/string/)) | Beállítja a 'mustUnderstand' attribútum értékét, ha a SOAP 1.2-es verziója van használatban. |
| void [set_EncodedRelay](./set_encodedrelay/)([String](../../system/string/)) | Beállítja a 'relay' attribútum értékének karakterlánc ábrázolását. |
| void [set_MustUnderstand](./set_mustunderstand/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a SOAP fejlécnek érthetőnek kell lennie. |
| void [set_Relay](./set_relay/)(**bool**) | Beállítja a 'relay' attribútum értékét. |
| void [set_Role](./set_role/)([String](../../system/string/)) | Beállítja a SOAP fejlécre címzett URI-ját, ha a SOAP 1.2-es verziója van használatban. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóval (nem megosztottal) állítja be. Lehetővé teszi a mutatók átváltását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [SoapHeader](./soapheader/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlElement](../../system.xml/xmlelement/)\>) | Új példányt hoz létre. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Web::Services::Protocols](../)
* Könyvtár [Aspose.Slides](../../)