---
title: Pen
second_title: Aspose.Slides för C++ API-referens
description: "Representerar egenskaper såsom färg, bredd osv. för de linjer och kurvor som ritas. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körtidsfel och/eller påståendefel. Packa alltid in denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 183
url: /sv/system.drawing/pen/
---
## Pen klass


Representerar egenskaper såsom färg, bredd osv. för de linjer och kurvor som ritas. Objekt av denna klass bör bara allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körtidsfel och/eller påståendefel. Packa alltid in denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Pen : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | Returnerar en kopia av det aktuella objektet. |
| void [Dispose](./dispose/)() | Frigör alla resurser som förvärvats av det aktuella objektet. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypens objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | Returnerar ett värde som indikerar justeringen av det aktuella [Pen](./)-objektet. |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | Returnerar detta pennas [Brush](../brush/)-objekt. |
| [Color](../color/) [get_Color](./get_color/)() const | Returnerar detta pennas färg. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | Returnerar en array av värden som specificerar en sammansatt penna. |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | Returnerar ett värde som indikerar änden som används i båda ändarna av en streckad linje. |
| **float** [get_DashOffset](./get_dashoffset/)() const | Returnerar avståndet från linjens början till början av ett streckmönster. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | Returnerar en array som indikerar ett anpassat streckmönster i en streckad linje. |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | Returnerar ett värde som indikerar streckstilen för det aktuella [Pen](./)-objektet. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | Returnerar ett värde som indikerar avslutningslinjekappen för det aktuella [Pen](./)-objektet. |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | Returnerar ett värde som indikerar hur linjer ritade av detta [Pen](./)-objekt förenas. |
| **float** [get_MiterLimit](./get_miterlimit/)() const | Returnerar gränsen för tjockleken på föreningen på ett snedklippt hörn. |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | INTE IMPLEMENTERAD. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | Returnerar ett värde som indikerar startlinjekappen för det aktuella [Pen](./)-objektet. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | Returnerar en kopia av ett Matrix-objekt som specificerar de geometriska transformationerna för den penna som representeras av det aktuella objektet. |
| **float** [get_Width](./get_width/)() const | Returnerar bredden på det aktuella [Pen](./)-objektet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen beskriven av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning av C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Multiplicerar det aktuella objektets transformationsmatris med den specificerade matrisen. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
|  [Pen](./pen/)(const [Color](../color/)\&) | Konstrukterar ett nytt [Pen](./)-objekt som representerar den angivna färgen. |
|  [Pen](./pen/)(const [Color](../color/)\&, **float**) | Konstrukterar ett nytt [Pen](./)-objekt som representerar den angivna färgen och bredden. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Konstrukterar ett nytt [Pen](./)-objekt och initierar det med det specificerade [Brush](../brush/)-objektet. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | Konstrukterar ett nytt [Pen](./)-objekt och initierar det med det specificerade [Brush](../brush/)-objektet. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [ResetTransform](./resettransform/)() | Återställer det aktuella objektets transformationsmatris så att den blir en enhetsmatris. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | Ställer in justeringen för det aktuella [Pen](./)-objektet. |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Ställer in detta pennas [Brush](../brush/)-objekt. |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | Ställer in detta pennas färg. |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Ställer in en array av värden som specificerar en sammansatt penna. |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Ställer in den anpassade slutlinjekappen. |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Ställer in den anpassade startlinjekappen. |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | Ställer in ett värde som specificerar änden som används i båda ändarna av en streckad linje. |
| void [set_DashOffset](./set_dashoffset/)(**float**) | Ställer in avståndet från linjens början till början av ett streckmönster. |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Ställer in en array som specificerar ett anpassat streckmönster i en streckad linje. Arrayen består av tal som specificerar längderna på alternerande streck och mellanrum. |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | Ställer in ett värde som specificerar streckstilen för det aktuella [Pen](./)-objektet. |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Ställer in avslutningslinjekappen för det aktuella [Pen](./)-objektet. |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | Ställer in ett värde som specificerar hur linjer ritade av detta [Pen](./)-objekt förenas. |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | Ställer in gränsen för tjockleken på föreningen på ett snedklippt hörn. |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Ställer in startlinjekappen för det aktuella [Pen](./)-objektet. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Ställer in ett Matrix-objekt som specificerar de geometriska transformationerna för den penna som representeras av det aktuella objektet. |
| void [set_Width](./set_width/)(**float**) | Ställer in bredden på det aktuella [Pen](./)-objektet. |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | INTE IMPLEMENTERAD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'th mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Översätter den lokala geometriska transformationen med de specificerade dimensionerna i den specificerade ordningen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning av C# lock()-sats uppslagning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)