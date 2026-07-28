---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for C++ API referencia
description: Representál egy kezelőt, amely a mester jegyzetdia lábléc, dátum-idő és oldalszám helykitöltőinek, valamint az összes gyermek helykitöltőnek a viselkedését tartja. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzetdiákban vannak tárolva. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.
type: docs
weight: 2900
url: /hu/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager osztály

Representál egy kezelőt, amely a mester jegyzetdia lábléc, dátum-idő, oldalszám helykitöltőinek és minden gyermekhelykitöltőnek a viselkedését tartalmazza. A gyermekhelykitöltők olyan helykitöltőket jelentnek, amelyek a függő jegyzet diáknál vannak tárolva. A függő jegyzet diák a mester jegyzetdiát használják és függnek tőle.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Értéket ad vissza, amely jelzi, hogy a dátum-idő helykitöltő jelen van. Olvasás**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Értéket ad vissza, amely jelzi, hogy a lábléc helykitöltő jelen van. Olvasás **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | Értéket ad vissza, amely jelzi, hogy a fejléc helykitöltő jelen van. Olvasás **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Értéket ad vissza, amely jelzi, hogy az oldalszám helykitöltő jelen van. Olvasás**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektummal társított referencia számláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hasonlít össze a nullptr értékkel referenciaként. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Beállítja a szöveget a mester jegyzetdia dátum-idő helykitöltőjéhez és minden gyermek dátum-idő helykitöltőjéhez. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzet diákban vannak. A függő jegyzet diák a mester jegyzetdiát használják és tőle függenek. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Módosítja a mester jegyzetdia dátum-idő helykitöltő és az összes gyermek dátum-idő helykitöltő láthatóságát. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzet diákban vannak. A függő jegyzet diák a mester jegyzetdiát használják és tőle függenek. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Beállítja a szöveget a dia dátum-idő helykitöltőjéhez. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Módosítja a dia dátum-idő helykitöltő láthatóságát. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Beállítja a szöveget a mester jegyzetdia lábléc helykitöltőjéhez és minden gyermek lábléc helykitöltőjéhez. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzet diákban vannak. A függő jegyzet diák a mester jegyzetdiát használják és tőle függenek. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Módosítja a mester jegyzetdia lábléc helykitöltő és az összes gyermek lábléc helykitöltő láthatóságát. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzet diákban vannak. A függő jegyzet diák a mester jegyzetdiát használják és tőle függenek. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Beállítja a szöveget a dia lábléc helykitöltőjéhez. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Módosítja a dia lábléc helykitöltő láthatóságát. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | Beállítja a szöveget a mester jegyzetdia fejléc helykitöltőjéhez és minden gyermek fejléc helykitöltőjéhez. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzet diákban vannak. A függő jegyzet diák a mester jegyzetdiát használják és tőle függenek. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | Módosítja a mester jegyzetdia fejléc helykitöltő és az összes gyermek fejléc helykitöltő láthatóságát. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzet diákban vannak. A függő jegyzet diák a mester jegyzetdiát használják és tőle függenek. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | Beállítja a szöveget a dia fejléc helykitöltőjéhez. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | Módosítja a dia fejléc helykitöltő láthatóságát. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Módosítja a mester jegyzetdia oldalszám helykitöltő és az összes gyermek oldalszám helykitöltő láthatóságát. A gyermekhelykitöltők olyan helykitöltőket jelentenek, amelyek a függő jegyzet diákban vannak. A függő jegyzet diák a mester jegyzetdiát használják és tőle függenek. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Módosítja a dia oldalszám helykitöltő láthatóságát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n. sablonparamétert gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tárolókban való gyengé módra cserélését. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referencia számláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)