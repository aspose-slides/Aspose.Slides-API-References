---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides C++ API-referencia
description: A Pptx szövegből HTML kinyeréséhez használható beállítások.
type: docs
weight: 482
url: /hu/aspose.slides.export/itexttohtmlconversionoptions/
---
## ITextToHtmlConversionOptions osztály


Options for extracting HTML from the Pptx text.

```cpp
class ITextToHtmlConversionOptions : public virtual System::Object
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az érték típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **bool** [get_AddClipboardFragmentHeader](./get_addclipboardfragmentheader/)() | Visszaad egy értéket, amely jelzi, hogy a Vágólap fejlécek hozzáadandók-e. Olvasás: **bool**. |
| virtual [System::String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Visszaadja a HTML kódolás nevét. Ez az érték a létrehozott HTML-fájlba kerül mentésre, de a hívó feladata, hogy biztosítsa a fájl mentését ebben a kódolásban. Olvasás: [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Export::ILinkEmbedController](../ilinkembedcontroller/)\> [get_LinkEmbedController](./get_linkembedcontroller/)() | Visszaad egy visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. Olvasás: [Export::ILinkEmbedController](../ilinkembedcontroller/). |
| virtual [Aspose::Slides::Export::TextInheritanceLimit](../textinheritancelimit/) [get_TextInheritanceLimit](./get_textinheritancelimit/)() | Visszaadja a szövegtulajdonságok öröklődési mélységét. Olvasás: [TextInheritanceLimit](../textinheritancelimit/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-olását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példányát képviseli-e a targetType által leírt típusnak. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolásépítését. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolásépítését. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat hivatkozás szerint. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat hivatkozás szerint. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként összehasonlítja az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| virtual void [set_AddClipboardFragmentHeader](./set_addclipboardfragmentheader/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a Vágólap fejlécek hozzáadandók-e. Írás: **bool**. |
| virtual void [set_EncodingName](./set_encodingname/)([System::String](../../system/string/)) | Beállítja a HTML kódolás nevét. Ez az érték a létrehozott HTML-fájlba kerül mentésre, de a hívó feladata, hogy biztosítsa a fájl mentését ebben a kódolásban. Írás: [System::String](../../system/string/). |
| virtual void [set_LinkEmbedController](./set_linkembedcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ILinkEmbedController](../ilinkembedcontroller/)\>) | Beállít egy visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. Írás: [Export::ILinkEmbedController](../ilinkembedcontroller/). |
| virtual void [set_TextInheritanceLimit](./set_textinheritancelimit/)([Aspose::Slides::Export::TextInheritanceLimit](../textinheritancelimit/)) | Beállítja a szövegtulajdonságok öröklődési mélységét. Írás: [TextInheritanceLimit](../textinheritancelimit/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett) állítja be. Lehetővé teszi a mutatók konténerekben való weak módra történő átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem kellene közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem kellene közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem kellene közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem kellene közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)