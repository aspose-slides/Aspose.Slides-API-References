---
title: HttpUtility
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Služební třída, která kóduje a dekóduje části URL do a z hexových únikových fragmentů.
type: docs
weight: 40
url: /cs/system.web/httputility/
---
## HttpUtility třída

Služební třída, která kóduje a dekóduje části URL do a z hexových únikových fragmentů.

```cpp
class HttpUtility : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače přidruženou k objektu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| static [String](../../system/string/) [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&) | Dekóduje fragment HTML. |
| static void [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Dekóduje fragment HTML. |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&) | Kóduje fragment HTML. |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Kóduje fragment HTML. |
| static void [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Kóduje fragment HTML. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# příkazu lock(). Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt strážce. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# příkazu lock(). Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt strážce. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/)) | Dekóduje fragment URI ze řetězce. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Dekóduje fragment URI ze řetězce. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Dekóduje fragment URI z pole bytů. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Dekóduje fragment URI z pole bytů. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Dekóduje fragment URI z pole bytů. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&) | Dekóduje fragment URI z řetězce bytů. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Dekóduje fragment URI ze řetězce. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekóduje fragment URI z pole bytů. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/)) | Zakóduje fragment URI. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/), const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Zakóduje fragment URI. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Zakóduje fragment URI. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zakóduje fragment URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&) | Zakóduje fragment URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Zakóduje fragment URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Zakóduje fragment URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zakóduje fragment URI. |
| static [String](../../system/string/) [UrlEncodeUnicode](./urlencodeunicode/)(const [String](../../system/string/)\&) | Zakóduje fragment URI pomocí Unicode. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const [String](../../system/string/)\&) | Zakóduje fragment URI pomocí Unicode. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Class [Object](../../system/object/)
* Namespace [System::Web](../)
* Library [Aspose.Slides](../../)