---
title: AutoShapeLock
second_title: Aspose.Slides för C++ API-referens
description: Avgör vilka operationer som är inaktiverade på den överordnade AutoshapeEx.
type: docs
weight: 79
url: /sv/aspose.slides/autoshapelock/
---
## AutoShapeLock klass


Avgör vilka operationer som är inaktiverade på den överordnade AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Avgör om en ändring av justeringsvärden är förbjuden. Läs **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Avgör om en ändring av pilspetsar är förbjuden. Läs **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Avgör om en form måste bevara bildförhållandet vid storleksändring. Läs **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Avgör om en direkt ändring av kontur för denna form är förbjuden. Läs **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Avgör om att lägga till denna form i en grupp är förbjudet. Läs **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Returnerar true om alla låsflaggor är inaktiverade. Skrivskyddad **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Avgör om att flytta denna form är förbjudet. Läs **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Avgör om en ändring av rotationsvinkeln för denna form är förbjuden. Läs **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Avgör om att välja denna form är förbjudet. Läs **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Avgör om en ändring av formtyp är förbjuden. Läs **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Avgör om att ändra storlek på denna form är förbjudet. Läs **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Avgör om redigering av text är förbjuden. Läs **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Avgör om en ändring av justeringsvärden är förbjuden. Skriv **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Avgör om en ändring av pilspetsar är förbjuden. Skriv **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Avgör om en form måste bevara bildförhållandet vid storleksändring. Skriv **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Avgör om en direkt ändring av kontur för denna form är förbjuden. Skriv **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Avgör om att lägga till denna form i en grupp är förbjudet. Skriv **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Avgör om att flytta denna form är förbjudet. Skriv **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Avgör om en ändring av rotationsvinkeln för denna form är förbjuden. Skriv **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Avgör om att välja denna form är förbjudet. Skriv **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Avgör om en ändring av formtyp är förbjuden. Skriv **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Avgör om att ändra storlek på denna form är förbjudet. Skriv **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Avgör om redigering av text är förbjuden. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n:te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning för C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [BaseShapeLock](../baseshapelock/)
* Klass [IAutoShapeLock](../iautoshapelock/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)