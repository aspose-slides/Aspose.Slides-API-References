---
title: IColorFormat
second_title: Aspose.Slides für C++ API Referenz
description: Stellt eine in einer Präsentation verwendete Farbe dar.
type: docs
weight: 1691
url: /de/aspose.slides/icolorformat/
---
## IColorFormat Klasse

Stellt eine in einer Präsentation verwendete Farbe dar.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Kopiert das Farbformat von \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **uint8_t** [get_B](./get_b/)() | Gibt die blaue Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lesen **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). Setzt RGB-Farben und löscht alle Farbtransformationen. Lesen [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Gibt die Farbtransformationsoperation zurück, die auf die Farbe am angegebenen Index angewendet wurde. Lesen/Schreiben [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Gibt die Sammlung der auf eine Farbe angewendeten Farbtransformationen zurück. Nur-Lesen [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Gibt die Farbdefinitionsmethode zurück. Lesen [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Gibt die blaue Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lesen **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Gibt die grüne Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lesen **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Gibt die rote Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lesen **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Gibt die grüne Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lesen **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück. Alle Farbtransformationen werden ignoriert. Lesen **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück. Alle Farbtransformationen werden ignoriert. Lesen **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Gibt die Farbvoreinstellung zurück. Lesen [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Gibt die rote Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lesen **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück. Alle Farbtransformationen werden ignoriert. Lesen **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Gibt die durch ein Farbschema identifizierte Farbe zurück. Lesen [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück. Lesen [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Setzt die blaue Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreiben **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). Setzt RGB-Farben und löscht alle Farbtransformationen. Schreiben [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Setzt die Farbtransformationsoperation, die auf die Farbe am angegebenen Index angewendet wird. Lesen/Schreiben [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Setzt die Farbdefinitionsmethode. Schreiben [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Setzt die blaue Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreiben **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Setzt die grüne Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreiben **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Setzt die rote Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreiben **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Setzt die grüne Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreiben **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Setzt die Farbtonkomponente einer Farbe in HSL-Darstellung. Alle Farbtransformationen werden ignoriert. Schreiben **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Setzt die Luminanzkomponente einer Farbe in HSL-Darstellung. Alle Farbtransformationen werden ignoriert. Schreiben **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Setzt die Farbvoreinstellung. Schreiben [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Setzt die rote Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreiben **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Setzt die Sättigungskomponente einer Farbe in HSL-Darstellung. Alle Farbtransformationen werden ignoriert. Schreiben **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Setzt die durch ein Farbschema identifizierte Farbe. Schreiben [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Setzt die durch die Systemfarbtabelle identifizierte Farbe. Schreiben [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Gibt ein [System::String](../../system/string/) zurück, das das aktuelle Farbformat darstellt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht das Konvertieren benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IFillParamSource](../ifillparamsource/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)