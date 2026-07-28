---
title: IDataSourceTypeForErrorBarsCustomValues
second_title: Aspose.Slides C++ API Referenciája
description: Meghatározza az értékek típusait a ChartDataPoint.ErrorBarsCustomValues tulajdonságlista elemeiben
type: docs
weight: 976
url: /hu/aspose.slides.charts/idatasourcetypeforerrorbarscustomvalues/
---
## IDataSourceTypeForErrorBarsCustomValues osztály

Meghatározza az értékek típusait a ChartDataPoint.ErrorBarsCustomValues tulajdonságlista elemeiben

```cpp
class IDataSourceTypeForErrorBarsCustomValues : public virtual System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e az XMinus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPoint.ErrorBarsCustomValues.XMinus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e az XPlus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPoint.ErrorBarsCustomValues.XPlus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e a YMinus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e a YPlus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data tulajdonság értékének típusát. Olvassa el [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolatos referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e az XMinus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPoint.ErrorBarsCustomValues.XMinus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e az XPlus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPoint.ErrorBarsCustomValues.XPlus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e a YMinus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) | Meghatározza, hogy az AsCell vagy AsLiteralString vagy AsLiteralDouble tulajdonság tényleges-e a YPlus tulajdonság objektumban a hibasávok egyéni értékeihez. Más szóval, meghatározza a ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data tulajdonság értékének típusát. Írja [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átváltását gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)