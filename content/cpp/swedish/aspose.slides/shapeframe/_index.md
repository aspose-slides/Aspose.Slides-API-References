---
title: ShapeFrame
second_title: Aspose.Slides för C++ API-referens
description: Representerar egenskaperna för en shape frame.
type: docs
weight: 5136
url: /sv/aspose.slides/shapeframe/
---
## ShapeFrame klass

Representerar egenskaperna för shape frame.

```cpp
class ShapeFrame : public Aspose::Slides::IShapeFrame
```

## Metoder

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klonar |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [CloneT](./clonet/)() override | Klonar. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Returnerar ett värde som anger om den här instansen är lika med ett angivet objekt. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ShapeFrame](./)\>) | Returnerar ett värde som anger om den här instansen är lika med ett angivet objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **float** [get_CenterX](./get_centerx/)() override | Returnerar X-koordinaten för en ramens centrum. Läs-endast **float**. |
| **float** [get_CenterY](./get_centery/)() override | Returnerar Y-koordinaten för en ramens centrum. Läs-endast **float**. |
| [NullableBool](../nullablebool/) [get_FlipH](./get_fliph/)() override | Bestämmer om en ram är vänd horisontellt. Läs-endast [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_FlipV](./get_flipv/)() override | Bestämmer om en ram är vänd vertikalt. Läs-endast [NullableBool](../nullablebool/). |
| **float** [get_Height](./get_height/)() override | Returnerar höjden på en ram. Läs-endast **float**. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() override | Returnerar koordinaterna för en ram. Läs-endast [System::Drawing::RectangleF](../../system.drawing/rectanglef/). |
| **float** [get_Rotation](./get_rotation/)() override | Returnerar antalet grader som en ram är roterad kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs-endast **float**. |
| **float** [get_Width](./get_width/)() override | Returnerar bredden på en ram. Läs-endast **float**. |
| **float** [get_X](./get_x/)() override | Returnerar X-koordinaten för ramens övre vänstra hörn. Läs-endast **float**. |
| **float** [get_Y](./get_y/)() override | Returnerar Y-koordinaten för ramens övre vänstra hörn. Läs-endast **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är knuten till objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Returnerar en hash-kod för detta objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'th mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
|  [ShapeFrame](./shapeframe/)(**float**, **float**, **float**, **float**, [NullableBool](../nullablebool/), [NullableBool](../nullablebool/), **float**) | Skapar nya shape frame-egenskaper. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IShapeFrame](../ishapeframe/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)