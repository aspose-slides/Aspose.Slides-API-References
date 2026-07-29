---
title: GeometryPath
second_title: Aspose.Slides för C++ API-referens
description: Representerar geometrisk bana för GeometryShape
type: docs
weight: 1067
url: /sv/aspose.slides/geometrypath/
---
## GeometryPath klass

Representerar geometrisk bana för [GeometryShape](../geometryshape/)

```cpp
class GeometryPath : public Aspose::Slides::IGeometryPath
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [ArcTo](./arcto/)(**float**, **float**, **float**, **float**) override | Lägger till den angivna bågen till sökvägen. |
| void [CloseFigure](./closefigure/)() override | Stänger den aktuella figuren i denna sökväg |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Lägger till en kubisk Bézier-kurva i slutet av sökvägen. |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**) override | Lägger till en kubisk Bézier-kurva i slutet av sökvägen. |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Lägger till en kubisk Bézier-kurva på det angivna stället i sökvägen. |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**, **uint32_t**) override | Lägger till en kubisk Bézier-kurva på det angivna stället i sökvägen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
|  [GeometryPath](./geometrypath/)() | Skapar en instans av [GeometryPath](./) |
| [PathFillModeType](../pathfillmodetype/) [get_FillMode](./get_fillmode/)() override | Ställer in fyllningsläge |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPathSegment](../ipathsegment/)\>\> [get_PathData](./get_pathdata/)() override | Returnerar geometrisk bana för [GeometryShape](../geometryshape/) som en array av bansegment. |
| **bool** [get_Stroke](./get_stroke/)() override | Ställer in strekningsutseende |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Gör det möjligt att hash:a anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Lägger till en linje i slutet av sökvägen |
| void [LineTo](./lineto/)(**float**, **float**) override | Lägger till en linje i slutet av sökvägen |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Lägger till en linje på det angivna stället i sökvägen |
| void [LineTo](./lineto/)(**float**, **float**, **uint32_t**) override | Lägger till en linje på det angivna stället i sökvägen |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
| void [MoveTo](./moveto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Ställer in nästa punkts position. |
| void [MoveTo](./moveto/)(**float**, **float**) override | Ställer in nästa punkts position. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Lägger till en kvadratisk Bézier-kurva i slutet av sökvägen |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**) override | Lägger till en kvadratisk Bézier-kurva i slutet av sökvägen |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Lägger till en kvadratisk Bézier-kurva på det angivna stället i sökvägen |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**, **uint32_t**) override | Lägger till en kvadratisk Bézier-kurva på det angivna stället i sökvägen |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Tar bort segment vid angivet index i geometrisk bana. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_FillMode](./set_fillmode/)([PathFillModeType](../pathfillmodetype/)) override | Ställer in fyllningsläge |
| void [set_Stroke](./set_stroke/)(**bool**) override | Ställer in strekningsutseende |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [IGeometryPath](../igeometrypath/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)