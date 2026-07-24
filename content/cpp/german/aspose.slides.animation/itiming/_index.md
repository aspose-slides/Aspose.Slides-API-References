---
title: ITiming
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Animationszeit dar.
type: docs
weight: 443
url: /de/aspose.slides.animation/itiming/
---
## ITiming Klasse

Stellt die Animationszeit dar.

```cpp
class ITiming : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Beschreibt den Prozentsatz der Beschleunigungsdauer des Effekts. Lesen **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Beschreibt, ob die Animation nach dem Abspielen in Vorwärtsrichtung automatisch in umgekehrter Richtung wiedergegeben wird. Lesen **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Beschreibt den Prozentsatz der Verzögerungsdauer des Effekts. Lesen **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Beschreibt die Dauer des Animationseffekts. Lesen **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Beschreibt, wie oft der Effekt wiederholt werden soll. Lesen **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Beschreibt, wie oft der Effekt wiederholt werden soll. Lesen **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Dieses Attribut gibt an, ob der Effekt bis zum Ende der Folie wiederholt wird. Lesen **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Dieses Attribut gibt an, ob der Effekt bis zum nächsten Klick wiederholt wird. Lesen **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Gibt an, ob ein Effekt nach Abschluss neu gestartet werden soll. Lesen [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückgespult wird. Lesen **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Gibt den Prozentsatz an, um den das Timing beschleunigt (oder verlangsamt) wird. Lesen **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Beschreibt die Verzögerungszeit nach dem Auslöser. Lesen **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Beschreibt den Auslösertyp. Lesen [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die mit dem Objekt verknüpfte Referenzzähler-Datenstruktur zurück. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zu C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zu C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wachobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zu C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht einen Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Beschreibt den Prozentsatz der Beschleunigungsdauer des Effekts. Schreiben **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Beschreibt, ob die Animation nach dem Abspielen in Vorwärtsrichtung automatisch in umgekehrter Richtung wiedergegeben wird. Schreiben **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Beschreibt den Prozentsatz der Verzögerungsdauer des Effekts. Schreiben **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Beschreibt die Dauer des Animationseffekts. Schreiben **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Beschreibt, wie oft der Effekt wiederholt werden soll. Schreiben **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Beschreibt, wie oft der Effekt wiederholt werden soll. Schreiben **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Dieses Attribut gibt an, ob der Effekt bis zum Ende der Folie wiederholt wird. Schreiben **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Dieses Attribut gibt an, ob der Effekt bis zum nächsten Klick wiederholt wird. Schreiben **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Gibt an, ob ein Effekt nach Abschluss neu gestartet werden soll. Schreiben [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückgespult wird. Schreiben **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Gibt den Prozentsatz an, um den das Timing beschleunigt (oder verlangsamt) wird. Schreiben **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Beschreibt die Verzögerungszeit nach dem Auslöser. Schreiben **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Beschreibt den Auslösertyp. Schreiben [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umstellen von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zu C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wachobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides::Animation](../)
* Bibliothek [Aspose.Slides](../../)