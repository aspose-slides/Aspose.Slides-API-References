---
title: GradientFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt ein Gradient-Format dar.
type: docs
weight: 1106
url: /de/aspose.slides/gradientformat/
---
## GradientFormat Klasse

Stellt ein Gradient-Format dar.

```cpp
class GradientFormat : public Aspose::Slides::PVIObject,
                       public Aspose::Slides::IGradientFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung von C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [Aspose::Slides::GradientDirection](../gradientdirection/) [get_GradientDirection](./get_gradientdirection/)() override | Gibt den Stil eines Gradienten zurück. Siehe [Slides::GradientDirection](../gradientdirection/). |
| [Aspose::Slides::GradientShape](../gradientshape/) [get_GradientShape](./get_gradientshape/)() override | Gibt die Form eines Gradienten zurück. Siehe [Slides::GradientShape](../gradientshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGradientStop](../igradientstop/)\> [get_GradientStop](./get_gradientstop/)(**int32_t**) override | Gibt einen Gradient-Stop am angegebenen Index zurück. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGradientStopCollection](../igradientstopcollection/)\> [get_GradientStops](./get_gradientstops/)() override | Gibt die Sammlung von Gradient-Stops zurück. Nur-Lesen [IGradientStopCollection](../igradientstopcollection/). |
| **float** [get_LinearGradientAngle](./get_lineargradientangle/)() override | Gibt den Winkel eines Gradienten zurück. Lesen **float**. |
| [NullableBool](../nullablebool/) [get_LinearGradientScaled](./get_lineargradientscaled/)() override | Bestimmt, ob ein Gradient skaliert ist. Lesen [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt das übergeordnete [IPresentationComponent](../ipresentationcomponent/) zurück. Nur-Lesen [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Gibt den Spiegelungsmodus für einen Gradient zurück. Lesen [Slides::TileFlip](../tileflip/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analogie zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analogie zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren mittels C# lock()-Statement. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wachobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| void [set_GradientDirection](./set_gradientdirection/)([Aspose::Slides::GradientDirection](../gradientdirection/)) override | Setzt den Stil eines Gradienten. Schreiben [Slides::GradientDirection](../gradientdirection/). |
| void [set_GradientShape](./set_gradientshape/)([Aspose::Slides::GradientShape](../gradientshape/)) override | Setzt die Form eines Gradienten. Schreiben [Slides::GradientShape](../gradientshape/). |
| void [set_LinearGradientAngle](./set_lineargradientangle/)(**float**) override | Setzt den Winkel eines Gradienten. Schreiben **float**. |
| void [set_LinearGradientScaled](./set_lineargradientscaled/)([NullableBool](../nullablebool/)) override | Bestimmt, ob ein Gradient skaliert ist. Schreiben [NullableBool](../nullablebool/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Setzt den Spiegelungsmodus für einen Gradient. Schreiben [Slides::TileFlip](../tileflip/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsam genutzten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsam genutzten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren mittels C# lock()-Statement. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wachobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [PVIObject](../pviobject/)
* Klasse [IGradientFormat](../igradientformat/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)