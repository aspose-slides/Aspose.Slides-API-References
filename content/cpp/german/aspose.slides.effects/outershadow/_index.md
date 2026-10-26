---
title: OuterShadow
second_title: Aspose.Slides für C++ API Referenz
description: Stellt einen Outer Shadow-Effekt dar.
type: docs
weight: 1041
url: /de/aspose.slides.effects/outershadow/
---
## OuterShadow Klasse

Stellt einen Outer Shadow-Effekt dar.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bestimmt, ob das angegebene [OuterShadow](./) gleich dem aktuellen [OuterShadow](./) ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) Radius in Punkten. Standardwert – 0 pt. Lesen **double**. |
| **float** [get_Direction](./get_direction/)() override | Richtung des Schattens in Grad. Standardwert – 0 ° (von links nach rechts). Lesen **float**. |
| **double** [get_Distance](./get_distance/)() override | Abstand des Schattens vom Objekt in Punkten. Standardwert – 0 pt. Lesen **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Gibt übergeordnetes [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) zurück. Nur-Lesen [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rechteckausrichtung. Standardwert – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Lesen [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Gibt an, ob der Schatten zusammen mit der Form rotiert. Standardwert – true. Lesen **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Horizontaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Lesen **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Vertikaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Lesen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Farbe des Schattens. Standardwert – automatisches Schwarz (themenabhängig). Nur-Lesen [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Horizontaler Schrägwinkel in Grad. Standardwert – 0 °. Lesen **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Vertikaler Schrägwinkel in Grad. Standardwert – 0 °. Lesen **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Nur-Lesen **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die mit dem Objekt verbundene Referenzzähler-Datenstruktur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Liefert die wirksamen Outer Shadow-Effektdaten mit angewendeter Vererbung. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Dient als Hashfunktion für einen bestimmten Typ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenzvergleicht Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) Radius in Punkten. Standardwert – 0 pt. Schreiben **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Richtung des Schattens in Grad. Standardwert – 0 ° (von links nach rechts). Schreiben **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Abstand des Schattens vom Objekt in Punkten. Standardwert – 0 pt. Schreiben **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rechteckausrichtung. Standardwert – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Schreiben [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Gibt an, ob der Schatten zusammen mit der Form rotiert. Standardwert – true. Schreiben **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Horizontaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Schreiben **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Vertikaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Schreiben **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Horizontaler Schrägwinkel in Grad. Standardwert – 0 °. Schreiben **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Vertikaler Schrägwinkel in Grad. Standardwert – 0 °. Schreiben **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt gemeinsam). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IOuterShadow](../ioutershadow/)
* Klasse [IVisualEffect](../ivisualeffect/)
* Klasse [IPVIObject](../../aspose.slides/ipviobject/)
* Namensraum [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)