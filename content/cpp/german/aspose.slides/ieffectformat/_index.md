---
title: IEffectFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Effekt-Eigenschaften einer Form dar.
type: docs
weight: 2029
url: /de/aspose.slides/ieffectformat/
---
## IEffectFormat Klasse

Stellt die Effekt-Eigenschaften einer Form dar.

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | Deaktiviert den Weichzeichnungseffekt. |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | Deaktiviert den Füllüberlagerungseffekt. |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | Deaktiviert den Leuchteffekt. |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | Deaktiviert den inneren Schatteneffekt. |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | Deaktiviert den äußeren Schatteneffekt. |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | Deaktiviert den voreingestellten Schatteneffekt. |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | Deaktiviert den Reflexionseffekt. |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | Deaktiviert den weichen Kanteneffekt. |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | Aktiviert den Füllüberlagerungseffekt. |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | Aktiviert den Leuchteffekt. |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | Aktiviert den inneren Schatteneffekt. |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | Aktiviert den äußeren Schatteneffekt. |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | Aktiviert den voreingestellten Schatteneffekt. |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | Aktiviert den Reflexionseffekt. |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | Aktiviert den weichen Kanteneffekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mittels C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | Weichzeichnungseffekt. Siehe [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Füllüberlagerungseffekt. Siehe [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | Leuchteffekt. Siehe [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Innerer Schatten. Siehe [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Gibt true zurück, wenn alle Effekte deaktiviert sind (wie bei einem gerade erstellten, standardmäßigen [EffectFormat](../effectformat/)-Objekt). Nur-Lese **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Äußerer Schatten. Siehe [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Voreingestellter Schatten. Siehe [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Reflexion. Siehe [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Weiche Kante. Siehe [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzählungs-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | Erhält die wirksamen Effektformatierungsdaten mit angewendeter Vererbung. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzwerttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die geteilte Referenzzählung um den angegebenen Wert. |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | Weichzeichnungseffekt. Schreiben [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | Füllüberlagerungseffekt. Schreiben [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | Leuchteffekt. Schreiben [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | Innerer Schatten. Schreiben [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | Äußerer Schatten. Schreiben [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | Voreingestellter Schatten. Schreiben [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | Reflexion. Schreiben [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | Weiche Kante. Schreiben [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | Setzt den Weichzeichnungseffekt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Erlaubt das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die geteilte Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IEffectParamSource](../ieffectparamsource/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)