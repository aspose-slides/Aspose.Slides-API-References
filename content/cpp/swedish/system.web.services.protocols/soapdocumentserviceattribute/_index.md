---
title: SoapDocumentServiceAttribute
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in standardformatet för SOAP-förfrågningar och -svar. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningstidfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 66
url: /sv/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute klass

Ställer in standardformatet för SOAP-förfrågningar och svar. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningstidfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | Hämtar ett värde som indikerar om parametrar är inkapslade i ett enda XML-element under 'Body'-elementet. |
| [SoapServiceRoutingStyle](../soapserviceroutingstyle/) [get_RoutingStyle](./get_routingstyle/)() | Hämtar ett värde som visar hur SOAP-meddelandena dirigeras till tjänsten. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | Hämtar parameterformateringen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Returnerar ett anpassat attribut av en angiven typ som appliceras på den angivna typen. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Returnerar alla anpassade attribut som appliceras på den angivna typen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satstemet. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, den initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, den initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | Ställer in ett värde som indikerar om parametrar är inkapslade i ett enda XML-element under 'Body'-elementet. |
| void [set_RoutingStyle](./set_routingstyle/)([SoapServiceRoutingStyle](../soapserviceroutingstyle/)) | Ställer in ett värde som visar hur SOAP-meddelandena dirigeras till tjänsten. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Ställer in parameterformateringen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:te mallargumentet till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svag modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
|  [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | Skapar en ny instans. |
|  [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Skapar en ny instans. |
|  [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/), [SoapParameterStyle](../soapparameterstyle/)) | Skapar en ny instans. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsningens upplåsning enligt C# lock()-satstemet. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Attribute](../../system/attribute/)
* Namnrymd [System::Web::Services::Protocols](../)
* Bibliotek [Aspose.Slides](../../)