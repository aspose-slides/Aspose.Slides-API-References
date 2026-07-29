---
title: PictureFrameLock
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer vilka operationer som är inaktiverade på föräldern PictureFrame.
type: docs
weight: 4746
url: /sv/aspose.slides/pictureframelock/
---
## PictureFrameLock klass

Bestämmer vilka operationer som är inaktiverade på föräldern [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Bestämmer om ändring av justeringsvärden är förbjuden. Läs **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Bestämmer om ändring av pilspetsar är förbjuden. Läs **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bestämmer om en form måste bevara bildförhållandet vid storleksändring. Läs **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Bestämmer om beskärning av en bild är förbjuden. Läs **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Bestämmer om direkt ändring av kontur för denna form är förbjuden. Läs **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bestämmer om att lägga till denna form i en grupp är förbjuden. Läs **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Returnerar true om alla låsflaggor är inaktiverade. Skrivskyddad **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bestämmer om att flytta denna form är förbjudet. Läs **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Bestämmer om ändring av rotationsvinkel för denna form är förbjuden. Läs **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bestämmer om markering av denna form är förbjuden. Läs **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Bestämmer om ändring av en formtyp är förbjuden. Läs **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bestämmer om storleksändring av denna form är förbjuden. Läs **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Bestämmer om ändring av justeringsvärden är förbjuden. Skriv **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Bestämmer om ändring av pilspetsar är förbjuden. Skriv **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bestämmer om en form måste bevara bildförhållandet vid storleksändring. Skriv **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Bestämmer om beskärning av en bild är förbjuden. Skriv **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Bestämmer om direkt ändring av kontur för denna form är förbjuden. Skriv **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bestämmer om att lägga till denna form i en grupp är förbjuden. Skriv **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bestämmer om att flytta denna form är förbjudet. Skriv **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Bestämmer om ändring av rotationsvinkel för denna form är förbjuden. Skriv **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bestämmer om markering av denna form är förbjuden. Skriv **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Bestämmer om ändring av en formtyp är förbjuden. Skriv **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bestämmer om storleksändring av denna form är förbjuden. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'th mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsningens upphävning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [BaseShapeLock](../baseshapelock/)
* Klass [IPictureFrameLock](../ipictureframelock/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)