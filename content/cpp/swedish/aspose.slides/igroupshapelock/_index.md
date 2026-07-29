---
title: IGroupShapeLock
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer vilka operationer som är inaktiverade på föräldern GroupShape.
type: docs
weight: 2497
url: /sv/aspose.slides/igroupshapelock/
---
## IGroupShapeLock klass


Bestämmer vilka operationer som är inaktiverade på föräldern [GroupShape](../groupshape/).

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bestämmer om formen måste bevara bildförhållandet vid storleksändring. Läs **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bestämmer om det är förbjudet att lägga till denna form i en grupp. Läs **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Return true om alla låsflaggor är inaktiverade. Skrivskyddad **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bestämmer om det är förbjudet att flytta denna form. Läs **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Bestämmer om det är förbjudet att ändra rotationsvinkeln för denna form. Läs **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bestämmer om det är förbjudet att markera denna form. Läs **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bestämmer om det är förbjudet att ändra storlek på denna form. Läs **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | Bestämmer om det är förbjudet att dela upp denna gruppform. Läs **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Gör det möjligt att hash:a anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referens-jämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bestämmer om formen måste bevara bildförhållandet vid storleksändring. Skriv **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bestämmer om det är förbjudet att lägga till denna form i en grupp. Skriv **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bestämmer om det är förbjudet att flytta denna form. Skriv **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Bestämmer om det är förbjudt att ändra rotationsvinkeln för denna form. Skriv **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bestämmer om det är förbjudet att markera denna form. Skriv **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bestämmer om det är förbjudet att ändra storlek på denna form. Skriv **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | Bestämmer om det är förbjudet att dela upp denna gruppform. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IBaseShapeLock](../ibaseshapelock/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)