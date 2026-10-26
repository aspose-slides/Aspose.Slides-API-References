---
title: ImageFormat
second_title: "Aspose.Slides för C++ API-referens"
description: "Representerar bildens filformat. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 131
url: /sv/system.drawing.imaging/imageformat/
---
## ImageFormat klass

Representerar bildens filformat. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assertfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ImageFormat : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | Bestämmer om bildformaten som representeras av det nuvarande och det angivna objektet är lika. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stilens jämförelse av flyttal där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stilens jämförelse av flyttal där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar bitmap-bildformatet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar det förbättrade metafilformatet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar Exchangeable [Image](../../system.drawing/image/) File (Exif)-formatet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar [Graphics](../../system.drawing/graphics/) Interchange Format (GIF)-bildformatet. |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | Returnerar GUID-en som är associerad med bildformatet som representeras av det aktuella objektet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar [Windows](../../system.windows/)-ikonbildformatet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar Joint Photographic Experts Group (JPEG)-bildformatet. |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar formatet för en bitmap i minnet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG)-bildformatet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar Tagged [Image](../../system.drawing/image/) File Format (TIFF)-bildformatet. |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar [Windows](../../system.windows/)-metafil (WMF)-bildformatet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | Skapar en instans av [ImageFormat](./)-klassen som representerar ett bildformat som är associerat med den angivna GUID-en. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaketobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde av det delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar det delade referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar det delade referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | Konverterar detta [ImageFormat](./)-objekt till en människoläsbar sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaketobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Drawing::Imaging](../)
* Bibliotek [Aspose.Slides](../../)