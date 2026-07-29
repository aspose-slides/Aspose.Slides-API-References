---
title: IConvertible
second_title: Aspose.Slides för C++ API-referens
description: "Definierar metoder som konverterar värdet av den implementerande referens- eller värdetypen till en common language runtime-typ som har ett motsvarande värde. Objekt av den här klassen bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assertionsfel. Wrappa alltid den här klassen i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 937
url: /sv/system/iconvertible/
---
## IConvertible klass

Definierar metoder som konverterar värdet av den implementerade referens- eller värdetypen till en Common Language Runtime-typ som har ett motsvarande värde. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller assert-fel. Wrappa alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class IConvertible : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Möjliggör hasning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar det faktiska typen av objektet. Analog till C# [System.Object.GetType()](../object/gettype/)-anrop. |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | Returnerar typkoden för den här instansen. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande [Boolean](../boolean/)-värde med den angivna kultur-specifika formateringsinformationen. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 8-bitars uint32_teger med den angivna kultur-specifika formateringsinformationen. |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande Unicode-tecken med den angivna kultur-specifika formateringsinformationen. |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande [System::DateTime](../datetime/) med den angivna kultur-specifika formateringsinformationen. |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande [System::Decimal](../decimal/)-nummer med den angivna kultur-specifika formateringsinformationen. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande dubbelprecisionsflyttal med den angivna kultur-specifika formateringsinformationen. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 16-bitars signed integer med den angivna kultur-specifika formateringsinformationen. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 32-bitars signed integer med den angivna kultur-specifika formateringsinformationen. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 64-bitars signed integer med den angivna kultur-specifika formateringsinformationen. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 8-bitars signed integer med den angivna kultur-specifika formateringsinformationen. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande enkelprecisionsflyttal med den angivna kultur-specifika formateringsinformationen. |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande [System::String](../string/) med den angivna kultur-specifika formateringsinformationen. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analog till C# [Object.ToString()](../object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till en [System::Object](../object/) av den angivna System::Type som har ett motsvarande värde, med den angivna kultur-specifika formateringsinformationen. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 16-bitars uint32_teger med den angivna kultur-specifika formateringsinformationen. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 32-bitars uint32_teger med den angivna kultur-specifika formateringsinformationen. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Konverterar värdet av denna instans till ett motsvarande 64-bitars uint32_teger med den angivna kultur-specifika formateringsinformationen. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktion. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [Object](../object/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)