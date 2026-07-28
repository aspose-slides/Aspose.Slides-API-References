---
title: ITextFrameFormat
second_title: Aspose.Slides C++ API referencia
description: Tartalmazza a TextFrame formázási tulajdonságait.
type: docs
weight: 4083
url: /hu/aspose.slides/itextframeformat/
---
## ITextFrameFormat osztály


Tartalmazza a [TextFrame](../textframe/) formázási tulajdonságait.

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Visszaadja a függőleges horgony szöveget egy [TextFrame](../textframe/)-ben. Olvassa [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Visszaadja a szöveg automatikus illeszkedési módját. Olvassa [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Ha [NullableBool::True](../nullablebool/), akkor a szöveget vízszintesen középre kell helyezni a keretben. Olvassa [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Visszaadja az oszlopok számát a szövegterületen. Ennek az értéknek pozitívnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. A 0 érték undefined értéket jelent. Olvassa **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Visszaadja a szövegoszlopok közti távolságot a szövegterületen (pontban). Ez csak akkor alkalmazandó, ha egynél több oszlop van. Ennek az értéknek pozitívnak kell lennie. Ellenkező esetben nullára lesz állítva. Olvassa **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Visszaadja vagy beállítja, hogy a szöveg teljesen kívül legyen a 3D jelenetből. Olvassa **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Visszaadja az alsó margót (pontokban) egy [TextFrame](../textframe/)-ben. Olvassa **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Visszaadja a bal margót (pontokban) egy [TextFrame](../textframe/)-ben. Olvassa **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Visszaadja a jobb margót (pontokban) egy [TextFrame](../textframe/)-ben. Olvassa **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Visszaadja a felső margót (pontokban) egy [TextFrame](../textframe/)-ben. Olvassa **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Megadja a szövegre a határoló keretben alkalmazott egyedi forgást. Ha nincs megadva, a kísérő alakzat forgását használja. Ha meg van adva, akkor ez függetlenül az alakzattól alkalmazásra kerül. Tehát az alakzat kaphat forgást, a szöveg is saját forgással rendelkezhet. A vizuális szöveg forgásának eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Olvassa **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Visszaadja a szöveg stílusát. Csak olvasásra [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Meghatározza a szöveg tájolását. A vizuális szöveg forgásának eredő értéke ebből a tulajdonságból és a RotationAngle egyéni szögből származik. Olvassa [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely a szöveg 3D effektus tulajdonságait képviseli. Csak olvasásra [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Lekéri a szöveg tördelő alakzatát. Olvassa [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** ha a szöveg [TextFrame](../textframe/) margóinál van tördelve. Olvassa [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Lekéri az öröklődés alkalmazásával a hatékony szövegkeret formázási adatokat. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak egy új objektumot inicializál és engedélyezi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Nem másol semmit, csak egy új objektumot inicializál és engedélyezi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaszerűen összehasonlítja az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Beállítja a függőleges horgony szöveget egy [TextFrame](../textframe/)-ben. Írja [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Beállítja a szöveg automatikus illeszkedési módját. Írja [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Ha [NullableBool::True](../nullablebool/), akkor a szöveget vízszintesen középre kell helyezni a keretben. Írja [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Beállítja az oszlopok számát a szövegterületen. Ennek az értéknek pozitívnak kell lennie. Ellenkező esetben nullára lesz állítva. A 0 érték undefined értéket jelent. Írja **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). Ez csak akkor alkalmazandó, ha egynél több oszlop van. Ennek az értéknek pozitívnak kell lennie. Ellenkező esetben nullára lesz állítva. Írja **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Visszaadja vagy beállítja, hogy a szöveg teljesen kívül legyen a 3D jelenetből. Írja **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Beállítja az alsó margót (pontokban) egy [TextFrame](../textframe/)-ben. Írja **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Beállítja a bal margót (pontokban) egy [TextFrame](../textframe/)-ben. Írja **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Beállítja a jobb margót (pontokban) egy [TextFrame](../textframe/)-ben. Írja **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Beállítja a felső margót (pontokban) egy [TextFrame](../textframe/)-ben. Írja **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Megadja a szövegre a határoló keretben alkalmazott egyedi forgást. Ha nincs megadva, a kísérő alakzat forgását használja. Ha meg van adva, akkor ez függetlenül az alakzattól alkalmazásra kerül. Tehát az alakzat kaphat forgást, a szöveg is saját forgással rendelkezhet. A vizuális szöveg forgásának eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Írja **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Meghatározza a szöveg tájolását. A vizuális szöveg forgásának eredő értéke ebből a tulajdonságból és a RotationAngle egyéni szögből származik. Írja [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Beállítja a szöveg tördelő alakzatát. Írja [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** ha a szöveg [TextFrame](../textframe/) margóinál van tördelve. Írja [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi, hogy a tárolók mutatóit gyenge módra állítsa. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)