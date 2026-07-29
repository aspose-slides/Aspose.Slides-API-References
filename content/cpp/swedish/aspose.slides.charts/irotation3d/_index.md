---
title: IRotation3D
second_title: Aspose.Slides för C++ API-referens
description: Representerar 3D-rotation av ett diagram.
type: docs
weight: 1171
url: /sv/aspose.slides.charts/irotation3d/
---
## IRotation3D klass

Representerar 3D-rotation av ett diagram.

```cpp
class IRotation3D : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Returnerar djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). Läs **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Anger höjden på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). Läs **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Returnerar perspektivvärdet (fält-av-synvinkel) för 3D-diagram (mellan 0 och 100). Ignoreras om egenskapen RightAngleAxes är sann. Läs **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Bestämmer om diagramaxlarna är i räta vinklar snarare än ritade i perspektiv. Med andra ord bestäms om diagramaxlarnas vinklar är oberoende av diagramrotation eller höjd. Läs **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Returnerar rotationsgraden kring X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egenskapen motsvarar 21.2.2.157 rotX (X Rotation) i ECMA-376 och "Y Rotation"-alternativet i PowerPoint 2007+. Läs **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Returnerar rotationsgraden kring Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egenskapen motsvarar 21.2.2.158 rotY (Y Rotation) i ECMA-376 och "X Rotation"-alternativet i PowerPoint 2007+. Läs **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Ställer in djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). Skriv **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Anger höjden på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). Skriv **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Ställer in perspektivvärdet (fält-av-synvinkel) för 3D-diagram (mellan 0 och 100). Ignoreras om egenskapen RightAngleAxes är sann. Skriv **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Bestämmer om diagramaxlarna är i räta vinklar snarare än ritade i perspektiv. Med andra ord bestäms om diagramaxlarnas vinklar är oberoende av diagramrotation eller höjd. Skriv **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Ställer in rotationsgraden kring X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egenskapen motsvarar 21.2.2.157 rotX (X Rotation) i ECMA-376 och "Y Rotation"-alternativet i PowerPoint 2007+. Skriv **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Ställer in rotationsgraden kring Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egenskapen motsvarar 21.2.2.158 rotY (Y Rotation) i ECMA-376 och "X Rotation"-alternativet i PowerPoint 2007+. Skriv **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:e mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)