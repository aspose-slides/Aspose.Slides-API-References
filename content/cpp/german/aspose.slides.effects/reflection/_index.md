---
title: Reflection
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Reflexionseffekt dar.
type: docs
weight: 1067
url: /de/aspose.slides.effects/reflection/
---
## Reflection Klasse


Stellt einen [Reflection](./) Effekt dar.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bestimmt, ob das angegebene [Reflection](./) gleich dem aktuellen [Reflection](./) ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) Radius. Lesen **double**. |
| **float** [get_Direction](./get_direction/)() override | Richtung der Spiegelung. Lesen **float**. |
| **double** [get_Distance](./get_distance/)() override | Abstand der Spiegelung. Lesen **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Gibt die Endposition (entlang der Alpha-Gradientenrampe) des End-Alpha-Wertes (Prozent) an. Lesen **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | End-Spiegelungs-Opazität (Prozent). Lesen **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Gibt die Richtung an, um die die Spiegelung verschoben wird (Winkel). Lesen **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Gibt das übergeordnete [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) zurück. Nur-Lese-[IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rechteckausrichtung. Lesen [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Gibt an, ob die Spiegelung mit der Form rotiert werden soll, wenn die Form rotiert wird. Lesen **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Gibt den horizontalen Skalierungsfaktor an, negative Skalierung verursacht ein Spiegeln (Prozent). Lesen **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Gibt den vertikalen Skalierungsfaktor an, negative Skalierung verursacht ein Spiegeln (Prozent). Lesen **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Gibt den horizontalen Schrägwinkel an. Lesen **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Gibt den vertikalen Schrägwinkel an. Lesen **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Gibt die Startposition (entlang der Alpha-Gradientenrampe) des Start-Alpha-Wertes (Prozent) an. Lesen **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Start-Spiegelungs-Opazität (Prozent). Lesen **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Nur-Lese-**uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Gibt wirksame [Reflection](./)-Effektdaten mit angewandter Vererbung zurück. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Dient als Hash-Funktion für einen bestimmten Typ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Objekttyp zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analog zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement. Direkt aufrufen oder [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenzvergleicht einen Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) Radius. Schreiben **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Richtung der Spiegelung. Schreiben **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Abstand der Spiegelung. Schreiben **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Gibt die Endposition (entlang der Alpha-Gradientenrampe) des End-Alpha-Wertes (Prozent) an. Schreiben **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | End-Spiegelungs-Opazität (Prozent). Schreiben **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Gibt die Richtung an, um die die Spiegelung verschoben wird (Winkel). Schreiben **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rechteckausrichtung. Schreiben [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Gibt an, ob die Spiegelung mit der Form rotiert werden soll, wenn die Form rotiert wird. Schreiben **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Gibt den horizontalen Skalierungsfaktor an, negative Skalierung verursacht ein Spiegeln (Prozent). Schreiben **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Gibt den vertikalen Skalierungsfaktor an, negative Skalierung verursacht ein Spiegeln (Prozent). Schreiben **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Gibt den horizontalen Schrägwinkel an. Schreiben **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Gibt den vertikalen Schrägwinkel an. Schreiben **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Gibt die Startposition (entlang der Alpha-Gradientenrampe) des Start-Alpha-Wertes (Prozent) an. Schreiben **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Start-Spiegelungs-Opazität (Prozent). Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte zu Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C#-lock()-Statement zum Entsperren. Direkt aufrufen oder [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IReflection](../ireflection/)
* Klasse [IVisualEffect](../ivisualeffect/)
* Klasse [IPVIObject](../../aspose.slides/ipviobject/)
* Namensraum [Aspose::Slides::Effects](../)
* Bibliothek [Aspose.Slides](../../)