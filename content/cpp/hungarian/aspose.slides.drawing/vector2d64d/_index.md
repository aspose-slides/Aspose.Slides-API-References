---
title: Vector2d64d
second_title: Aspose.Slides C++ API-referencia
description: 2D vektor double komponensekkel
type: docs
weight: 66
url: /hu/aspose.slides.drawing/vector2d64d/
---
## Vector2d64d osztály

2D vektor **double** komponensekkel

```cpp
class Vector2d64d : public System::Object,
                    public System::Details::BoxableObjectBase
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **double** [Dot](./dot/)([Vector2d64d](./)) | Kiszámítja két vektor skalárszorzatát. |
| **bool** [Equals](./equals/)(const [Vector2d64d](./)\&) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemitikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **double** [get_Length](./get_length/)() | Megkapja a vektor skalár hosszát. Csak olvasható **double**. |
| [Vector2d64d](./) [get_Norm](./get_norm/)() | Megkapja a normál vektort. Csak olvasható [Vector2d64d](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja a objektumhoz kapcsolódó referenciagyakorló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# „is” operátor analógiája. |
| **bool** [IsNull](./isnull/)() const |  |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| static [Vector2d64d](./) [Max](./max/)([Vector2d64d](./), [Vector2d64d](./)) |  |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Engedélyezi az egyedi típusok klónozását. |
| static [Vector2d64d](./) [Min](./min/)([Vector2d64d](./), [Vector2d64d](./)) |  |
| [Vector2d64d](./) [Normalize](./normalize/)() | Létrehoz egy egyenes vonalú vektort, amelynek hossza = 1. Ennek a vektornak nem szabad nulla hosszúnak lennie. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializál egy új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában semmit nem másol, csak inicializál egy új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciagyakorlót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módba. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciagyakorló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciagyakorlót. Nem szabad közvetlenül hívni; használjon inkább okosmutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciagyakorlót. Nem szabad közvetlenül hívni; használjon inkább okosmutatókat vagy ThisProtector-t. |
| void [SwapXY](./swapxy/)() | Felcseréli az X és Y értékeket |
| [System::String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Engedélyezi az egyedi objektumok karakterlánccá konvertálását. |
| [Vector2d32f](../vector2d32f/) [ToVector2d32f](./tovector2d32f/)() | Ehhez [Vector2d32f](../vector2d32f/) |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
|  [Vector2d64d](./vector2d64d/)(**double**, **double**) | Konstruktor |
|  [Vector2d64d](./vector2d64d/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Konstruktor |
|  [Vector2d64d](./vector2d64d/)() |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciagyakorlót. Nem szabad közvetlenül hívni; használjon inkább okosmutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciagyakorlót. Nem szabad közvetlenül hívni; használjon inkább okosmutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [One](./one/) |  |
| static [Zero](./zero/) |  |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides::Drawing](../)
* Könyvtár [Aspose.Slides](../../)