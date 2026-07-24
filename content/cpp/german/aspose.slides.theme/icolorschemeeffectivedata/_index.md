---
title: IColorSchemeEffectiveData
second_title: Aspose.Slides für C++ API-Referenz
description: Unveränderliches Objekt, das effektive Farbschemaeigenschaften enthält.
type: docs
weight: 157
url: /de/aspose.slides.theme/icolorschemeeffectivedata/
---
## IColorSchemeEffectiveData Klasse

Unveränderliches Objekt, das effektive Farbschemaeigenschaften enthält.

```cpp
class IColorSchemeEffectiveData : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent1](./get_accent1/)() | Erste Akzentfarbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent2](./get_accent2/)() | Zweite Akzentfarbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent3](./get_accent3/)() | Dritte Akzentfarbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent4](./get_accent4/)() | Vierte Akzentfarbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent5](./get_accent5/)() | Fünfte Akzentfarbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent6](./get_accent6/)() | Sechste Akzentfarbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark1](./get_dark1/)() | Erste dunkle Farbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark2](./get_dark2/)() | Zweite dunkle Farbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_FollowedHyperlink](./get_followedhyperlink/)() | Farbe für besuchte Hyperlinks. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Hyperlink](./get_hyperlink/)() | Farbe für Hyperlinks. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light1](./get_light1/)() | Erste helle Farbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light2](./get_light2/)() | Zweite helle Farbe im Schema. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [idx_get](./idx_get/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) | Gibt das Element am angegebenen Index zurück. Nur lesend [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des geteilten Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Anmerkungen

Diese Klasse wird als Teil von [IThemeEffectiveData](../ithemeeffectivedata/) verwendet.

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides::Theme](../)
* Library [Aspose.Slides](../../)