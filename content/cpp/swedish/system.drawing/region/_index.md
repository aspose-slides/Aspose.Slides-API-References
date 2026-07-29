---
title: Region
second_title: Aspose.Slides för C++ API-referens
description: "Representerar interioren av en grafisk form. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 261
url: /sv/system.drawing/region/
---
## Region klass

Representerar interioren av en grafisk form. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Förpaketera alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class Region : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Returnerar en kopia av det aktuella objektet. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Ersätter regionen som representeras av det aktuella objektet med den del av regionen som definieras av den angivna rektangeln som inte intersecterar med denna region. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Ersätter regionen som representeras av det aktuella objektet med den del av regionen som definieras av den angivna rektangeln som inte intersecterar med denna region. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersätter regionen som representeras av det aktuella objektet med den del av regionen som definieras av den angivna vägen som inte intersecterar med denna region. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersätter regionen som representeras av det aktuella objektet med den del av den angivna regionen som inte intersecterar med denna region. |
| void [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Avgör om den angivna regionen är identisk med den region som representeras av det aktuella objektet på den angivna ritytan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-liknande flyttalssammanlikning där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-liknande flyttalssammanlikning där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av exkludering av den region som definieras av den angivna rektangeln från den. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av exkludering av den region som definieras av den angivna rektangeln från den. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av exkludering av den region som definieras av den angivna vägen från den. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av exkludering av den angivna regionen från den. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Hämtar en [RectangleF](../rectanglef/)-struktur som representerar en rektangel som begränsar denna [Region](./) på ritytan för ett [Graphics](../graphics/)-objekt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Returnerar ett RegionData-objekt som innehåller data som definierar regionen som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Returnerar en array av [RectangleF](../rectanglef/)-strukturer som approximerar denna [Region](./) efter att den angivna matristransformeringen har tillämpats. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objekttypen. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och en region definierad av den angivna rektangeln. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och en region definierad av den angivna rektangeln. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och en region definierad av den angivna vägen. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och den angivna regionen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Avgör om regionen som representeras av det aktuella objektet har ett tomt inre på den angivna ritytan. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Avgör om regionen som representeras av det aktuella objektet har ett oändligt inre på den angivna ritytan. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Avgör om den angivna punkten ligger inom regionen som representeras av det aktuella objektet. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Avgör om den angivna punkten ligger inom regionen som representeras av det aktuella objektet. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Avgör om någon del av den angivna rektangeln ligger inom regionen som representeras av det aktuella objektet. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Avgör om någon del av den angivna rektangeln ligger inom regionen som representeras av det aktuella objektet. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Avgör om den angivna punkten ligger inom regionen som representeras av det aktuella objektet med hjälp av den angivna grafik. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Avgör om den angivna punkten ligger inom regionen som representeras av det aktuella objektet med hjälp av den angivna grafik. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Avgör om någon del av den angivna rektangeln ligger inom regionen som representeras av det aktuella objektet med hjälp av den angivna grafik. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Avgör om någon del av den angivna rektangeln ligger inom regionen som representeras av det aktuella objektet med hjälp av den angivna grafik. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Avgör om den angivna punkten ligger inom regionen som representeras av det aktuella objektet. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Avgör om den angivna punkten ligger inom regionen som representeras av det aktuella objektet med hjälp av den angivna grafik. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-statement. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| void [MakeEmpty](./makeempty/)() | Initierar det aktuella objektet med ett tomt inre. |
| void [MakeInfinite](./makeinfinite/)() | Initierar detta regionobjekt med ett oändligt inre. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingen data, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr genom referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
|  [Region](./region/)() | Skapar en ny instans av [Region](./)-klassen. |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Skapar en ny instans av [Region](./)-klassen som representerar en region definierad av den angivna rektangeln. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Skapar en ny instans av [Region](./)-klassen som representerar en region definierad av den angivna rektangeln. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Skapar en ny instans av [Region](./)-klassen som representerar en region definierad av den angivna vägen. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Skapar en ny instans av [Region](./)-klassen som representerar en region definierad av det angivna RegionData-objektet. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-te mallargumentet till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transformerar denna region med den angivna matrisen. |
| void [Transform](./transform/)(const SkMatrix\&) | Transformerar denna region med den angivna matrisen. |
| void [Translate](./translate/)(int, int) | Flyttar regionens koordinater med den angivna mängden. |
| void [Translate](./translate/)(**float**, **float**) | Flyttar regionens koordinater med den angivna mängden. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av föreningsoperationen av denna region och en region definierad av den angivna rektangeln. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av föreningsoperationen av denna region och en region definierad av den angivna rektangeln. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av föreningsoperationen av denna region och en region definierad av den angivna vägen. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av föreningsoperationen av denna region och den angivna regionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-statement upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Ersätter regionen som representeras av det aktuella objektet med de delar av denna region och den region som definieras av den angivna rektangeln som inte intersecterar. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Ersätter regionen som representeras av det aktuella objektet med de delar av denna region och den region som definieras av den angivna rektangeln som inte intersecterar. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersätter regionen som representeras av det aktuella objektet med de delar av denna region och den region som definieras av den angivna vägen som inte intersecterar. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersätter regionen som representeras av det aktuella objektet med de delar av denna region och den angivna regionen som inte intersecterar. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
| virtual  [~Region](./~region/)() | Destruktor. |
## Se också

* Klass [Object](../../system/object/)
* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)