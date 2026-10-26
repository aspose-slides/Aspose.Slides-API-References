---
title: IConnectorLock
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer vilka operationer som är inaktiverade på den överordnade Connector.
type: docs
weight: 1860
url: /sv/aspose.slides/iconnectorlock/
---
## IConnectorLock klass

Bestämmer vilka operationer som är inaktiverade på föräldern [Connector](../connector/).

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Bestämmer om förändring av justeringsvärden är förbjuden. Läs **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Bestämmer om förändring av pilhuvuden är förbjuden. Läs **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bestämmer om en form måste bevara bildförhållandet vid storleksändring. Läs **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bestämmer om en direkt förändring av konturen för denna form är förbjuden. Läs **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bestämmer om att lägga till denna form i en grupp är förbjudet. Läs **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Returnerar true om alla låsflaggor är inaktiverade. Skrivskyddad **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | Bestämmer om förflyttning av denna form är förbjuden. Läs **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Bestämmer om förändring av rotationsvinkel för denna form är förbjuden. Läs **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bestämmer om val av denna form är förbjudet. Läs **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Bestämmer om förändring av en formtyp är förbjuden. Läs **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bestämmer om storleksändring av denna form är förbjuden. Läs **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Bestämmer om förändring av justeringsvärden är förbjuden. Skriv **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Bestämmer om förändring av pilhuvuden är förbjuden. Skriv **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bestämmer om en form måste bevara bildförhållandet vid storleksändring. Skriv **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bestämmer om en direkt förändring av konturen för denna form är förbjuden. Skriv **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bestämmer om att lägga till denna form i en grupp är förbjudet. Skriv **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | Bestämmer om förflyttning av denna form är förbjuden. Skriv **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Bestämmer om förändring av rotationsvinkel för denna form är förbjuden. Skriv **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bestämmer om val av denna form är förbjudet. Skriv **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Bestämmer om förändring av en formtyp är förbjuden. Skriv **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bestämmer om storleksändring av denna form är förbjuden. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te templatargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |

## Se också

* Klass [IBaseShapeLock](../ibaseshapelock/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)