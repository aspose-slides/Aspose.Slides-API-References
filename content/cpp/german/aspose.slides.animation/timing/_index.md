---
title: Timing
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Animations-Timing dar.
type: docs
weight: 625
url: /de/aspose.slides.animation/timing/
---
## Timing Klasse


Stellt die Animationszeit dar.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_Accelerate](./get_accelerate/)() override | Beschreibt den Prozentsatz der Beschleunigungsdauer. Lesen **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Beschreibt, ob die Animation automatisch in umgekehrter Richtung abgespielt werden soll, nachdem sie in Vorwärtsrichtung abgespielt wurde. Lesen **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Beschreibt den Prozentsatz der Verzögerungsdauer des Verhaltens. Lesen **float**. |
| **float** [get_Duration](./get_duration/)() override | Beschreibt die Dauer des Animationseffekts. Lesen **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Beschreibt, wie oft der Effekt wiederholt werden soll. Lesen **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Beschreibt, wie oft der Effekt wiederholt werden soll. Lesen **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Dieses Attribut gibt an, ob der Effekt bis zum Ende der Folie wiederholt wird. Lesen **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Dieses Attribut gibt an, ob der Effekt bis zum nächsten Klick wiederholt wird. Lesen **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Gibt an, ob ein Effekt nach Abschluss neu gestartet werden soll. Lesen [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückgespult wird. Lesen **bool**. |
| **float** [get_Speed](./get_speed/)() override | Gibt den Prozentsatz an, um den das Timing beschleunigt (oder verlangsamt) werden soll. Lesen **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Beschreibt die Verzögerungszeit nach dem Auslöser. Lesen **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Beschreibt den Auslösertyp. Lesen [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Beschreibt den Prozentsatz der Beschleunigungsdauer. Schreiben **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Beschreibt, ob die Animation automatisch in umgekehrter Richtung abgespielt werden soll, nachdem sie in Vorwärtsrichtung abgespielt wurde. Schreiben **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Beschreibt den Prozentsatz der Verzögerungsdauer. Schreiben **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Beschreibt die Dauer des Animationseffekts. Schreiben **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Beschreibt, wie oft der Effekt wiederholt werden soll. Schreiben **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Beschreibt, wie oft der Effekt wiederholt werden soll. Schreiben **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Dieses Attribut gibt an, ob der Effekt bis zum Ende der Folie wiederholt wird. Schreiben **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Dieses Attribut gibt an, ob der Effekt bis zum nächsten Klick wiederholt wird. Schreiben **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Gibt an, ob ein Effekt nach Abschluss neu gestartet werden soll. Schreiben [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückgespult wird. Schreiben **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Gibt den Prozentsatz an, um den das Timing beschleunigt (oder verlangsamt) werden soll. Schreiben **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Beschreibt die Verzögerungszeit nach dem Auslöser. Schreiben **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Beschreibt den Auslösertyp. Schreiben [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des gemeinsamen Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht das Konvertieren benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ITiming](../itiming/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Namensraum [Aspose::Slides::Animation](../)
* Library [Aspose.Slides](../../)