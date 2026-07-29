---
title: Rotation3D
second_title: Aspose.Slides för C++ API-referens
description: Representerar 3D-rotation av ett diagram.
type: docs
weight: 1327
url: /sv/aspose.slides.charts/rotation3d/
---
## Rotation3D klass

Representerar 3D-rotation av ett diagram.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Returnerar djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). Läs **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Anger höjden på ett 3-D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). Läs **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Returnerar perspektivvärdet (synfältets vinkel) för 3D-diagram (mellan 0 och 240). Ignoreras om RightAngleAxes-egenskap är true. Läs **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Bestämmer om diagramaxlarna är vinkelräta i stället för ritade i perspektiv. Med andra ord bestämmer den om diagramaxlarnas vinklar är oberoende av diagramrotation eller höjd. Läs **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Returnerar rotationsgraden kring X-axeln, dvs. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egenskapen matchar post 21.2.2.157 rotX (X Rotation) i ECMA-376 och alternativet "Y Rotation" i PowerPoint 2007+. Läs **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Returnerar rotationsgraden kring Y-axeln, dvs. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egenskapen matchar post 21.2.2.158 rotY (Y Rotation) i ECMA-376 och alternativet "X Rotation" i PowerPoint 2007+. Läs **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning av C#-statement lock(). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initialiserar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med det angivna värdet. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Ställer in djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). Skriv **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Anger höjden på ett 3-D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). Skriv **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Ställer in perspektivvärdet (synfältets vinkel) för 3D-diagram (mellan 0 och 240). Ignoreras om RightAngleAxes-egenskap är true. Skriv **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Bestämmer om diagramaxlarna är vinkelräta i stället för ritade i perspektiv. Med andra ord bestämmer den om diagramaxlarnas vinklar är oberoende av diagramrotation eller höjd. Skriv **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Ställer in rotationsgraden kring X-axeln, dvs. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egenskapen matchar post 21.2.2.157 rotX (X Rotation) i ECMA-376 och alternativet "Y Rotation" i PowerPoint 2007+. Skriv **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Ställer in rotationsgraden kring Y-axeln, dvs. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egenskapen matchar post 21.2.2.158 rotY (Y Rotation) i ECMA-376 och alternativet "X Rotation" i PowerPoint 2007+. Skriv **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n-:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning av C#-statement lock(). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [IRotation3D](../irotation3d/)
* Klass [IDOMObject](../../aspose.slides/idomobject/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)