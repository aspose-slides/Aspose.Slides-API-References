---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides C++ API-referencia
description: "Megadja, hogy a módszertől áthaladó vagy onnan visszatérő összes SOAP üzenet a Document formázást használja. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja argumentumként a függvényekhez."
type: docs
weight: 53
url: /hu/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute osztály


Meghatározza, hogy a metódusból áthaladó vagy visszatérő összes SOAP üzenet a Document formázást használja. Az ilyen osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig a [System::SmartPtr](../../system/smartptr/) mutatóba csomagolja ezt az osztályt, és ezt a mutatót használja argumentumként a függvényekhez.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika segítségével. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [String](../../system/string/) [get_Action](./get_action/)() | Lekéri a 'SOAPAction' attribútum értékét. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | Lekéri a kötést, amelyhez az XML webszolgáltatás-módszer egy műveletet valósít meg. |
| **bool** [get_OneWay](./get_oneway/)() | Lekéri azt az értéket, amely azt jelzi, ha a kliens nem várja meg, hogy a szerver befejezze a módszer feldolgozását. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | Lekéri azt az értéket, amely azt jelzi, ha a paraméterek egyetlen XML elemben vannak az 'Body' elem alatt. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | Lekéri a SOAP kéréshez kapcsolódó XML elem nevét, amely egy szolgáltatásleírásban műveletként van definiálva. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | Lekéri a SOAP kéréshez kapcsolódó névteret. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | Lekéri a SOAP válaszhoz kapcsolódó XML elem nevét. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | Lekéri a SOAP válaszhoz kapcsolódó névteret. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | Lekéri azt az értéket, amely meghatározza az üzenet kódolási módját. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Visszaad egy megadott típusra alkalmazott egyéni attribútumot. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Visszaadja az összes megadott típusra alkalmazott egyéni attribútumot. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Action](./set_action/)([String](../../system/string/)) | Beállítja a 'SOAPAction' attribútum értékét. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | Beállítja a kötést, amelyhez az XML webszolgáltatás-módszer egy műveletet valósít meg. |
| void [set_OneWay](./set_oneway/)(**bool**) | Beállít egy értéket, amely azt jelzi, ha a kliens nem várja meg, hogy a szerver befejezze a módszer feldolgozását. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | Beállít egy értéket, amely azt jelzi, ha a paraméterek egyetlen XML elemben vannak az 'Body' elem alatt. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | Beállítja a SOAP kéréshez kapcsolódó XML elem nevét, amely egy szolgáltatásleírásban műveletként van definiálva. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | Beállítja a SOAP kéréshez kapcsolódó névteret. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | Beállítja a SOAP válaszhoz kapcsolódó XML elem nevét. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | Beállítja a SOAP válaszhoz kapcsolódó névteret. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Beállít egy értéket, amely meghatározza az üzenet kódolási módját. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóval (nem megosztott) állítja be. Lehetővé teszi a mutatók konténerekben való gyenge módra való átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Új példányt hoz létre. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | Új példányt hoz létre. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Attribute](../../system/attribute/)
* Névterület [System::Web::Services::Protocols](../)
* Könyvtár [Aspose.Slides](../../)