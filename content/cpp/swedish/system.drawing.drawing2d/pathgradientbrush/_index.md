---
title: PathGradientBrush
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en pensel som fyller insidan av ett GraphicsPath-objekt med en gradient. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Ange alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 144
url: /sv/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush klass


Representerar en pensel som fyller insidan av ett [GraphicsPath](../graphicspath/)-objekt med en gradient. Objekt av den här klassen bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Packa alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Metoder

| Method | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Gör ingenting. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | INTE IMPLEMENTERAD. |
| [Color](../../system.drawing/color/) [get_CenterColor](./get_centercolor/)() const | Returnerar en färg som är i mitten av den bana som fylls av det aktuella objektet. |
| [PointF](../../system.drawing/pointf/) [get_CenterPoint](./get_centerpoint/)() const | Hämtar mittpunkten för gradienten. |
| [PointF](../../system.drawing/pointf/) [get_FocusScales](./get_focusscales/)() const | Hämtar fokuspunkten för gradientens avtagande. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | Returnerar ett värde som definierar en flerkärnig linjär gradient. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | INTE IMPLEMENTERAD. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_SurroundColors](./get_surroundcolors/)() const | Returnerar färger som motsvarar punkterna i den bana som denna [PathGradientBrush](./) fyller. |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | Returnerar en kopia av ett [Matrix](../matrix/)-objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | Returnerar omslagsläget. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | Multiplicerar det aktuella objektets transformmatris med den angivna matrisen. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, [WrapMode](../wrapmode/)) | Skapar en ny instans av [PathGradientBrush](./)-klassen. |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, [WrapMode](../wrapmode/)) | Skapar en ny instans av [PathGradientBrush](./)-klassen. |
|  [PathGradientBrush](./pathgradientbrush/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&) | Skapar en ny instans av [PathGradientBrush](./)-klassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr med referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| void [ResetTransform](./resettransform/)() | Återställer det aktuella objektets transformmatris så att den blir en identitetsmatris. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | Ställer in en blandning som specificerar faktorer och positioner för basfärger för denna pensel. |
| void [set_CenterColor](./set_centercolor/)([Color](../../system.drawing/color/)) | Ställer in en färg som är i mitten av den bana som fylls av det aktuella objektet. |
| void [set_CenterPoint](./set_centerpoint/)(const [PointF](../../system.drawing/pointf/)\&) | Ställer in mittpunkten för gradienten. |
| void [set_FocusScales](./set_focusscales/)(const [PointF](../../system.drawing/pointf/)\&) | Ställer in fokuspunkten för gradientens avtagande. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | Ställer in ett värde som definierar en flerkärnig linjär gradient. |
| void [set_SurroundColors](./set_surroundcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | Ställer in färger som motsvarar punkterna i den bana som denna [PathGradientBrush](./) fyller. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | Ställer in ett [Matrix](../matrix/)-objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | Ställer in omslagsläget. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | INTE IMPLEMENTERAD. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | INTE IMPLEMENTERAD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för en delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Se också

* Klass [Brush](../../system.drawing/brush/)
* Namnrymd [System::Drawing::Drawing2D](../)
* Bibliotek [Aspose.Slides](../../)