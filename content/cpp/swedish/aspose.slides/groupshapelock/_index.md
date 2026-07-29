---
title: GroupShapeLock
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer vilka operationer som är inaktiverade på föräldern GroupShape.
type: docs
weight: 1210
url: /sv/aspose.slides/groupshapelock/
---
## GroupShapeLock klass

Bestämmer vilka operationer som är inaktiverade på föräldern [GroupShape](../groupshape/).

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bestämmer om formen måste bevara bildförhållandet vid storleksändring. Läs **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bestämmer om det är förbjudet att lägga till denna form i en grupp. Läs **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Return true om alla låsflaggor är inaktiverade. Read-only **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bestämmer om det är förbjudet att flytta denna form. Läs **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Bestämmer om det är förbjudet att ändra rotationsvinkeln för denna form. Läs **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bestämmer om det är förbjudet att markera denna form. Läs **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bestämmer om det är förbjudet att ändra storlek på denna form. Läs **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | Bestämmer om det är förbjudet att dela upp denna gruppform. Läs **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bestämmer om formen måste bevara bildförhållandet vid storleksändring. Skriv **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bestämmer om det är förbjudet att lägga till denna form i en grupp. Skriv **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bestämmer om det är förbjudet att flytta denna form. Skriv **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Bestämmer om det är förbjudet att ändra rotationsvinkeln för denna form. Skriv **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bestämmer om det är förbjudet att markera denna form. Skriv **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bestämmer om det är förbjudet att ändra storlek på denna form. Skriv **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | Bestämmer om det är förbjudet att dela upp denna gruppform. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'th-mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [BaseShapeLock](../baseshapelock/)
* Klass [IGroupShapeLock](../igroupshapelock/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)