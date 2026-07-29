---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides för C++ API-referens
description: "Anger att alla SOAP-meddelanden som skickas eller returneras från metoden använder dokumentformatering. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller asserts. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 53
url: /sv/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute klass


Anger att alla SOAP-meddelanden som passerar eller returneras från metoden använder dokumentformatering. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika trots att enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika trots att enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [String](../../system/string/) [get_Action](./get_action/)() | Hämtar värdet på attributet 'SOAPAction'. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | Hämtar bindningen för vilken en XML-webbtjänstmetod implementerar en operation. |
| **bool** [get_OneWay](./get_oneway/)() | Hämtar ett värde som indikerar om en klient inte väntar på att servern ska slutföra bearbetningen av en metod. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | Hämtar ett värde som indikerar om parametrar är inkapslade i ett enda XML-element under 'Body'-elementet. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | Hämtar namnet på XML-elementet som är associerat med SOAP-begäran, vilket definieras i en tjänstebeskrivning som en operation. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | Hämtar namnrymden som är associerad med SOAP-begäran. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | Hämtar namnet på XML-elementet som är associerat med SOAP-svaret. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | Hämtar namnrymden som är associerad med SOAP-svaret. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | Hämtar ett värde som bestämmer meddelandekodningsmetoden. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar datastrukturen för referenstillräknaren som är associerad med objektet. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Returnerar ett anpassat attribut av en specificerad typ som tillämpas på den specificerade typen. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Returnerar alla anpassade attribut som tillämpas på den specificerade typen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakterobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenstillräknare med angivet värde. |
| void [set_Action](./set_action/)([String](../../system/string/)) | Sätter ett värde för attributet 'SOAPAction'. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | Sätter bindningen för vilken en XML-webbtjänstmetod implementerar en operation. |
| void [set_OneWay](./set_oneway/)(**bool**) | Sätter ett värde som indikerar om klienten inte väntar på att servern ska slutföra bearbetningen av en metod. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | Sätter ett värde som indikerar om parametrar är inkapslade i ett enda XML-element under 'Body'-elementet. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | Sätter namnet på XML-elementet som är associerat med SOAP-begäran, vilket definieras i en tjänstebeskrivning som en operation. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | Sätter namnrymden som är associerad med SOAP-begäran. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | Sätter namnet på XML-elementet som är associerat med SOAP-svaret. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | Sätter namnrymden som är associerad med SOAP-svaret. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Sätter ett värde som bestämmer meddelandekodningsmetoden. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referenstillräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenstillräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenstillräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Konstruerar en ny instans. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | Konstruerar en ny instans. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakterobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenstillräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenstillräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Attribute](../../system/attribute/)
* Namnrymd [System::Web::Services::Protocols](../)
* Bibliotek [Aspose.Slides](../../)