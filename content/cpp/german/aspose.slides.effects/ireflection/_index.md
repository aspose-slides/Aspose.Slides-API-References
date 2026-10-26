---
title: IReflection
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Reflexionseffekt dar.
type: docs
weight: 937
url: /de/aspose.slides.effects/ireflection/
---
## IReflection Klasse

Stellt einen Reflexionseffekt dar.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) Radius. Lesen **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Richtung der Reflexion. Lesen **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Entfernung der Reflexion. Lesen **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Gibt die Endposition (entlang der Alpha-Gradientenrampe) des End-Alpha-Werts (Prozent) an. Lesen **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Ende der Reflexions-Opazität. (Prozent). Lesen **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Gibt die Richtung an, um die Reflexion zu versetzen. (Winkel). Lesen **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Rechteckausrichtung. Lesen [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Gibt an, ob die Reflexion mit der Form rotiert, wenn die Form rotiert wird. Lesen **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Gibt den horizontalen Skalierungsfaktor an, negative Skalierung bewirkt ein Spiegeln. (Prozent) Lesen **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Gibt den vertikalen Skalierungsfaktor an, negative Skalierung bewirkt ein Spiegeln. (Prozent) Lesen **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Gibt den horizontalen Schrägwinkel an. Lesen **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Gibt den vertikalen Schrägwinkel an. Lesen **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Gibt die Startposition (entlang der Alpha-Gradientenrampe) des Start-Alpha-Werts (Prozent) an. Lesen **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Start-Opazität der Reflexion. (Prozent). Lesen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Erhält effektive Daten mit angewandter Vererbung. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) Radius. Schreiben **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Richtung der Reflexion. Schreiben **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Entfernung der Reflexion. Schreiben **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Gibt die Endposition (entlang der Alpha-Gradientenrampe) des End-Alpha-Werts (Prozent) an. Schreiben **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Ende der Reflexions-Opazität. (Prozent). Schreiben **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Gibt die Richtung an, um die Reflexion zu versetzen. (Winkel). Schreiben **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Rechteckausrichtung. Schreiben [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Gibt an, ob die Reflexion mit der Form rotiert, wenn die Form rotiert wird. Schreiben **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Gibt den horizontalen Skalierungsfaktor an, negative Skalierung bewirkt ein Spiegeln. (Prozent) Schreiben **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Gibt den vertikalen Skalierungsfaktor an, negative Skalierung bewirkt ein Spiegeln. (Prozent) Schreiben **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Gibt den horizontalen Schrägwinkel an. Schreiben **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Gibt den vertikalen Schrägwinkel an. Schreiben **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Gibt die Startposition (entlang der Alpha-Gradientenrampe) des Start-Alpha-Werts (Prozent) an. Schreiben **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Start-Opazität der Reflexion. (Prozent). Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IImageTransformOperation](../iimagetransformoperation/)
* Klasse [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namensraum [Aspose::Slides::Effects](../)
* Bibliothek [Aspose.Slides](../../)