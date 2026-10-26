---
title: Cookie
second_title: Aspose.Slides C++ API referenciája
description: "Egy HTTP cookie-t reprezentál. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja az objektum függvényekhez argumentumként történő átadásához."
type: docs
weight: 1
url: /hu/system.net/cookie/
---
## Cookie osztály


HTTP cookie-t képviseli. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad foglalni. Soha ne hozzon létre példányt ezen típusból a stack-en vagy az operator new használatával, mivel ez futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja az objektum függvényekhez argumentumként történő átadásához.

```cpp
class Cookie : public System::Object
```

## Módszerek

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Létrehoz egy másolatot a jelenlegi példányról. |
|  [Cookie](./cookie/)() | Új példányt hoz létre. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Új példányt hoz létre. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Új példányt hoz létre. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Új példányt hoz létre. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célra. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | A 'Comment' attribútum értékét adja vissza. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | A 'CommentURL' attribútum értékét adja vissza. |
| **bool** [get_Discard](./get_discard/)() const | A 'Discard' attribútum értékét adja vissza. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | A 'Domain' attribútum értékét adja vissza. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Egy értéket ad vissza, amely jelzi, hogy a tartomány implicit-e. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Visszaadja a tartomány kulcsát. |
| **bool** [get_Expired](./get_expired/)() | Egy értéket ad vissza, amely jelzi, hogy a cookie lejárt-e. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | A 'Expires' attribútum értékét adja vissza. |
| **bool** [get_HttpOnly](./get_httponly/)() const | A 'HttpOnly' attribútum értékét adja vissza. |
| [String](../../system/string/) [get_Name](./get_name/)() const | A cookie nevét adja vissza. |
| [String](../../system/string/) [get_Path](./get_path/)() const | A 'Path' attribútum értékét adja vissza. |
| **bool** [get_Plain](./get_plain/)() const | Egy értéket ad vissza, amely jelzi, hogy a cookie specifikáció 'Plain' típusú-e. |
| [String](../../system/string/) [get_Port](./get_port/)() const | A 'Port' attribútum értékét adja vissza. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Visszaadja a 'Port' attribútum értékeinek gyűjteményét. |
| **bool** [get_Secure](./get_secure/)() const | A 'Secure' attribútum értékét adja vissza. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Visszaadja, hogy mikor jött létre a cookie. |
| [String](../../system/string/) [get_Value](./get_value/)() const | A cookie értékét adja vissza. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | A cookie specifikációját adja vissza. |
| **int32_t** [get_Version](./get_version/)() const | A '[Version](../../system/version/)' attribútum értékét adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektummal társított referenciaszámláló adatstruktúrát adja vissza. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Ezt a metódust más metódusok hívják egy metódusnév beállításához. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusból. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípust hasonlít össze a nullptr értékkel referenciával. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | A 'Comment' attribútum értékét állítja be. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | A 'CommentURL' attribútum értékét állítja be. |
| void [set_Discard](./set_discard/)(**bool**) | A 'Discard' attribútum értékét állítja be. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | A 'Domain' attribútum értékét állítja be. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a tartomány implicit-e. |
| void [set_Expired](./set_expired/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a cookie lejárt-e. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | A 'Expires' attribútum értékét állítja be. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | A 'HttpOnly' attribútum értékét állítja be. |
| void [set_Name](./set_name/)([String](../../system/string/)) | A cookie nevét állítja be. |
| void [set_Path](./set_path/)([String](../../system/string/)) | A 'Path' attribútum értékét állítja be. |
| void [set_Port](./set_port/)([String](../../system/string/)) | A 'Port' attribútum értékét állítja be. |
| void [set_Secure](./set_secure/)(**bool**) | A 'Secure' attribútum értékét állítja be. |
| void [set_Value](./set_value/)([String](../../system/string/)) | A cookie értékét állítja be. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | A cookie specifikációját állítja be. |
| void [set_Version](./set_version/)(**int32_t**) | A '[Version](../../system/version/)' attribútum értékét állítja be. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonparamétert gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a mutatók konténerben való gyenge módra való váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott hivatkozásszámláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Az aktuális példányt karakterlánc ábrázolásba szerializálja. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Ellenőrzi és beállítja az alapértelmezett attribútumok értékeit. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | A 'Comment' attribútum neve. |
| static [CommentUrlAttributeName](./commenturlattributename/) | A 'CommentURL' attribútum neve. |
| static [DiscardAttributeName](./discardattributename/) | A 'Discard' attribútum neve. |
| static [DomainAttributeName](./domainattributename/) | A 'Domain' attribútum neve. |
| static [EqualsLiteral](./equalsliteral/) | Az elválasztó jel, amelyet egy attribútum nevének és értékének elválasztására használnak. |
| static [ExpiresAttributeName](./expiresattributename/) | A 'Expires' attribútum neve. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | A 'HttpOnly' attribútum neve. |
| static [MaxAgeAttributeName](./maxageattributename/) | A 'Max-Age' attribútum neve. |
| static [MaxSupportedVersion](./maxsupportedversion/) | A legnagyobb támogatott verzió. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | A legnagyobb támogatott verzió karakterlánc ábrázolása. |
| static [PathAttributeName](./pathattributename/) | A 'Path' attribútum neve. |
| static [PortAttributeName](./portattributename/) | A 'Port' attribútum neve. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | A tömb, amely a 'Port' attribútum értékeinek elválasztóit tartalmazza. |
| static [QuotesLiteral](./quotesliteral/) | A szimbólum, amelyet az attribútum részeinek körülvesz. |
| static [ReservedToName](./reservedtoname/) | Egy érték, amely a cookie nevének van fenntartva. |
| static [ReservedToValue](./reservedtovalue/) | Egy érték, amely a cookie értékének van fenntartva. |
| static [SecureAttributeName](./secureattributename/) | A 'Secure' attribútum neve. |
| static [SeparatorLiteral](./separatorliteral/) | Az attribútum elválasztó. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | A speciális attribútumok nevének előtagja. |
| static [VersionAttributeName](./versionattributename/) | A '[Version](../../system/version/)' attribútum neve. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Net](../)
* Könyvtár [Aspose.Slides](../../)