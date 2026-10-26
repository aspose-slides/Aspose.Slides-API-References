---
title: ColorFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine in einer Präsentation verwendete Farbe dar.
type: docs
weight: 339
url: /de/aspose.slides/colorformat/
---
## ColorFormat Klasse


Stellt eine in einer Präsentation verwendete Farbe dar.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Kopiert das Farbformat von "color". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Prüft auf Gleichheit mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN nicht gleich einem beliebigen Wert ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN nicht gleich einem beliebigen Wert ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **uint8_t** [get_B](./get_b/)() override | Gibt die blaue Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lese **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). Setzt RGB-Farben und löscht alle Farbtransformationen. Lese [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Gibt die Farbtransformationsoperation zurück, die auf die Farbe am angegebenen Index angewendet wird. Lesen/Schreiben [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Gibt die Sammlung von Farbtransformationen zurück, die auf eine Farbe angewendet werden. Nur lesbar [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Gibt die Farbdefinitionsmethode zurück. Lese [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Gibt die blaue Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lese **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Gibt die grüne Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lese **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Gibt die rote Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lese **float**. |
| **uint8_t** [get_G](./get_g/)() override | Gibt die grüne Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. |
| **float** [get_Hue](./get_hue/)() override | Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück. Alle Farbtransformationen werden ignoriert. Lese **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück. Alle Farbtransformationen werden ignoriert. Lese **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Parent_Immediate-Objekt zurück. Nur lesbar [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt den übergeordneten [IPresentationComponent](../ipresentationcomponent/) zurück. Nur lesbar [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Gibt die Farbvoreinstellung zurück. Lese [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Gibt die rote Komponente einer Farbe zurück. Alle Farbtransformationen werden ignoriert. Lese **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück. Alle Farbtransformationen werden ignoriert. Lese **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Gibt die durch ein Farbschema identifizierte Farbe zurück. Lese [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück. Lese [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Holt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Holt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement zum Sperren. Direkt aufrufen oder das Sentinelle-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzen von Werttyp-Objekten mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_B](./set_b/)(**uint8_t**) override | Setzt die blaue Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreibe **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). Setzt RGB-Farben und löscht alle Farbtransformationen. Schreibe [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Setzt die Farbtransformationsoperation, die auf die Farbe am angegebenen Index angewendet wird. Lesen/Schreiben [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Setzt die Farbdefinitionsmethode. Schreibe [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Setzt die blaue Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreibe **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Setzt die grüne Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreibe **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Setzt die rote Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreibe **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Setzt die grüne Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. |
| void [set_Hue](./set_hue/)(**float**) override | Setzt die Farbtonkomponente einer Farbe in HSL-Darstellung. Alle Farbtransformationen werden ignoriert. Schreibe **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Setzt die Luminanzkomponente einer Farbe in HSL-Darstellung. Alle Farbtransformationen werden ignoriert. Schreibe **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Setzt die Farbvoreinstellung. Schreibe [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Setzt die rote Komponente einer Farbe. Alle Farbtransformationen werden ignoriert. Schreibe **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Setzt die Sättigungskomponente einer Farbe in HSL-Darstellung. Alle Farbtransformationen werden ignoriert. Schreibe **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Setzt die durch ein Farbschema identifizierte Farbe. Schreibe [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Setzt die durch die Systemfarbtabelle identifizierte Farbe. Schreibe [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Gibt ein [System::String](../../system/string/) zurück, das das aktuelle Farbformat darstellt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-Ausdruck typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C#-lock()-Statement zum Entsperren. Direkt aufrufen oder das Sentinelle-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [PVIObject](../pviobject/)
* Klasse [IColorFormat](../icolorformat/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)