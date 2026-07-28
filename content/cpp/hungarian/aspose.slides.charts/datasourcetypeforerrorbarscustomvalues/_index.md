---
title: DataSourceTypeForErrorBarsCustomValues
second_title: Aspose.Slides for C++ API-referencia
description: "Meghatározza a ChartDataPoint::get_ErrorBarsCustomValues tulajdonságlistájában szereplő értéktípusokat"
type: docs
weight: 404
url: /hu/aspose.slides.charts/datasourcetypeforerrorbarscustomvalues/
---
## DataSourceTypeForErrorBarsCustomValues osztály


Meghatározza az értékek típusait a [ChartDataPoint::get_ErrorBarsCustomValues](../chartdatapoint/get_errorbarscustomvalues/) tulajdonságlistában

```cpp
class DataSourceTypeForErrorBarsCustomValues : public Aspose::Slides::Charts::IDataSourceTypeForErrorBarsCustomValues
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
|  [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az XMinus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPoint.ErrorBarsCustomValues.XMinus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az XPlus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPoint.ErrorBarsCustomValues.XPlus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az YMinus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az YPlus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az XMinus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPoint.ErrorBarsCustomValues.XMinus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az XPlus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPoint.ErrorBarsCustomValues.XPlus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az YMinus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) override | Megadja, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az YPlus adatpont tulajdonságobjektumban a hibasávok egyedi értékeihez. Más szóval meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a shared helyett). Lehetővé teszi a mutatók konténerben való weak módra való átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IDataSourceTypeForErrorBarsCustomValues](../idatasourcetypeforerrorbarscustomvalues/)
* Névterület [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)