---
title: IPictureFrameLock
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer vilka operationer som är inaktiverade på den överordnade PictureFrameEx.
type: docs
weight: 3264
url: /sv/aspose.slides/ipictureframelock/
---
## IPictureFrameLock klass


Bestämmer vilka operationer som är inaktiverade på den överordnade PictureFrameEx.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Bestämmer om ändring av justeringsvärden är förbjuden. Läs **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Bestämmer om ändring av pilspetsar är förbjuden. Läs **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bestämmer om en form måste bevara bildförhållandet vid storleksändring. Läs **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Bestämmer om beskärning av en bild är förbjuden. Läs **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bestämmer om direkt ändring av kontur för denna form är förbjuden. Läs **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bestämmer om att lägga till denna form i en grupp är förbjuden. Läs **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Returnerar true om alla låsflaggor är inaktiverade. Skrivskyddad **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bestämmer om förflyttning av denna form är förbjuden. Läs **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Bestämmer om ändring av rotationsvinkel för denna form är förbjuden. Läs **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bestämmer om urval av denna form är förbjudet. Läs **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Bestämmer om ändring av en formtyp är förbjuden. Läs **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bestämmer om storleksändring av denna form är förbjuden. Läs **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt enligt referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt enligt referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referens-jämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Bestämmer om ändring av justeringsvärden är förbjuden. Skriv **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Bestämmer om ändring av pilspetsar är förbjuden. Skriv **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bestämmer om en form måste bevara bildförhållandet vid storleksändring. Skriv **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Bestämmer om beskärning av en bild är förbjuden. Skriv **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bestämmer om direkt ändring av kontur för denna form är förbjuden. Skriv **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bestämmer om att lägga till denna form i en grupp är förbjuden. Skriv **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bestämmer om förflyttning av denna form är förbjuden. Skriv **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Bestämmer om ändring av rotationsvinkel för denna form är förbjuden. Skriv **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bestämmer om urval av denna form är förbjudet. Skriv **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Bestämmer om ändring av en formtyp är förbjuden. Skriv **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bestämmer om storleksändring av denna form är förbjuden. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se också

* Klass [IBaseShapeLock](../ibaseshapelock/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)