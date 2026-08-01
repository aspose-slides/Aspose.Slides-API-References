---
title: SoapMessage
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het SOAP-bericht voor. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 131
url: /nl/system.web.services.protocols/soapmessage/
---
## SoapMessage klasse


Stelt de SOAP-bericht voor. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class SoapMessage : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [CollectHeaders](./collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | Stelt de interne verzameling van de SOAP-headers in. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](./findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | Zoekt de header-mapping op basis van het opgegeven headertype. |
| virtual [String](../../system/string/) [get_Action](./get_action/)() | Geeft een waarde van het 'SOAPAction'-attribuut terug. |
| [String](../../system/string/) [get_ContentEncoding](./get_contentencoding/)() | Haalt een waarde van de 'Content-Encoding'-header op. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() | Haalt een waarde van de 'Content-Type'-header op. |
| [SoapException](../soapexception/) [get_Exception](./get_exception/)() | Haalt de uitzondering op die door de XML [Web](../../system.web/) service-methode wordt geworpen. |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](./get_headers/)() | Geeft de verzameling van de SOAP-headers terug. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](./get_inparameters/)() | Haalt de parameters op die aan de XML [Web](../../system.web/) service-methode worden doorgegeven. |
| **bool** [get_IsSoap12](./get_issoap12/)() | Geeft een waarde terug die aangeeft of SOAP-versie 1.2 wordt gebruikt. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](./get_outparameters/)() | Haalt de output-parameters op die aan de XML [Web](../../system.web/) service-methode worden doorgegeven. |
| virtual [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | Geeft de gebruikte SOAP-versie terug. |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](./get_stage/)() | Haalt de verwerkingsfase van een SOAP-bericht op. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](./get_stream/)() | Haalt de stream op die de SOAP-berichtgegevens bevat. |
| virtual [String](../../system/string/) [get_Url](./get_url/)() | Geeft de XML [Web](../../system.web/) service-URL terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash van aangepaste objecten mogelijk. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](./getinparametervalue/)(**int32_t**) | Haalt de invoerparameterwaarde op op de opgegeven index. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](./getoutparametervalue/)(**int32_t**) | Haalt de outputparameterwaarde op op de opgegeven index. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](./getreturnvalue/)() | Haalt de retourwaarde op van de XML [Web](../../system.web/) service-methode. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_ContentEncoding](./set_contentencoding/)([String](../../system/string/)) | Stelt een waarde in voor de 'Content-Encoding'-header. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) | Stelt een waarde in voor de 'Content-Type'-header. |
| void [set_InParameters](./set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Stelt de parameters in die aan de XML [Web](../../system.web/) service-methode worden doorgegeven. |
| void [set_InternalStream](./set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Stelt de stream in die de SOAP-berichtgegevens bevat. |
| void [set_OutParameters](./set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Stelt de output-parameters in die aan de XML [Web](../../system.web/) service-methode worden doorgegeven. |
| void [SetException](./setexception/)([SoapException](../soapexception/)) | Stelt de uitzondering in die door de XML [Web](../../system.web/) service-methode wordt gegooid. |
| void [SetHeaders](./setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | Stelt de verzameling van de SOAP-headers in. |
| void [SetStage](./setstage/)([SoapMessageStage](../soapmessagestage/)) | Stelt de verwerkingsfase van het SOAP-bericht in. |
| void [SetStream](./setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Stelt de stream in die de SOAP-berichtgegevens bevat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Vermindert en geeft de gedeelde referentieteller terug. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
|  [SoapMessage](./soapmessage/)() | Construeert een nieuwe instantie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van het C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| void [UpdateHeaderValues](./updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | Werk de interne verzameling van de SOAP-headers bij. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Vermindert de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Web::Services::Protocols](../)
* Bibliotheek [Aspose.Slides](../../)