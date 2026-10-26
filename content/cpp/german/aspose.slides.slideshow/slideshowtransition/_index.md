---
title: SlideShowTransition
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt den Folienübergang dar.
type: docs
weight: 404
url: /de/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition Klasse

Stellt den Folienübergang dar.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bestimmt, ob die beiden [SlideShowTransition](./) Instanzen gleich sind. Lesen/Schreiben **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-Stil des Gleitkommavergleichs, bei dem zwei NaNs als gleich betrachtet werden, obwohl laut IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-Stil des Gleitkommavergleichs, bei dem zwei NaNs als gleich betrachtet werden, obwohl laut IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lesen **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann zusammen mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatisches Vorwärtsblättern erfolgt. Lesen **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Gibt an, ob ein Mausklick die Folie vorwärts bewegt oder nicht. Wenn dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Lesen **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Ermittelt die Dauer des Folienübergangseffekts in Millisekunden. Lesen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Liefert die eingebetteten Audiodaten. Lesen [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Gibt an, ob dieser Sound ein integrierter Sound ist. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung aufgefordert, das name-Attribut dieses Sounds in ihrer Liste integrierter Sounds zu prüfen und ggf. einen benutzerdefinierten Namen oder eine UI anzuzeigen. Lesen **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Dieses Attribut gibt an, ob der Sound wiederholt wird, bis das nächste Sound-Ereignis in der Diashow eintritt. Lesen **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Setzt oder gibt den Soundmodus für den Folienübergang zurück. Lesen [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. Der [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) muss zugewiesen werden, um den Soundnamen zu erhalten oder zu setzen. Lesen [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. Lesen [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Typ des Übergangs. Lesen [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) Übergangswert anzeigen. Nur lesbar [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Dient als Hash-Funktion für einen bestimmten Typ, geeignet für Hash-Algorithmen und Datenstrukturen wie Hash-Tabellen. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C# lock() Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts wirklich, initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts wirklich, initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Schreiben **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann zusammen mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatisches Vorwärtsblättern erfolgt. Schreiben **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Gibt an, ob ein Mausklick die Folie vorwärts bewegt oder nicht. Wenn dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Schreiben **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Setzt die Dauer des Folienübergangseffekts in Millisekunden. Schreiben **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Setzt die eingebetteten Audiodaten. Schreiben [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Gibt an, ob dieser Sound ein integrierter Sound ist. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung aufgefordert, das name-Attribut dieses Sounds in ihrer Liste integrierter Sounds zu prüfen und ggf. einen benutzerdefinierten Namen oder eine UI anzuzeigen. Schreiben **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Dieses Attribut gibt an, ob der Sound wiederholt wird, bis das nächste Sound-Ereignis in der Diashow eintritt. Schreiben **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Setzt oder gibt den Soundmodus für den Folienübergang zurück. Schreiben [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. Der [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) muss zugewiesen werden, um den Soundnamen zu erhalten oder zu setzen. Schreiben [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. Schreiben [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Typ des Übergangs. Schreiben [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte zu einer Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock() Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Namensraum [Aspose::Slides::SlideShow](../)
* Bibliothek [Aspose.Slides](../../)