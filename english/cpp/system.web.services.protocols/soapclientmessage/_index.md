---
title: SoapClientMessage
second_title: Aspose.Slides for C++ API Reference
description: "Represents the data in a SOAP request sent or a SOAP response received. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 40
url: /cpp/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage class


Represents the data in a SOAP request sent or a SOAP response received. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## Methods

| Method | Description |
| --- | --- |
| void [CollectHeaders](../soapmessage/collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | Sets the internal collection of the SOAP headers. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](../soapmessage/findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | Find the header mapping by specified header type. |
| [String](../../system/string/) [get_Action](./get_action/)() override | Returns a value of the 'SOAPAction' attribute. |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\> [get_Client](./get_client/)() | Returns an instance of the client proxy class. |
| [String](../../system/string/) [get_ContentEncoding](../soapmessage/get_contentencoding/)() | Gets a value of the 'Content-Encoding' header. |
| [String](../../system/string/) [get_ContentType](../soapmessage/get_contenttype/)() | Gets a value of the 'Content-Type' header. |
| [SoapException](../soapexception/) [get_Exception](../soapmessage/get_exception/)() | Gets the exception that is thrown by the XML [Web](../../system.web/) service method. |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](../soapmessage/get_headers/)() | Returns the collection of the SOAP headers. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](../soapmessage/get_inparameters/)() | Gets the parameters that are passed into the XML [Web](../../system.web/) service method. |
| **bool** [get_IsSoap12](../soapmessage/get_issoap12/)() | Returns a value that indicates if SOAP version 1.2 is used. |
| virtual **bool** [get_OneWay](./get_oneway/)() | Returns a value that indicates if a client doesn't wait for a server to finish processing a method. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](../soapmessage/get_outparameters/)() | Gets the output parameters passed into the XML [Web](../../system.web/) service method. |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() override | Returns the SOAP version that is used. |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](../soapmessage/get_stage/)() | Gets the processing stage of a SOAP message. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](../soapmessage/get_stream/)() | Gets the stream that contains the SOAP message data. |
| [String](../../system/string/) [get_Url](./get_url/)() override | Returns the XML [Web](../../system.web/) service URL. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](../soapmessage/getinparametervalue/)(**int32_t**) | Gets the input parameter value at the specified index. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](../soapmessage/getoutparametervalue/)(**int32_t**) | Gets the output parameter value at the specified index. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](../soapmessage/getreturnvalue/)() | Gets the return value of the XML [Web](../../system.web/) service method. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_ContentEncoding](../soapmessage/set_contentencoding/)([String](../../system/string/)) | Sets a value of the 'Content-Encoding' header. |
| void [set_ContentType](../soapmessage/set_contenttype/)([String](../../system/string/)) | Sets a value of the 'Content-Type' header. |
| void [set_InParameters](../soapmessage/set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Sets the parameters that are passed into the XML [Web](../../system.web/) service method. |
| void [set_InternalStream](../soapmessage/set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sets the stream that contains the SOAP message data. |
| void [set_OutParameters](../soapmessage/set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Sets the output parameters passed into the XML [Web](../../system.web/) service method. |
| void [SetException](../soapmessage/setexception/)([SoapException](../soapexception/)) | Sets the exception that is thrown by the XML [Web](../../system.web/) service method. |
| void [SetHeaders](../soapmessage/setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | Sets the collection of the SOAP headers. |
| void [SetStage](../soapmessage/setstage/)([SoapMessageStage](../soapmessagestage/)) | Sets the processing stage of the SOAP message. |
| void [SetStream](../soapmessage/setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sets the stream that contains the SOAP message data. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [SoapClientMessage](./soapclientmessage/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapMethodStubInfo\>, [String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Constructs a new instance. |
|  [SoapMessage](../soapmessage/soapmessage/)() | Constructs a new instance. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [UpdateHeaderValues](../soapmessage/updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | Updates the internal collection of the SOAP headers. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [SoapMessage](../soapmessage/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.Slides](../../)