---
title: Uri
second_title: Aspose.Slides for C++ API Reference
description: "Unified resource identifier. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 1327
url: /system/uri/
---
## Uri class


Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Determines the type of the specified host name. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Determines if the specified scheme is valid. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Compares the specified [Uri](./) objects using the specified comparison rules. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Determines if the URIs represented by the current and specified objects are equal. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compares objects using C# [Object.Equals](../object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Converts a string to its escaped representation. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Converts a URI string to its escaped representation. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Gets the decimal value of a hexadecimal digit. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Returns the absolute path of the URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Returns the absolute URI. |
| [String](../string/) [get_Authority](./get_authority/)() const | Returns the host name and the port number for a server. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Returns an unescaped host name. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Returns the escaped URI fragment. |
| [String](../string/) [get_Host](./get_host/)() const | Returns the host name. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Returns the host name type. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Returns an International Domain Name of the host. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Determines if the URI represented by the current object is absolute. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Determines if the URI represented by the current object has default port for the URI's scheme. |
| **bool** [get_IsFile](./get_isfile/)() const | Determines if the URI represented by the current object is a file. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Determines if the URI represented by the current object references a local host. |
| **bool** [get_IsUnc](./get_isunc/)() const | Determines if the URI represented by the current object is a UNC path. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Returns the operating system representation of the file name referenced by the URI represented by the current object. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Returns the URI string that was passed to the constructor when current object was constructed. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Returns the absolute path and query components of the URI represented by the current object separated by a question mark (?). |
| **int32_t** [get_Port](./get_port/)() const | Returns the port number of the URI represented by the current object. |
| [String](../string/) [get_Query](./get_query/)() const | Returns the query information included in the URI represented by the current object. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Returns the scheme of the URI represented by the current object. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Returns an array of strings containing the path segments of the URI represented by the current object. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Determines if the URI string passed to the constructor of the current object was fully escaped. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Returns a uer name, password and other user information associated with the URI represented by the current object. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Returns the specified components of the URI represented by the current object using the specified escaping. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Gets reference counter data structure associated with the object. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Gets the hash code for the URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Returns the specified portion of the URI represented by the current object. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../object/gettype/) call. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Returns a hexadecimal equivalent of the specified character. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Converts the specified hexadecimal representation of a character to a character. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Determines of the URI represented by the current [Uri](./) object is a base of URI represented by the specified [Uri](./) object. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Determines if the specified character represents a valid hexadecimal digit. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Determines if a character in the specified string at the specified position is hexadecimal encoded. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indicates whether the string used to construct this [Uri](./) was well-formed and is not required to be further escaped. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Determines if the specified string is a well-formed URI. |
| void [Lock](../object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determines the difference between two [Uri](./) instances. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determines the difference between URIs represented by the current and the specified [Uri](./) objects. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Returns the string representation of the URI represented by the current object. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constructs a [Uri](./) object that represents the specified URI; an argument specifies the URI kind. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constructs an [Uri](./) abject from the specified [Uri](./) object representing the base URI and the string representation of relative URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constructs an [Uri](./) abject from the specified base and relative URIs. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implements C# typeof([System.Object](../object/)) construct. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Unescapes the specified escaped string. |
| void [Unlock](../object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
|  [Uri](./uri/)(const [String](../string/)\&) | Constructs a [Uri](./) object that represents the specified URI. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Constructs a [Uri](./) object that represents the specified URI; an argument specifies if the URI should be escaped. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Constructs an [Uri](./) abject from the specified [Uri](./) object representing the base URI and the string representation of relative URI; an argument specifies if the URI should be escaped. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Constructs a [Uri](./) object that represents the specified URI; an argument specifies the URI kind. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Constructs an [Uri](./) abject from the specified base and relative URIs. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constructs an [Uri](./) abject from the specified base and relative URIs. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destroys object. Frees all internal data structures. |
## Fields

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Specifies the characters that separate the communication protocol scheme from the address portion of the [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Specifies that the [Uri](./) is a pointer to a file. |
| static [UriSchemeFtp](./urischemeftp/) | Specifies that the [Uri](./) is accessed through the File Transfer Protocol. |
| static [UriSchemeGopher](./urischemegopher/) | Specifies that the [Uri](./) is accessed through the Gopher protocol. |
| static [UriSchemeHttp](./urischemehttp/) | Specifies that the [Uri](./) is accessed through the Hypertext Transfer Protocol. |
| static [UriSchemeHttps](./urischemehttps/) | Specifies that the [Uri](./) is accessed through the Secure Hypertext Transfer Protocol. |
| static [UriSchemeMailto](./urischememailto/) | Specifies that the [Uri](./) is an email address and is accessed through the Simple Mail Transport Protocol. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Specifies that the [Uri](./) is accessed through the NetPipe scheme used by [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Specifies that the [Uri](./) is accessed through the NetTcp scheme used by [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Specifies that the [Uri](./) is an Internet news group and is accessed through the Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Specifies that the [Uri](./) is an Internet news group and is accessed through the Network News Transport Protocol. |
## Remarks



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
This code example produces the following output:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)