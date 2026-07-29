---
title: MotionCmdPath
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett kommando i en bana.
type: docs
weight: 456
url: /sv/aspose.slides.animation/motioncmdpath/
---
## MotionCmdPath klass

Represent one command of a path.

```cpp
class MotionCmdPath : public Aspose::Slides::Animation::IMotionCmdPath
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| [MotionCommandPathType](../motioncommandpathtype/) [get_CommandType](./get_commandtype/)() override | Specificerar kommandotyp. Läs [MotionCommandPathType](../motioncommandpathtype/). |
| **bool** [get_IsRelative](./get_isrelative/)() override | Bestäm om kommandokoordinater är relativa eller inte. Läs **bool**. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../../system.drawing/pointf/)\> [get_Points](./get_points/)() override | Specificerar kommandopunkter. Läs [System::Drawing::PointF](../../system.drawing/pointf/)[]. |
| [MotionPathPointsType](../motionpathpointstype/) [get_PointsType](./get_pointstype/)() override | Specificerar typ av kommandopunkter. Läs [MotionPathPointsType](../motionpathpointstype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Motsvarighet till C#-metoden [Object.GetHashCode()](../../system/object/gethashcode/). Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Motsvarighet till C#-anropet [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Motsvarighet till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C#-satsen lock() (lås). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Motsvarighet till C#-metoden [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar i själva verket ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar i själva verket ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_CommandType](./set_commandtype/)([MotionCommandPathType](../motioncommandpathtype/)) override | Specificerar kommandotyp. Skriv [MotionCommandPathType](../motioncommandpathtype/). |
| void [set_IsRelative](./set_isrelative/)(**bool**) override | Bestäm om kommandokoordinater är relativa eller inte. Skriv **bool**. |
| void [set_Points](./set_points/)([System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../../system.drawing/pointf/)\>) override | Specificerar kommandopunkter. Skriv [System::Drawing::PointF](../../system.drawing/pointf/)[]. |
| void [set_PointsType](./set_pointstype/)([MotionPathPointsType](../motionpathpointstype/)) override | Specificerar typ av kommandopunkter. Skriv [MotionPathPointsType](../motionpathpointstype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt den n:te mallargumentet till en svag pekare (istället för en delad). Gör det möjligt att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Motsvarighet till C#-metoden [Object.ToString()](../../system/object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar C#-satsen lock() (lås) för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [IMotionCmdPath](../imotioncmdpath/)
* Namnutrymme [Aspose::Slides::Animation](../)
* Bibliotek [Aspose.Slides](../../)