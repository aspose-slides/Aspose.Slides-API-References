---
title: Matrix
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en 3x3-matris som definierar transformoperations. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertion-fel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 118
url: /sv/system.drawing.drawing2d/matrix/
---
## Matrix klass

Representerar en 3x3-matris som definierar transformoperations. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Matrix : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Skapar en kopia av det aktuella objektet. |
| void [Dispose](./dispose/)() | Frigir alla operativsystemresurser som förvärvats av det aktuella objektet. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Testar om det angivna objektet är en [Matrix](./) och är identiskt med detta objekt. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Returnerar en array som innehåller matrisens element i följande ordning: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Bestämmer om matrisen som representeras av det aktuella objektet är en identitetsmatris. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Bestämmer om matrisen som representeras av det aktuella objektet är inverterbar. |
| **float** [get_OffsetX](./get_offsetx/)() const | Returnerar X-översättningsvärdet för matrisen som representeras av det aktuella objektet. |
| **float** [get_OffsetY](./get_offsety/)() const | Returnerar Y-översättningsvärdet för matrisen som representeras av det aktuella objektet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenskontarrens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| void [Invert](./invert/)() | Inverterar matrisen som representeras av det aktuella objektet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
|  [Matrix](./matrix/)() | Skapar en ny instans av klassen [Matrix](./) som representerar en identitetsmatris. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Skapar en ny instans av klassen [Matrix](./) och initierar den med de angivna värdena. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Skapar en ny instans av klassen [Matrix](./) för den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Skapar en ny instans av klassen [Matrix](./) för den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Multiplicerar matrisen som representeras av det aktuella objektet med den angivna matrisen. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Multiplicerar matrisen som representeras av det aktuella objektet med den angivna matrisen. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med det angivna värdet. |
| void [Reset](./reset/)() | Återställer matrisen som representeras av det aktuella objektet så att den blir en identitetsmatris. |
| void [Rotate](./rotate/)(**float**) | Roterar matrisen som representeras av det aktuella objektet medurs med den angivna vinkeln. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Roterar matrisen som representeras av det aktuella objektet medurs runt origo med den angivna vinkeln. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Roterar matrisen som representeras av det aktuella objektet medurs runt den angivna punkten med den angivna vinkeln. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Roterar matrisen som representeras av det aktuella objektet medurs runt den angivna punkten med den angivna vinkeln. |
| void [Scale](./scale/)(**float**, **float**) | Tillämpar den angivna skalningsvektorn på matrisen som representeras av det aktuella objektet. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Tillämpar den angivna skalningsvektorn på matrisen som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Shear](./shear/)(**float**, **float**) | Tillämpar den angivna shear-vektorn på matrisen som representeras av det aktuella objektet. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Tillämpar den angivna shear-vektorn på matrisen som representeras av det aktuella objektet. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Tillämpar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Tillämpar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Tillämpar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Tillämpar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Tillämpar endast skala- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Tillämpar endast skala- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Tillämpar endast skala- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Tillämpar endast skala- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| void [Translate](./translate/)(**float**, **float**) | Tillämpar den angivna transvektorn på matrisen som representeras av det aktuella objektet. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Tillämpar den angivna transvektorn på matrisen som representeras av det aktuella objektet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Multiplicerar varje vektor i en array med matrisen som representeras av det aktuella objektet. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Multiplicerar varje vektor i en array med matrisen som representeras av det aktuella objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Matrix](./~matrix/)() | Destruktör. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Drawing::Drawing2D](../)
* Bibliotek [Aspose.Slides](../../)