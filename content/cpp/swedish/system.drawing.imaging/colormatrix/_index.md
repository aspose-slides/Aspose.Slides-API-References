---
title: ColorMatrix
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en 5x5-matris som innehåller koordinaterna för färgrymden RGBAW. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Inslut alltid denna klass i en System::SmartPtr pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 27
url: /sv/system.drawing.imaging/colormatrix/
---
## ColorMatrix klass

Representerar en 5x5-matris som innehåller koordinaterna för färgrymden RGBAW. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktion. Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Inslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class ColorMatrix : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Skapar en ny instans av [ColorMatrix](./) klass och initierar den med värdena för identitetsmatrisen. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Skapar en ny instans av [ColorMatrix](./) klass och initierar den med de angivna värdena. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-stil flyttalssammanlikning där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-stil flyttalssammanlikning där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **float** [get_Matrix00](./get_matrix00/)() const | Returnerar ett värde i rad 0 och kolumn 0. |
| **float** [get_Matrix01](./get_matrix01/)() const | Returnerar ett värde i rad 0 och kolumn 1. |
| **float** [get_Matrix02](./get_matrix02/)() const | Returnerar ett värde i rad 0 och kolumn 2. |
| **float** [get_Matrix03](./get_matrix03/)() const | Returnerar ett värde i rad 0 och kolumn 3. |
| **float** [get_Matrix04](./get_matrix04/)() const | Returnerar ett värde i rad 0 och kolumn 4. |
| **float** [get_Matrix10](./get_matrix10/)() const | Returnerar ett värde i rad 1 och kolumn 0. |
| **float** [get_Matrix11](./get_matrix11/)() const | Returnerar ett värde i rad 1 och kolumn 1. |
| **float** [get_Matrix12](./get_matrix12/)() const | Returnerar ett värde i rad 1 och kolumn 2. |
| **float** [get_Matrix13](./get_matrix13/)() const | Returnerar ett värde i rad 1 och kolumn 3. |
| **float** [get_Matrix14](./get_matrix14/)() const | Returnerar ett värde i rad 1 och kolumn 4. |
| **float** [get_Matrix20](./get_matrix20/)() const | Returnerar ett värde i rad 2 och kolumn 0. |
| **float** [get_Matrix21](./get_matrix21/)() const | Returnerar ett värde i rad 2 och kolumn 1. |
| **float** [get_Matrix22](./get_matrix22/)() const | Returnerar ett värde i rad 2 och kolumn 2. |
| **float** [get_Matrix23](./get_matrix23/)() const | Returnerar ett värde i rad 2 och kolumn 3. |
| **float** [get_Matrix24](./get_matrix24/)() const | Returnerar ett värde i rad 2 och kolumn 4. |
| **float** [get_Matrix30](./get_matrix30/)() const | Returnerar ett värde i rad 3 och kolumn 0. |
| **float** [get_Matrix31](./get_matrix31/)() const | Returnerar ett värde i rad 3 och kolumn 1. |
| **float** [get_Matrix32](./get_matrix32/)() const | Returnerar ett värde i rad 3 och kolumn 2. |
| **float** [get_Matrix33](./get_matrix33/)() const | Returnerar ett värde i rad 3 och kolumn 3. |
| **float** [get_Matrix34](./get_matrix34/)() const | Returnerar ett värde i rad 3 och kolumn 4. |
| **float** [get_Matrix40](./get_matrix40/)() const | Returnerar ett värde i rad 4 och kolumn 0. |
| **float** [get_Matrix41](./get_matrix41/)() const | Returnerar ett värde i rad 4 och kolumn 1. |
| **float** [get_Matrix42](./get_matrix42/)() const | Returnerar ett värde i rad 4 och kolumn 2. |
| **float** [get_Matrix43](./get_matrix43/)() const | Returnerar ett värde i rad 4 och kolumn 3. |
| **float** [get_Matrix44](./get_matrix44/)() const | Returnerar ett värde i rad 4 och kolumn 4. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenräknare-datatypen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/) anrop. |
| **float** [idx_get](./idx_get/)(int, int) | Returnerar ett värde på den angivna rad och kolumn. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Sätter det angivna värdet på den angivna platsen i matrisen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenräknare med angivet värde. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Sätter ett värde i rad 0 och kolumn 0. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Sätter ett värde i rad 0 och kolumn 1. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Sätter ett värde i rad 0 och kolumn 2. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Sätter ett värde i rad 0 och kolumn 3. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Sätter ett värde i rad 0 och kolumn 4. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Sätter ett värde i rad 1 och kolumn 0. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Sätter ett värde i rad 1 och kolumn 1. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Sätter ett värde i rad 1 och kolumn 2. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Sätter ett värde i rad 1 och kolumn 3. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Sätter ett värde i rad 1 och kolumn 4. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Sätter ett värde i rad 2 och kolumn 0. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Sätter ett värde i rad 2 och kolumn 1. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Sätter ett värde i rad 2 och kolumn 2. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Sätter ett värde i rad 2 och kolumn 3. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Sätter ett värde i rad 2 och kolumn 4. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Sätter ett värde i rad 3 och kolumn 0. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Sätter ett värde i rad 3 och kolumn 1. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Sätter ett värde i rad 3 och kolumn 2. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Sätter ett värde i rad 3 och kolumn 3. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Sätter ett värde i rad 3 och kolumn 4. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Sätter ett värde i rad 4 och kolumn 0. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Sätter ett värde i rad 4 och kolumn 1. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Sätter ett värde i rad 4 och kolumn 2. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Sätter ett värde i rad 4 och kolumn 3. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Sätter ett värde i rad 4 och kolumn 4. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referenräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/) metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/)) konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [Object](../../system/object/)
* Namnrymd [System::Drawing::Imaging](../)
* Bibliotek [Aspose.Slides](../../)